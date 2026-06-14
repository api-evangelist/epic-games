# Epic Games GraphQL

Epic Games exposes GraphQL surfaces across several developer-facing products. The primary surface historically lived at `https://graphql.epicgames.com/graphql` and powered the Epic Games Store catalog, offer lookups, and internal services. That public introspection endpoint is no longer reachable (HTTP 410), but the EOS platform and EGS backend continue to use GraphQL internally and through partner integrations.

## Surfaces

| Surface | Endpoint / Notes |
|---|---|
| Epic Games Store catalog | `https://graphql.epicgames.com/graphql` (deprecated/gone) |
| EOS Web APIs (REST + token exchange) | `https://api.epicgames.dev` |
| Developer Portal | `https://dev.epicgames.com` |

## Authentication

All EOS and EGS API calls require OAuth 2.0 tokens obtained from the Epic Account OAuth server at `https://account-public-service-prod.ol.epicgames.com/account/api/oauth/token`. Clients register a **ClientId** and **ClientSecret** inside the EOS Developer Portal and exchange them for access tokens using the `client_credentials` or `authorization_code` grant.

## Known GraphQL Usage

- **Epic Games Store** – The store frontend has historically queried a private GraphQL API for catalog items, offers, namespace lookups, and price information.
- **EOS Ecom Interface** – Entitlement and offer queries used internally by EOS SDK calls map closely to GraphQL-style resource shapes.
- **Fortnite Backend** – Fortnite's backend (Lightswitch, MCP/profile service) exposes JSON endpoints that mirror GraphQL object structures for player profiles, items, and stats.

## Schema

See `epic-games-schema.graphql` for a representative GraphQL schema covering Epic Online Services domain objects: identity, social, sessions, lobbies, commerce, progression, integrity, and voice.

## References

- EOS Developer Portal: https://dev.epicgames.com
- EOS Web API Reference: https://dev.epicgames.com/docs/web-api-ref
- EOS Getting Started: https://dev.epicgames.com/docs/epic-online-services/eos-get-started
- Epic Games GitHub: https://github.com/EpicGames
- EOS SDK Downloads: https://dev.epicgames.com/docs/epic-online-services/platform-sdks
