---
'@modelcontextprotocol/server': patch
---

Restore a reused server's existing `onclose` handler after each modern exchange so application cleanup callbacks continue to run.
