# AUCC Website: 2025 Engineering Case Study

> Historical portfolio case study for work undertaken by the Web Development & Consulting Club (WDCC) in 2025. This document is maintained in a personal repository and is **not** an official statement by the current WDCC team.

## Context

The Auckland University Canoe Club needed a site for club information, events, member signups and content editing. WDCC developed the project as a team. Credit belongs to the contributors listed in the [project README](../README.md).

## My role

I served as **2025 Tech Lead**, coordinating with the project manager, developers and designer. This historical role should not be confused with current project ownership or maintainership.

## Engineering implementation visible in this repository

| Concern | Evidence to inspect |
| --- | --- |
| Full-stack Next.js implementation | [Application routes](../src/app) and [components](../src/components) |
| Content management | [Payload configuration](../src/payload.config.ts) and [collections](../src/collections) |
| Continuous integration | [GitHub Actions workflows](../.github/workflows) covering build, lint and tests |
| Automated testing | [Vitest configuration](../vitest.config.ts) and workflow definitions |
| Packaging | [Dockerfile](../Dockerfile) and [Docker Compose](../docker-compose.yml) |
| Infrastructure as code | [Terraform](../terraform) |
| Deployment environments | Preview and staging workflows under [GitHub Actions](../.github/workflows) |

The existence of configuration files does not establish that any deployment remains live or that all checks currently pass.

## Decisions worth discussing in an interview

1. **CMS integration:** How content editors work independently of developers, and where schema or permissions change the operational trade-offs.
2. **Team coordination:** How work was broken into independently reviewable tasks and how frontend/design integration was managed.
3. **Deployment workflow:** What preview and staging environments enable, including review before changes reach users.
4. **Complexity management:** Why an integrated codebase can be appropriate for a student consulting team compared with independently deployed services.

These are discussion prompts, not assertions that every listed choice was personally made by the 2025 Tech Lead.

## Team credit and boundaries

This was a collaborative WDCC project. See the [2025 team roster](../README.md#2025-team). Individual contributions should be substantiated by pull requests, commit history, review comments or project records, rather than attributed solely to the tech lead.

**Repository safety:** This documentation adds no runtime behavior. It does not change deployment workflows, secrets, environment variables, live infrastructure or the original organization's repository.

## Before using as portfolio evidence

- Identify specific PRs or issues personally authored or reviewed.
- Add a screenshot of the completed experience, only with the club's permission where required.
- Confirm the exact launch and production history before making public availability claims.
