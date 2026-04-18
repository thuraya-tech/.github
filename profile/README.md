# Thuraya Tech

Observability and IT asset management — built for the Saudi enterprise, data-resident in-kingdom.

## Products

- **[Thuraya Trace](https://thurayatrace.cloud)** — application performance monitoring and distributed tracing
- **[Thuraya Qayd](https://thurayaqayd.cloud)** — IT asset management and CMDB (Arabic-first, NDMO- and PDPL-aligned)

## Shared infrastructure

- `id.thuraya.tech` — single sign-on (Keycloak)
- `docs.thuraya.tech` — documentation
- `cd.thuraya.tech` — continuous delivery (ArgoCD)
- `status.thuraya.tech` — service health

## Repository layout

| Group | Repos |
|-------|-------|
| Shared | `thuraya-*` |
| Trace | `trace-*` |
| Qayd | `qayd-*` |
| AI | `ai-agents` |

Most repositories are private; public work lives in the marketing site and legacy release proxies.
