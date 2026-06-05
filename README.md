# Epic Games (epic-games)

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
