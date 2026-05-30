# Imgur (imgur)

Imgur is a popular image and album hosting platform whose REST API (v3) exposes the full platform — upload, retrieve, vote, comment, gallery, account, tags, topics — over HTTP/JSON. Anonymous reads/writes are supported with a Client-ID; per-user actions use OAuth2 access tokens. Commercial use is routed through RapidAPI's metered tiers.

**URL:** [Visit APIs.json URL](https://apidocs.imgur.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Photography, Images, Image Hosting, Albums, Gallery, Social, Memes, Content Sharing, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Imgur API v3

RESTful HTTP/JSON API for Imgur covering images, albums, the public gallery, comments, accounts, tags, topics, meme generation, and notifications.

**Human URL:** [https://apidocs.imgur.com/](https://apidocs.imgur.com/)

**Base URL:** `https://api.imgur.com/3/`

#### Tags:

 - Images, Albums, Gallery, Comments, Accounts, Tags, OAuth2

#### Properties

- [Documentation](https://apidocs.imgur.com/)
- [OpenAPI](openapi/imgur-openapi.yml)
- [Authentication](https://apidocs.imgur.com/#authorization-and-oauth)
- [RateLimits](rate-limits/imgur-rate-limits.yml)
- [SignUp](https://api.imgur.com/oauth2/addclient)
- [JSONSchema — Image](json-schema/imgur-image-schema.json)
- [JSONSchema — Album](json-schema/imgur-album-schema.json)
- [JSONSchema — Comment](json-schema/imgur-comment-schema.json)
- [JSONSchema — Account](json-schema/imgur-account-schema.json)
- [JSONSchema — Gallery Item](json-schema/imgur-gallery-item-schema.json)
- [JSONSchema — Tag](json-schema/imgur-tag-schema.json)
- [JSONSchema — Access Token](json-schema/imgur-access-token-schema.json)
- [JSONStructure — Image](json-structure/imgur-image-structure.json)
- [JSONStructure — Album](json-structure/imgur-album-structure.json)
- [JSONStructure — Comment](json-structure/imgur-comment-structure.json)
- [JSONStructure — Account](json-structure/imgur-account-structure.json)
- [JSONStructure — Gallery Item](json-structure/imgur-gallery-item-structure.json)
- [Example — Upload Image](examples/imgur-uploadImage-example.json)
- [Example — Get Image](examples/imgur-getImage-example.json)
- [Example — Get Album](examples/imgur-getAlbum-example.json)
- [Example — Get Gallery](examples/imgur-getGallery-example.json)
- [Example — Create Comment](examples/imgur-createComment-example.json)
- [Example — Get Account](examples/imgur-getAccount-example.json)
- [Example — Issue Access Token](examples/imgur-issueAccessToken-example.json)
- [Example — Get Rate Limit Credits](examples/imgur-getRateLimitCredits-example.json)
- [Plans](plans/imgur-plans-pricing.yml)
- [FinOps](finops/imgur-finops.yml)

## Common Properties

- [Website](https://imgur.com/)
- [Portal](https://api.imgur.com/)
- [Documentation](https://apidocs.imgur.com/)
- [TermsOfService](https://imgur.com/tos)
- [PrivacyPolicy](https://imgur.com/privacy)
- [Support](https://help.imgur.com/)
- [Blog](https://imgur.com/blog)
- [GitHubOrganization](https://github.com/Imgur)
- [StackOverflow](https://stackoverflow.com/questions/tagged/imgur)
- [SDK — imgurpython](https://github.com/Imgur/imgurpython)
- [SDK — Hermes (iOS)](https://github.com/Imgur/Hermes)
- [SDK — Mandible](https://github.com/Imgur/mandible)
- [SDK — Incus](https://github.com/Imgur/incus)
- [SDK — incusjs](https://github.com/Imgur/incusjs)
- [SDK — Imgur.API (.NET)](https://github.com/DamienDennehy/Imgur.API)
- [SpectralRules](rules/imgur-rules.yml)
- [Vocabulary](vocabulary/imgur-vocabulary.yml)
- [JSON-LD](json-ld/imgur-context.jsonld)
- [NaftikoCapability — Shared Imgur](capabilities/shared/imgur.yaml)
- [NaftikoCapability — Share Image To Gallery](capabilities/share-image-to-gallery.yaml)
- [NaftikoCapability — Build Album](capabilities/build-album.yaml)
- [NaftikoCapability — Moderate Comments](capabilities/moderate-comments.yaml)

## Features

| Name | Description |
|------|-------------|
| Image Upload | Anonymous or authenticated upload via binary, base64, or remote URL. |
| Albums | Group images into ordered, privacy-aware collections. |
| Public Gallery | Hot / top / user sections with sort and time windows. |
| Comments & Voting | Threaded comments and up/down voting on gallery items. |
| Tags & Topics | Folksonomy tagging and editor-curated topic channels. |
| Meme Generation | Generate memes from default templates. |
| Notifications | Per-user notification feed for replies, followers, and gallery events. |
| Rate-Limit Introspection | GET /3/credits returns current client and user quota usage. |

## Use Cases

| Name | Description |
|------|-------------|
| User-Generated Content Hosting | Apps and forums offload image hosting to Imgur's free Client-ID tier. |
| Meme & Social Content Pipelines | Bots and Discord/Reddit integrations upload generated images on the fly. |
| Screenshot Sharing | Desktop tools (ShareX, Greenshot) push screenshots to anonymous Imgur links. |
| Mobile App Image Pipelines | iOS/Android apps use the iOS/Android SDKs to upload user photos. |
| Gallery Content Curation | Editors fetch hot/top gallery feeds to surface trending images on third-party sites. |

## Integrations

| Name | Description |
|------|-------------|
| Reddit | Imgur grew up alongside Reddit; Reddit posts frequently embed Imgur links. |
| Discord | Many Discord bots use Imgur for ephemeral image storage. |
| ShareX | Popular Windows screenshot tool uploads directly to Imgur via Client-ID. |
| RapidAPI | Commercial Imgur API access is routed through RapidAPI's marketplace. |
| imgurpython, Imgur.API, Hermes | Official and community SDKs cover Python, .NET, Swift, and Go ecosystems. |

## Solutions

| Name | Description |
|------|-------------|
| Free Anonymous Tier | Client-ID based, non-commercial use within daily/hourly quotas at $0. |
| OAuth2 User Tier | Per-user authenticated access for apps acting on behalf of an Imgur user. |
| RapidAPI Commercial Tiers | Basic / Pro / Ultra / Mega tiers on RapidAPI for commercial use cases. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Imgur API v3 OpenAPI](openapi/imgur-openapi.yml)

### JSON Schema

- [Image](json-schema/imgur-image-schema.json)
- [Album](json-schema/imgur-album-schema.json)
- [Comment](json-schema/imgur-comment-schema.json)
- [Account](json-schema/imgur-account-schema.json)
- [Gallery Item](json-schema/imgur-gallery-item-schema.json)
- [Tag](json-schema/imgur-tag-schema.json)
- [Access Token](json-schema/imgur-access-token-schema.json)

### JSON Structure

- [Image](json-structure/imgur-image-structure.json)
- [Album](json-structure/imgur-album-structure.json)
- [Comment](json-structure/imgur-comment-structure.json)
- [Account](json-structure/imgur-account-structure.json)
- [Gallery Item](json-structure/imgur-gallery-item-structure.json)

### JSON-LD

- [Imgur Context](json-ld/imgur-context.jsonld)

### Examples

- [Upload Image](examples/imgur-uploadImage-example.json)
- [Get Image](examples/imgur-getImage-example.json)
- [Get Album](examples/imgur-getAlbum-example.json)
- [Get Gallery](examples/imgur-getGallery-example.json)
- [Create Comment](examples/imgur-createComment-example.json)
- [Get Account](examples/imgur-getAccount-example.json)
- [Issue Access Token](examples/imgur-issueAccessToken-example.json)
- [Get Rate Limit Credits](examples/imgur-getRateLimitCredits-example.json)

### Plans, Rate Limits, FinOps

- [Plans & Pricing](plans/imgur-plans-pricing.yml)
- [Rate Limits](rate-limits/imgur-rate-limits.yml)
- [FinOps Mapping](finops/imgur-finops.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Imgur](capabilities/shared/imgur.yaml) — 14 operations for image, album, gallery, comment, account, and rate-limit surfaces

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Share Image To Gallery](capabilities/share-image-to-gallery.yaml) | Imgur | 3 | Content Publisher |
| [Build Album](capabilities/build-album.yaml) | Imgur | 2 | Photo Curator |
| [Moderate Comments](capabilities/moderate-comments.yaml) | Imgur | 3 | Community Moderator |

## Vocabulary

- [Imgur Vocabulary](vocabulary/imgur-vocabulary.yml) — Controlled vocabulary spanning 10 resources, 5 actions, OAuth2/Client-ID authentication, reputation tiers, and gallery enumerations.

## Rules

- [Imgur Spectral Rules](rules/imgur-rules.yml) — 10 rules enforcing Imgur API v3 conventions: server URL, path prefixes, operation summary case, operationId presence, security schemes, and parameter naming.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
