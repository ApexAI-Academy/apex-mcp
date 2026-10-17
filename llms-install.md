# Installing Apex MCP (for AI agents)

Apex MCP is a hosted remote server. Nothing to install or build.

1. Add a remote MCP server named `apex` with URL `https://apexai.academy/mcp` (transport: Streamable HTTP).
2. No key is needed for public tools. If the user has an Apex Premium API key, send it as the header `Authorization: Bearer <key>`. Ask the user for it; never guess or log it.
3. Verify: call `list_courses`. It should return the published courses.

Example config:

```json
{ "mcpServers": { "apex": { "url": "https://apexai.academy/mcp" } } }
```

More: https://apexai.academy/llms.txt
