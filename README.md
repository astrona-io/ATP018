# ATP018 — Keycloak

An Astrona **training path**: a course track that groups training series
(`ATSxxx`) as its domains. Each stage in `path.yaml` is one domain and points
at the repository that teaches it. There is no official Keycloak certification
exam, so the domains and weights are Astrona's own and `examPreparation` is
off.

| Stage | Domain | Weight | Content | Status |
| --- | --- | --- | --- | --- |
| STG001 | Fundamentals & Getting Started | 10 % | [ATS088](https://github.com/astrona-io/ATS088) | Draft, written, not yet run |
| STG002 | Realm Administration & Identity Management | 20 % | ATS089 | Planned |
| STG003 | Securing Applications & Services | 25 % | ATS090 | Planned |
| STG004 | Fine-Grained Authorization Services | 15 % | ATS091 | Planned |
| STG005 | Keycloak Development & SPI Customization | 15 % | ATS092 | Planned |
| STG006 | Production Operations, Security & Kubernetes | 15 % | ATS093 | Planned |

The site picks it up through [astrona-content](https://github.com/astrona-io/astrona-content):
a file in `courses/` that points at this repository, and the content sync
builds the course — one section per stage, with the readings, playgrounds and
labs each stage repository lists in its `astrona.yaml`. That course file does
not exist yet; add it when the first stage is ready to show.

A stage may point at any GitHub repository with an `astrona.yaml`, including
third-party ones; which repositories a track may use is decided in
astrona-content's review.
