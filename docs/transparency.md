# Transparency contract

Transparency means that another human or connector-backed agent can reconstruct
the work from GitHub without relying on a private conversation.

## Record publicly in the work item

- task inputs and authoritative links;
- assumptions that affect implementation;
- decisions and who supplied them;
- scope changes and deviations;
- native blockers and cross-repository ordering;
- commands actually run and summarized outcomes;
- review, benchmark, screenshot, log, or deployment evidence;
- the close reason and any return condition.

## Never record

- credentials or secret values;
- unredacted sensitive logs or personal data;
- private model reasoning;
- unsupported claims of validation, publication, merge, or deployment.

## Evidence ladder

Use precise delivery language: planned, implemented locally, validated locally,
committed locally, pushed, pull request verified, merged, and deployed and
verified. Each claim requires direct evidence from that stage.

## Project rule

Projects summarize issue and pull-request facts. If a Project value conflicts
with the connector-visible repository, issue, pull request, relationship, or
check, correct the Project projection; do not reinterpret the authoritative
record to match the board.
