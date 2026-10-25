# BoxToPlay MCP

Remote MCP server for BoxToPlay hosting. Manage the Minecraft servers, BungeeCord / Velocity proxies, TeamSpeak servers and VPS you own at BoxToPlay from an MCP-compatible client.

The server runs at `https://api.boxtoplay.com/mcp`.

## Use it

Connect the server, sign in with your BoxToPlay account and choose an access profile. Then ask your assistant to check the status of a server, read its latest logs, restart it, install a modpack or a plugin, manage backups or administer a VPS. Long operations run as jobs that the assistant follows until they finish. Tools that change a service are marked as destructive, so your client can ask for your approval before running them.

## Connect

- MCP endpoint: `https://api.boxtoplay.com/mcp`
- Transport: Streamable HTTP
- Auth: OAuth, or a BoxToPlay API key as `Authorization: Bearer`

Developer documentation: [https://api.boxtoplay.com/docs](https://api.boxtoplay.com/docs)

OpenAPI: [https://api.boxtoplay.com/v1/openapi.json](https://api.boxtoplay.com/v1/openapi.json)

## Data

This package contains no code. It only points your MCP client to `https://api.boxtoplay.com/mcp`. When a tool runs, the client sends its arguments, such as a server identifier, a file content or a command, to BoxToPlay over HTTPS under your BoxToPlay account. The server acts only on the services owned by that account. The package itself stores nothing.

Privacy policy: [https://www.boxtoplay.com/en/privacy](https://www.boxtoplay.com/en/privacy)

## License

MIT. See `LICENSE`.
