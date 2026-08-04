# Level Headed Games

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
