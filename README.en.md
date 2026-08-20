# DPVAT: Emissão de Guia

### DPVAT: Emissão de Guia for Claude, ChatGPT and AI agents

DPVAT: Issuance de Guia, official-source lookup. Platform-hosted, pay per query with prepaid credit.

- 📊 **1 tool**
- 🔒 **Read-only**
- 💬 **Works with any MCP client**: Claude Desktop, Cursor, VS Code, Cline, Continue
- 🔑 **Magic-link login (no password)**

[Portuguese version](README.md) · [Full docs (PT-BR)](docs/)

---

## One-click install

### Claude (Web and Desktop)

[➕ Open in Claude and connect](https://claude.ai/new?modal=add-custom-connector#settings/customize-connectors)

Manual: [claude.ai/customize/connectors](https://claude.ai/customize/connectors?surface=cowork) → **+** → **Add custom connector** → name `DPVAT: Emissão de Guia`, URL `https://api.mcp.ai/p_dpvat_guia`.

### Cursor

[➕ Install in Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=dpvat_guia&config=eyJ1cmwiOiJodHRwczovL2FwaS5tY3AuYWkvcF9kcHZhdF9ndWlhIn0=)

### VS Code (Copilot Chat)

[➕ Install in VS Code](vscode:mcp/install?name=dpvat_guia&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fapi.mcp.ai%2Fp_dpvat_guia%22%7D)

### Any other MCP-over-HTTP client

```
https://api.mcp.ai/p_dpvat_guia
```

---

## 1 tool

| Tool | Description |
|---|---|
| `dpvat_guia_consultar` | DPVAT: Emissão de Guia, consulta em fonte oficial. |

---

## Pricing

See [docs/precos.md](docs/precos.md) (PT-BR).

---

## License

MIT — see [LICENSE](LICENSE). The MCP server at `api.mcp.ai/p_dpvat_guia` is proprietary (hosted); this repo (manifests, docs, skills) is MIT.
