# arknetz-moderation

ArkNetzWebWeaver central moderation file (MIT). Root Master only — enforced
by GitHub repo write permissions, never by a secret in the app.

- `moderation.json.zst` — canonical file (empty seed: `{"patches":[]}`,
  22 bytes). `moderation.json` is the plain mirror.
- Resolution order before rendering: Root Master → Parent Registrar → Post
  Author (PROTOCOL.md §3.4).

Seed state (2026-11-20): no patches. Test seed data only.
