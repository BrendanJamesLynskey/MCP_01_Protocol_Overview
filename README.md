# The Model Context Protocol — A Visual Tour

What MCP actually is on the wire — JSON-RPC 2.0 primitives, host/client/server topology, capability negotiation, the full lifecycle, and the version timeline from `2024-11-05` to `2026-07-28`. Includes an end-to-end annotated handshake, and the same exchange under the stateless 2026-07-28 revision.

Covers both protocol eras: the handshake era (`initialize`, up to `2025-11-25`) and the stateless `2026-07-28` revision (per-request `_meta`, `server/discover`, no sessions). New slides 06b and 08b; handshake-era material is tagged "before 2026-07-28". Every changed claim cites the [2026-07-28 specification](https://modelcontextprotocol.io/specification/2026-07-28/changelog) (accessed 2026-10-08). Animated companion: [Agent Protocols Explained](https://agent-protocols-explained.vercel.app).

**Live site:** https://brendanjameslynskey.github.io/MCP_01_Protocol_Overview/

Part of the [Model Context Protocol series](https://github.com/BrendanJamesLynskey/LLMs#model-context-protocol-mcp).
