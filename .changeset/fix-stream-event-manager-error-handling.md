---
'@cherrystudio/ai-core': patch
---

Fix assistant silently hanging after MCP tool call by restoring error handling in recursive stream calls and adding timeout protection
