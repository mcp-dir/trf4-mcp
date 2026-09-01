# Instalação detalhada

Jurisprudência TRF4 é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_trf4`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_trf4` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_trf4` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_trf4` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.trf4` (ou `servers.trf4` no VS Code) do config do cliente e reinicie.
