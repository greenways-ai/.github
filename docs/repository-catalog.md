# Greenways repository catalog

This catalog is the organization-level orientation map for the ChatGPT Pro
GitHub connector. Project membership was read from the live Projects on
2026-08-24. Repository-local files remain authoritative for implementation.

Private repositories and Projects require authenticated GitHub access. Connector
authorization and indexing are separate requirements and are not implied by
local `gh` access; rows marked `Repository access required` cannot be oriented
without access to the corresponding repository.

## Greenways Infra

Project: https://github.com/orgs/greenways-ai/projects/2

| Repository | Responsibility | Connector entry | Validation authority |
| --- | --- | --- | --- |
| [`workspace`](https://github.com/greenways-ai/workspace) | Cross-repository workspace and rollout coordination | `README.md`, `AGENTS.md` | Root `AGENTS.md` and Makefile |
| [`historia`](https://github.com/greenways-ai/historia) | Git-native temporal indexing and tracing | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`hestia`](https://github.com/greenways-ai/hestia) | Provenance, rights, and contract ledger | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`hodos`](https://github.com/greenways-ai/hodos) | Graph and relational path technology | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`hoplite`](https://github.com/greenways-ai/hoplite) | Hara application server | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`ignatius`](https://github.com/greenways-ai/ignatius) | Shared runtime technology | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`tahto`](https://github.com/greenways-ai/tahto) | Local-first application and semantic profiles | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`visual-language`](https://github.com/greenways-ai/visual-language) | Adaptive mosaic design system | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`www`](https://github.com/greenways-ai/www) | Public Greenways website | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`greenways-ai.github.io`](https://github.com/greenways-ai/greenways-ai.github.io) | Open-source publishing site | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`homebrew-tap`](https://github.com/greenways-ai/homebrew-tap) | Greenways product formulas | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`hoplite-store-sqlite`](https://github.com/greenways-ai/hoplite-store-sqlite) | SQLite auth-store adapter for Hoplite | `README.md` | Needs repository-specific validation map |
| [`homebrew-hoplite`](https://github.com/greenways-ai/homebrew-hoplite) | Hoplite Homebrew formulas | `README.md` | Needs repository-specific validation map |
| [`packages`](https://github.com/greenways-ai/packages) | Signed package metadata | `README.md` | Needs repository-specific validation map |
| [`studio-platform`](https://github.com/greenways-ai/studio-platform) | Auditable browser-native creative infrastructure | `README.md` | Needs repository-specific validation map |
| [`studio-tooling`](https://github.com/greenways-ai/studio-tooling) | HAL music, Studio, Supersonic, and HARP tooling | `README.md` | Needs repository-specific validation map |
| [`greenways-ci`](https://github.com/greenways-ai/greenways-ci) | Shared continuous-integration support | `README.md` | Needs repository-specific validation map |
| [`alumbra`](https://github.com/greenways-ai/alumbra) | Voxel and game engine | `README.md` | Needs repository-specific validation map |
| [`sanskara`](https://github.com/greenways-ai/sanskara) | Private 3D scene-generation engine | Repository access required | Needs access and validation map |
| [`hardware`](https://github.com/greenways-ai/hardware) | Private Lisp and neural-network hardware work | Repository access required | Needs access and validation map |
| [`web-infra`](https://github.com/greenways-ai/web-infra) | Private web infrastructure and ledger runtimes | Repository access required | Needs access and validation map |
| [`agent-flow`](https://github.com/greenways-ai/agent-flow) | Private REPL-first agent workflow kit | Repository access required | Needs access and validation map |

## Greenways Platform

Project: https://github.com/orgs/greenways-ai/projects/4 (private)

| Repository | Responsibility | Connector entry | Validation authority |
| --- | --- | --- | --- |
| [`greenways-platform`](https://github.com/greenways-ai/greenways-platform) | Public delivery layer for explicitly released, reviewed Greenways Spaces content; separate from Greenways OS private Fabric and local product authority | Repository access required; `README.md`, `AGENTS.md` | Repository `AGENTS.md`; contract-only validation boundary—no application or infrastructure implementation validation is defined yet |

## Greenways OS

Project: https://github.com/orgs/greenways-ai/projects/3

| Repository | Responsibility | Connector entry | Validation authority |
| --- | --- | --- | --- |
| [`greenways-os`](https://github.com/greenways-ai/greenways-os) | Greenways product and creative-world delivery | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |

## Selection rule

Choose the repository that owns the observable outcome. For cross-repository
work, keep one parent issue in the outcome-owning repository and create one
sub-issue and pull request per changed repository. Do not copy an issue into
multiple repositories.
