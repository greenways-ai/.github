# Greenways organization guidance

## Purpose

This repository owns connector-visible organization guidance and default
GitHub contribution contracts. It does not own product or library
implementation work.

## Authority

- `README.md` is the connector entry point.
- `docs/repository-catalog.md` maps repositories to responsibilities and
  Project ownership.
- `docs/connector-first-delivery.md` defines issue and pull-request flow.
- `docs/transparency.md` defines the auditable work record.
- `.github/ISSUE_TEMPLATE/` and `.github/pull_request_template.md` provide
  organization defaults where a child repository has no local override.

## Working rules

- Preserve GitHub as the durable system of record.
- Do not put execution-critical information only in a Project custom field.
- Keep one outcome-owning issue and use native sub-issues and dependencies for
  cross-repository delivery.
- Link specifications instead of copying them into multiple issues.
- Never publish credentials, private reasoning, or unredacted sensitive logs.
- Record assumptions, decisions, actions, validation, and deviations.

## Validation

For documentation changes:

1. Check every relative and canonical GitHub link.
2. Confirm every repository in the catalog belongs to the stated Project.
3. Parse every YAML file under `.github/ISSUE_TEMPLATE/`.
4. Confirm issue forms contain required outcome, scope, acceptance, validation,
   relationship, and delivery inputs.
5. Confirm the pull-request template contains one Primary issue and evidence
   sections.

Repository implementation instructions belong in the nearest `AGENTS.md` of
the owning repository and take precedence for files in that scope.
