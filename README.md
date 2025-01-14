# LLAMARA Distribution

LLAMARA - **L**arge **L**anguage **A**ssistant for **M**odel-**A**ugmented **R**etrieval and **A**nalysis - is an LLM-based assistant for information retrieval from a provided knowledge base.
It aims at supporting researchers working with scientific papers, whitepapers and documentation,
as well as possibly serving research findings in an accessible way to the public.

> **NOTE:** This repository contains the LLAMARA distribution build and release pipelines only.
> Source code for LLAMARA backend can be found at [llamara-ai/llamara-backend](https://github.com/llamara-ai/llamara-backend),
> the source code for LLAMARA frontend is currently not publicly available.

LLAMARA Distribution is a ready-to-use build of LLAMARA backend that includes LLAMARA frontend as well.

It is published as a [Docker container](https://github.com/orgs/llamara-ai/packages/container/package/llamara) and can be [deployed using Docker Compose](https://github.com/llamara-ai/llamara-deployment-docker).
You can also download the built JAR as artifact from the [CI Build](https://github.com/llamara-ai/llamara-distro/actions/workflows/build.yaml) action and from individual releases.

The Docker image [`ghcr.io/llamara-ai/llamara`](https://github.com/orgs/llamara-ai/packages/container/package/llamara) provides the following labels:

- `latest`: points to the latest release
- `vX.Y.Z`: points to a specific release
- `main`: points to the latest snapshot build from the `main` branches of backend, frontend and distribution repositories
