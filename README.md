# Epic Games (epic-games)

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

Epic Games is the studio behind Fortnite, the Unreal Engine, the Epic Games Store, MetaHuman, RealityScan, Twinmotion, RAD Game Tools, and the Epic Online Services (EOS) backend. Epic operates a unified developer portal at dev.epicgames.com that hosts the EOS SDK and REST APIs (Auth, Connect, Friends, Presence, Lobby, Sessions, Achievements, Stats, Leaderboards, Player Data Storage, Title Storage, Voice, Sanctions, Anti-Cheat, Reports, P2P, Ecom, User Info), the Unreal Engine documentation, the Epic Games Store publishing tools, and the Kids Web Services (KWS) compliance platform. EOS is cross-platform and runs on Windows, macOS, Linux, PlayStation, Xbox, Switch, iOS, Android, and web. This profile rolls Epic's developer-facing surfaces into a single index; the Unreal Engine surface has its own dedicated profile.

**APIs.json:** [https://www.epicgames.com](https://www.epicgames.com)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- Achievements
- Anti-Cheat
- Cross-Platform
- EOS
- Epic Online Services
- Game Backend
- Game Development
- Games
- Identity
- Lobby
- Matchmaking
- Multiplayer
- Sessions
- Unreal Engine
- Voice

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-23

## APIs

### Epic Online Services (EOS)

Epic Online Services is Epic's free cross-platform backend for games. EOS exposes both a native C/C++ SDK (with Unity, Unreal, and platform wrappers) and a set of REST web services covering identity (Epic Account Services, Connect, Auth), social (Friends, Presence, Blocklist), play (Lobby, Sessions, P2P, Voice), progression (Achievements, Stats, Leaderboards), storage (Player Data Storage, Title Storage), integrity (Anti-Cheat, Sanctions, Reports), and commerce (Ecom). All EOS APIs are gated behind an Epic developer organization, sandbox, and client credentials issued in the EOS Developer Portal.

- **Human URL:** [https://dev.epicgames.com/en-US/services/epic-online-services](https://dev.epicgames.com/en-US/services/epic-online-services)
- **Base URL:** `https://api.epicgames.dev`

#### Tags

- Achievements
- Anti-Cheat
- EOS
- Game Backend
- Identity
- Lobby
- Sessions
- Voice

#### Properties

- [Portal](https://dev.epicgames.com)
- [Documentation](https://dev.epicgames.com/docs/epic-online-services)
- [Getting Started](https://dev.epicgames.com/docs/epic-online-services/eos-get-started)
- [SDK](https://dev.epicgames.com/docs/epic-online-services/platform-sdks)
- [Web A P I](https://dev.epicgames.com/docs/web-api-ref)
- [Postman Collection](collections/epic-games.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/epic-games.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Epic Account Services

Epic Account Services provides OAuth 2.0 / OIDC sign-in with an Epic Account, exposing user identity, display name, country, preferred language, and linked-account information to integrating games and tools. It powers cross-platform Epic login and is the identity layer underneath EOS Auth.

- **Human URL:** [https://dev.epicgames.com/docs/epic-account-services](https://dev.epicgames.com/docs/epic-account-services)
- **Base URL:** `https://api.epicgames.dev`

#### Tags

- Authentication
- Identity
- OAuth
- OIDC
- SSO

#### Properties

- [Documentation](https://dev.epicgames.com/docs/epic-account-services)
- [Authentication](https://dev.epicgames.com/docs/epic-account-services/auth-interface)
- [Postman Collection](collections/epic-games.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/epic-games.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Epic Games Store Publishing

The Epic Games Store publishing surface lets developers upload builds, configure store pages, manage offers, run sales, and integrate with EOS achievements and entitlements. Publishing tools include the BuildPatchTool / EOS SDK Tool for uploading builds and a developer portal for managing products. There is no fully self-serve public REST Store API; publishing is gated through Epic's onboarding.

- **Human URL:** [https://dev.epicgames.com/en-US/store](https://dev.epicgames.com/en-US/store)
- **Base URL:** `https://dev.epicgames.com`

#### Tags

- Builds
- Entitlements
- Publishing
- Store

#### Properties

- [Portal](https://dev.epicgames.com/en-US/store)
- [Documentation](https://dev.epicgames.com/docs/epic-games-store)
- [Postman Collection](collections/epic-games.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/epic-games.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kids Web Services (KWS)

Kids Web Services is Epic's compliance and parental-verification platform for games and online services that handle children's data. KWS exposes REST APIs and an SDK for age verification, parental consent collection (COPPA, GDPR-K, age-appropriate design code), account linking, and consent revocation flows.

- **Human URL:** [https://kidswebservices.com](https://kidswebservices.com)
- **Base URL:** `https://kidswebservices.com`

#### Tags

- COPPA
- Compliance
- GDPR-K
- Kids
- Parental Consent
- Privacy

#### Properties

- [Portal](https://kidswebservices.com)
- [Documentation](https://docs.kidswebservices.com)
- [Postman Collection](collections/epic-games.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/epic-games.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Unreal Engine (Pointer)

Unreal Engine is profiled separately. See the unreal-engine entry for Unreal SDK / Plugin / Pixel Streaming / RHI / Online Subsystem details.

- **Human URL:** [https://www.unrealengine.com](https://www.unrealengine.com)
- **Base URL:** `https://www.unrealengine.com`

#### Tags

- Game Engine
- SDK
- Unreal Engine

#### Properties

- [Sister Entry](https://github.com/api-evangelist/unreal-engine)
- [Postman Collection](collections/epic-games.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/epic-games.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.epicgames.com)
- [Store](https://store.epicgames.com)
- [Portal](https://dev.epicgames.com)
- [Documentation](https://dev.epicgames.com/docs)
- [Community](https://dev.epicgames.com/community)
- [API Reference](https://dev.epicgames.com/docs/web-api-ref)
- [Getting Started](https://dev.epicgames.com/docs/epic-online-services/eos-get-started)
- [Tutorials](https://dev.epicgames.com/docs/services/en-US/Tutorials)
- [GitHub Organization](https://github.com/EpicGames)
- [Status](https://status.epicgames.com)
- [Support](https://www.epicgames.com/help)
- [Blog](https://www.unrealengine.com/blog)
- [Terms of Service](https://store.epicgames.com/en-US/eula)
- [Privacy Policy](https://www.epicgames.com/site/en-US/privacypolicy)
- [Terms of Service](https://www.epicgames.com/site/en-US/eula)
- [X (Twitter)](https://x.com/EpicGames)
- [Facebook](https://www.facebook.com/epicgames)
- [LinkedIn](https://www.linkedin.com/company/epic-games)
- [YouTube](https://www.youtube.com/@epic)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
