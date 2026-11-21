# arknetz-moderation

ArkNetzWebWeaver central moderation file (MIT). Root Master only — enforced
by GitHub repo write permissions, never by a secret in the app.

- `moderation.json.zst` — canonical file (live empty state: `{"patches":[]}`,
  37 bytes). `moderation.json` is the plain mirror.
- Resolution order before rendering: Root Master → Parent Registrar → Post
  Author (PROTOCOL.md §3.4).

Live state: no patches. The Root Master adds a patch here only when content
needs removing or replacing — an empty file means nothing is moderated right now.
