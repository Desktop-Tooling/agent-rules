# Desktop-Tooling org overlay

Shared rules and Cursor skills live in **dev-centr/agent-rules**. This repo is the org overlay only - it does not vendor a snapshot.

When assembling context for this org's repos, resolve:

- `AGENT_RULES_PATH` = `$CODE_ROOT/github.com/dev-centr/agent-rules`
- Org overlay = this `AGENTS.md`
- `ORG` = `Desktop-Tooling`
- Site = `https://desktop-tooling.github.io` (SolidStart static, GitHub Pages, no Cloudflare)
- Docs hub = `https://desktop-tooling.github.io/docs/` (Antora + Valentus v2)

This org owns OS-level desktop utilities (Explorer, shell extensions, theming, launchers, windowing). It does not own shells (`openshellorg`), HCI research (`HCI-Nerdz`), or developer-machine tooling (`dev-centr`).

Shared changes: PR `dev-centr/agent-rules`. Org-only: commit here.
