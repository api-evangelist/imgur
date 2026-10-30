# Imgur

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Imgur is a popular image and album hosting platform whose REST API (v3) exposes the full platform — upload, retrieve, vote, comment, gallery, account, tags, topics — over HTTP/JSON. Anonymous reads/writes are supported with a Client-ID; per-user actions use OAuth2 access tokens. Commercial use is routed through RapidAPI's metered tiers.

**Areas:** Photography · Image · Image Hosting · Albums · Gallery · Social · Memes · Content Sharing · Public APIs

## Imgur on APIs.io

Everything profiled for Imgur is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/imgur/](https://apis.io/providers/imgur/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [Imgur Account API](https://apis.io/apis/imgur/imgur-account-api/) — Account-scoped data: profile, images, albums, favorites, settings, notifications.
- [Imgur Album API](https://apis.io/apis/imgur/imgur-album-api/) — Album creation, retrieval, and image-management operations.
- [Imgur Auth API](https://apis.io/apis/imgur/imgur-auth-api/) — OAuth2 token issuance and refresh.
- [Imgur Comment API](https://apis.io/apis/imgur/imgur-comment-api/) — Comments on gallery items.
- [Imgur Gallery API](https://apis.io/apis/imgur/imgur-gallery-api/) — Public gallery listing, voting, sharing, and reporting.
- [Imgur Image API](https://apis.io/apis/imgur/imgur-image-api/) — Image upload, retrieval, deletion, favorite, and update operations.
- [Imgur Memegen API](https://apis.io/apis/imgur/imgur-memegen-api/) — Meme generation and meme defaults.
- [Imgur Notification API](https://apis.io/apis/imgur/imgur-notification-api/) — User notification retrieval and dismissal.
- [Imgur Tags API](https://apis.io/apis/imgur/imgur-tags-api/) — Tag-based gallery browsing and tagging of gallery items.
- [Imgur Topic API](https://apis.io/apis/imgur/imgur-topic-api/) — Topic listings and topic galleries.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (7)

The data models the API reads and writes.

- [Imgur OAuth2 Access Token](https://apis.io/schemas/imgur/imgur-access-token/)
- [Imgur Account](https://apis.io/schemas/imgur/imgur-account/)
- [Imgur Album](https://apis.io/schemas/imgur/imgur-album/)
- [Imgur Comment](https://apis.io/schemas/imgur/imgur-comment/)
- [Imgur Gallery Item](https://apis.io/schemas/imgur/imgur-gallery-item/)
- [Imgur Image](https://apis.io/schemas/imgur/imgur-image/)
- [Imgur Tag](https://apis.io/schemas/imgur/imgur-tag/)

#### JSON Structure (5)

Data models expressed in JSON Structure.

- [Imgur Account Structure](https://apis.io/json-structure/imgur/imgur-account-structure/)
- [Imgur Album Structure](https://apis.io/json-structure/imgur/imgur-album-structure/)
- [Imgur Comment Structure](https://apis.io/json-structure/imgur/imgur-comment-structure/)
- [Imgur Gallery Item Structure](https://apis.io/json-structure/imgur/imgur-gallery-item-structure/)
- [Imgur Image Structure](https://apis.io/json-structure/imgur/imgur-image-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Imgur Context](https://apis.io/jsonld/imgur/imgur-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Imgur Vocabulary](https://apis.io/vocabularies/imgur/imgur-vocabulary/)

#### Examples (8)

Example requests and responses.

- [Imgur Createcomment Example](https://apis.io/examples/imgur/imgur-createComment-example/)
- [Imgur Getaccount Example](https://apis.io/examples/imgur/imgur-getAccount-example/)
- [Imgur Getalbum Example](https://apis.io/examples/imgur/imgur-getAlbum-example/)
- [Imgur Getgallery Example](https://apis.io/examples/imgur/imgur-getGallery-example/)
- [Imgur Getimage Example](https://apis.io/examples/imgur/imgur-getImage-example/)
- [Imgur Getratelimitcredits Example](https://apis.io/examples/imgur/imgur-getRateLimitCredits-example/)
- [Imgur Issueaccesstoken Example](https://apis.io/examples/imgur/imgur-issueAccessToken-example/)
- [Imgur Uploadimage Example](https://apis.io/examples/imgur/imgur-uploadImage-example/)

#### Collections (10)

Postman and Open Collection request collections.

- [Imgur Account API](https://apis.io/collections/imgur/open-imgur-account-api/)
- [Imgur Album API](https://apis.io/collections/imgur/open-imgur-album-api/)
- [Imgur Auth API](https://apis.io/collections/imgur/open-imgur-auth-api/)
- [Imgur Comment API](https://apis.io/collections/imgur/open-imgur-comment-api/)
- [Imgur Gallery API](https://apis.io/collections/imgur/open-imgur-gallery-api/)
- [Imgur Image API](https://apis.io/collections/imgur/open-imgur-image-api/)
- [Imgur Memegen API](https://apis.io/collections/imgur/open-imgur-memegen-api/)
- [Imgur Notification API](https://apis.io/collections/imgur/open-imgur-notification-api/)
- [Imgur Tags API](https://apis.io/collections/imgur/open-imgur-tags-api/)
- [Imgur Topic API](https://apis.io/collections/imgur/open-imgur-topic-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Imgur — jsonschema rules](https://apis.io/rules/imgur/imgur-jsonschema-spectral-rules/)
- [Imgur API Rules](https://apis.io/rules/imgur/imgur-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Imgur Domain Security](https://apis.io/security/imgur/imgur-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Imgur Plans Pricing](https://apis.io/plans/imgur/imgur-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Imgur Rate Limits](https://apis.io/rate-limits/imgur/imgur-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Imgur Finops](https://apis.io/finops/imgur/imgur-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://imgur.com/)
- [Documentation](https://apidocs.imgur.com/)
- [Support](https://help.imgur.com/)
- [Blog](https://imgur.com/blog)
- [Terms of service](https://imgur.com/tos)
- [Privacy policy](https://imgur.com/privacy)
- [GitHub](https://github.com/Imgur)

## API Evangelist rating

**Kin Score 46.6** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 62.0 |
| Contract governance | 27.3 |
| Operational transparency | 10.5 |
| Developer ergonomics | 50.0 |
| Access clarity | 42.1 |

**Agent readiness 21.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 24.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/imgur/](https://apis.io/providers/imgur/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Imgur: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/imgur/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
