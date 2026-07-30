# Level Headed Games

Level Headed Games (Level Headed, LLC) is an independent video game studio building an original online
cooperative multiplayer game. The studio describes itself as passionate about making immersive
experiences that let players express themselves and have fun with their friends, and is building "fun,
surprising, and heavily social video game worlds." Development is community-involved, with an open call
for co-op players to join an Alpha playtest community.

Backed by: a16z (surfaced from the a16z investment list; not confirmed on the studio's own site)

## API surface

**None.** As of the 2026-07-19 enrichment pass this studio publishes no API, SDK, developer
documentation, developer portal, changelog, status page, or public GitHub organization. Its only public
web property is a single-page marketing site. This profile is retained as a venture-portfolio company
record, not as an API provider.

Probed and confirmed absent: `/.well-known/security.txt`, `/.well-known/openid-configuration`,
`/.well-known/oauth-authorization-server`, `/.well-known/api-catalog`, `/.well-known/ai-plugin.json`,
`/llms.txt`, `/openapi.json`, `/docs`, `/developers`, `/api`.

## Identity caveat

The a16z investment-list entry supplied only a company name with no URL. `levelheadedgames.com` was
matched on exact name, sector, and the `level-headed-games` LinkedIn slug. The binding is **probable,
not verified** — see `x-identity-note` in `apis.yml`.

## Artifacts

- `security/level-headed-games-domain-security.yml` — probed TLS/HSTS/DNS posture
- `well-known/level-headed-games-well-known.yml` — negative discovery-surface probe record
- `llms/level-headed-games-llms.txt` — generated catalog summary
