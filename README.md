<p align="center">
  <img src="logo.svg" width="96" height="96" alt="Protocol Career logo">
</p>

# Protocol Career MCP

**Practice consulting drills and prepare for case interviews at the top US consulting firms, from any MCP client.**

| | |
|---|---|
| **Name** | `protocol-career` |
| **Repository** | https://github.com/Holox76000/protocol-career-mcp |
| **Server URL** | `https://protocol-club.com/api/mcp` |
| **Transport** | Streamable HTTP (remote, stateless) |
| **Authentication** | None |
| **Logo** | [`logo.svg`](logo.svg) |
| **Website** | https://protocol-club.com |

## Short description

Practice consulting drills and prepare for case interviews at the top US consulting firms.

## Long description

Protocol Career MCP brings [Protocol Career](https://protocol-club.com) interview preparation into your AI assistant. Connect it to any MCP client to train on consulting drills and get ready for interviews at the major US consulting firms — McKinsey, BCG, Bain and the rest of the field.

Use it to:

- **Run drills** — work the skills interviewers test, such as mental math, market sizing, structuring and chart reading, in short repeatable sessions.
- **Practise case interviews** — go through a case end to end, the way it is run in a real interview.
- **Prepare the fit interview** — rehearse personal experience and behavioural answers.

It is a remote server: there is nothing to install and no API key to manage.

## Connect

Add the server URL to your MCP client as a remote (Streamable HTTP) server.

**Claude Code**

```bash
claude mcp add --transport http protocol-career https://protocol-club.com/api/mcp
```

**Generic `mcp.json`**

```json
{
  "mcpServers": {
    "protocol-career": {
      "type": "http",
      "url": "https://protocol-club.com/api/mcp"
    }
  }
}
```

## Registry

[`server.json`](server.json) is the entry for the [Official MCP Registry](https://registry.modelcontextprotocol.io).

## Links

- Website: https://protocol-club.com
- Issues: https://github.com/Holox76000/protocol-career-mcp/issues
