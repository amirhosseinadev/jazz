---
"jazz-tools": patch
---

Keep the cached catalogue announcement fingerprint across writes and derived-cache fills, share a maintained subscription's output tables instead of copying them on every update, and borrow table schemas during query validation. A cold browser client spent about 40% less worker CPU opening a large schema.
