# Connector-first delivery workflow

## Operating boundary

The ChatGPT Pro GitHub connector is the sole discovery and context path for the
web workflow. GitHub is the durable ledger. Codex may execute code changes and
publish authorized results, but task context must not depend on a private chat,
local-only file, or Project-only field.

## Issue contract

An executable issue contains Outcome, Context, Scope, Acceptance criteria,
Validation, Relationships, and Delivery. Each section must carry enough detail
or canonical GitHub links for a fresh connector-backed conversation to recover
the contract.

Roadmaps and Epics coordinate executable sub-issues. A Task, Bug, Feature, or
Gate should normally fit one primary pull request.

## Readiness

Project Readiness is a visual projection of issue evidence:

- `Ready` — the issue contract is complete and native blockers are clear.
- `Needs decision` — a human product or architecture choice is missing.
- `Needs specification` — expected behavior or boundaries are incomplete.
- `Needs reproduction` — a reported failure lacks reliable reproduction.
- `Needs access` — execution requires unavailable credentials, repositories,
  environments, or approvals.

The reason must be stated in the issue. The field alone is not evidence.

## Work record

When work starts, record the agent or person, base SHA, intended scope,
validation plan, and material assumptions. Scope or architecture changes are
written back to the issue or a versioned decision document.

## Pull-request contract

Every implementation pull request contains one canonical Primary issue URL,
changes and reasons, commands actually run and their outcomes, inspectable
evidence, compatibility and risk notes, dependency links, and remaining work.

Use `Closes` only for complete delivery. Use `Advances` for partial delivery or
an Epic contribution.

## Completion and parking

Close completed work as completed. Close deferred work as not planned with a
reason and a concrete return condition. Reopening parked work returns it to
review: refresh the issue contract and readiness before execution resumes.
