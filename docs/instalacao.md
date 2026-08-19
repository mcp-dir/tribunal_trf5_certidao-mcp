# Instalação detalhada

Tribunal TRF5: Certidão Negativa Cível e Criminal é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_tribunal_trf5_certidao`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_tribunal_trf5_certidao` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_tribunal_trf5_certidao` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_tribunal_trf5_certidao` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.tribunal_trf5_certidao` (ou `servers.tribunal_trf5_certidao` no VS Code) do config do cliente e reinicie.
