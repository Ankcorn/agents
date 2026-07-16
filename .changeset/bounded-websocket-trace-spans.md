---
"agents": patch
"@cloudflare/ai-chat": patch
"@cloudflare/think": patch
---

Bound custom spans to the hibernatable WebSocket invocation so cancellation and disconnects cannot leave agent, turn, inference, model, or result spans open. RPC and alarm turns retain full-stream span lifetimes.
