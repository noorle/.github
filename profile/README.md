# Noorle — The Agent Runtime

Noorle gives AI agents one secure MCP endpoint: built-in tools, custom WASM plugins, and 1,000+ connectors — auth, rate limits, and audit logs included.

Each gateway is a single authenticated MCP endpoint (`mcp-{id}.noorle.com`) that aggregates three kinds of capabilities:

- **Built-in tools** — Web Search, Code Runner, Files, HTTP Client, Browser, Sandbox, and Knowledge Retrieval, ready out of the box.
- **Custom plugins** — your own logic as sandboxed WebAssembly, written in Python, TypeScript, JavaScript, Go, or Rust.
- **Connectors** — external services via REST/OpenAPI import or any MCP server.

Works with any MCP-compatible client — Claude Desktop, Claude Code, Cursor, Continue.dev, Cline, or your own agents — over Streamable HTTP or stateless HTTP. Setup takes about five minutes, and there's no infrastructure to host.

## Get started

- 🚀 [Five-minute quickstart](https://noorle.com/docs/use/five-minute-quickstart)
- 📚 [Documentation](https://noorle.com/docs/)
- 🔌 [MCP gateways](https://noorle.com/platform/mcp-gateways/)
- 🧩 [Plugin examples](https://github.com/noorle/plugin-examples) · [CLI releases](https://github.com/noorle/cli-releases)
- 💲 [Pricing](https://noorle.com/pricing/) — $10 free credit, no credit card required

## Connect an MCP client

```bash
claude mcp add --transport http noorle https://mcp-{gateway-id}.noorle.com \
  --header "X-API-Key: $NOORLE_API_KEY"
```

---

[Website](https://noorle.com/) · [Docs](https://noorle.com/docs/) · [X](https://x.com/NoorleHQ) · [LinkedIn](https://www.linkedin.com/company/noorle) · support@noorle.com
