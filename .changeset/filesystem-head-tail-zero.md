---
"@modelcontextprotocol/server-filesystem": patch
---

Return empty result for `read_text_file` when `head: 0` or `tail: 0`, and enforce non-negative integer schemas (#5184).
