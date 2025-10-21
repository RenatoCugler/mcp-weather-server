```markdown
# MCP Weather Server — Sample Project

This repository is a small sample project: my first MCP (Model Context Protocol) server.

It was created as an exercise following the tutorial linked below. 
Thank you to the original author for the guide and inspiration.

Credits
-------
- Tutorial / inspiration: Debs O'Brien (debs_obrien)
	- https://dev.to/debs_obrien/building-your-first-mcp-server-a-beginners-tutorial-5fag

Quick start
-----------
- Requirements: Node.js (18+ recommended), npm
- Install dependencies:

```bash
npm install
```

- Run (development):

```bash
node main.ts
```

Notes
-----
- This project exposes a simple `get-weather` tool using the MCP server SDK. The
	implementation calls Open-Meteo APIs to resolve a city to coordinates and fetch
	current/hourly weather data.
- See `main.ts` for implementation details.

If you'd like, I can add a small example client or a test harness to demonstrate
calling the server locally.
```