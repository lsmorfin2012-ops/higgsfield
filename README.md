# higgsfield

## Higgsfield MCP server

This repo is configured to use the Higgsfield MCP server via [`.mcp.json`](./.mcp.json):

```json
{
  "mcpServers": {
    "higgsfield": {
      "type": "http",
      "url": "https://mcp.higgsfield.ai/mcp"
    }
  }
}
```

When you open this project in Claude Code, it will prompt you to approve the
`higgsfield` MCP server defined in `.mcp.json`. Once approved, the
Higgsfield tools become available in your session. If the server requires
authentication, follow its OAuth/API-key flow when prompted.
.
