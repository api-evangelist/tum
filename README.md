# Technical University of Munich (tum)

The Technical University of Munich (TUM) is a public research university in Munich, Germany, ranked #47 in the QS World University Rankings 2025. TUM has no single centralized commercial developer portal; its most visible public API footprint is the community- and student-driven [TUM-Dev](https://github.com/TUM-Dev) open-source organization, which builds and operates the TUM Campus App ecosystem and several openly available APIs.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/tum/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=tum-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Germany, Open Source, Campus, Open Data

## APIs

- **NavigaTUM API** — Search and resolve rooms, buildings, and places across TUM campuses (Rust/MeiliSearch, OpenAPI 3.0). Base: `https://nav.tum.de/api`. Docs: https://github.com/TUM-Dev/NavigaTUM/blob/main/server/README.md
- **eat-api (Mensa/Canteen API)** — Static JSON API for Munich student canteen menus and prices. Base: `https://tum-dev.github.io/eat-api`. Docs: https://github.com/TUM-Dev/eat-api
- **TUM Campus App Backend (gRPC)** — Go backend with a gRPC interface powering the official Campus App clients. Source: https://github.com/TUM-Dev/Campus-Backend

## Plans

- [plans/tum-plans-pricing.yml](plans/tum-plans-pricing.yml)

## Rate Limits

- [rate-limits/tum-rate-limits.yml](rate-limits/tum-rate-limits.yml)

## FinOps

- [finops/tum-finops.yml](finops/tum-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.tum.de/en/
- GitHub: https://github.com/TUM-Dev
- Developer Portal: https://www.tum.dev/
- LinkedIn: https://www.linkedin.com/school/technische-universitat-munchen/
- Source Code: https://github.com/TUM-Dev

## Notes

All cataloged APIs were verified against live, public, unauthenticated endpoints in June 2026. NavigaTUM's `/api/search` endpoint and eat-api's static JSON files return data without authentication. The Campus-Backend gRPC API is open source but operated for the official apps rather than offered as a documented third-party API. The central research information system, TUMFIS (`https://portal.fis.tum.de/`), runs on Elsevier Pure but exposes no documented public API. No endpoints were fabricated; URLs that did not resolve are recorded in [review.yml](review.yml).

## Maintainers

- Kin Lane — kin@apievangelist.com
