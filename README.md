# BoxToPlay MCP

Your game servers, managed in plain conversation.

Connect your BoxToPlay account to your AI assistant and simply ask for what you would normally click through in a control panel:

- "Why won't my Minecraft server start?" Your assistant checks its status, health report and latest logs, then tells you what is wrong and how to fix it.
- "Install the Create mod and restart the server." Done, and your assistant waits until it is back online before answering.

## What you can do

- **Fix problems faster**: your assistant reads crash logs, startup errors and server health for you and explains them in plain words.
- **Customize in seconds**: install modpacks, mods, plugins, datapacks and Bedrock add-ons, edit configuration files, manage worlds.
- **Stay in control**: start, stop and restart, schedule tasks, create backups before risky changes and restore them.
- **Run your whole community**: Minecraft servers, BungeeCord and Velocity networks, TeamSpeak servers and VPS, all from the same chat.

## Safe by design

You sign in with your own BoxToPlay account and choose what your assistant may do: read only, basic control or full access. It only reaches the services you own, and every change is marked so your client can ask for your approval first. It never buys, renews or pays for anything.

New to BoxToPlay? Create your Minecraft, TeamSpeak or VPS server at [boxtoplay.com](https://www.boxtoplay.com/), then connect it.

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
