# ⚠️ mcp-vulnerable-fixture

**Intentionally vulnerable MCP server for testing [`mcp-vetter-agent`](https://github.com/hemv-857/mcp-vetter-agent).**

## Warning

- This software contains **deliberate security vulnerabilities**.
- **Do not deploy** this server to any public or production environment.
- **Do not connect** this server to an agent or client you care about.
- Use only in isolated local/sandbox environments for security-audit testing.

## Purpose

Provides a known-bad MCP server so `mcp-vetter-agent` can demonstrate detection of insecure tool definitions, missing auth, prompt-injection surfaces, and related issues.

## License

MIT — but again: intentionally insecure, testing only.
