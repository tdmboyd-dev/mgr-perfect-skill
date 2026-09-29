# Repository continuity protocol

Owner-approved on 2026-09-29. This extends BEAST; it does not replace product canon, existing verification gates, or current user instructions.

## Purpose and authority

Keep one coordinated work map while preserving repository, product, deployment and domain boundaries. A repository count is not a product or public-domain count. Do not merge application roots or move source code as a continuity repair.

AGENTS.md directs entry. WORK-STATE.md is the compact current resume record. Existing product continuity, build queues, research manifests, scorecards and audit ledgers remain authoritative for their own subjects. Link them instead of creating parallel backlogs. Newer explicit owner decisions govern product direction; executed evidence governs claims of success. Historical assistant promises are not proof.

## Start or resume

1. Verify repository identity, intended branch and fresh HEAD. Preserve local changes and other contributors' commits.
2. Read AGENTS.md, canonical BEAST, WORK-STATE.md and the local authority files it names. Follow stricter local read orders.
3. Compare HEAD with the resume record's inspected base. If it moved, inspect the intervening changes and reconcile before editing. A stale checkpoint is a warning to inspect, not an instruction to reset.
4. Inspect the relevant source, tests, contracts and evidence. A tree listing is not a full code audit.
5. Check the active work claim and central coordination record, if authorized to access it. Select one coherent task with explicit paths and acceptance criteria.

## Required WORK-STATE fields

- Updated date/time and responsible session or operator.
- Repository, working branch, last inspected code commit (the parent of a documentation-only update is valid when clearly labeled).
- Purpose and boundaries; links to existing authority, queue, audit and research records.
- Evidence-backed current checkpoint; distinguish observed code from previous reports.
- Next executable batch, dependencies and exact blockers.
- Unresolved decisions and transfer-packet requests.
- Active work claim: task, owner/session, branch, path scope, base SHA, claimed time, review/expiry time and status.
- Verification: command/run, commit, environment, observed result and remaining unverified scope.
- Current stopping point and whether any real process/schedule is running.

Do not store credentials, environment values, private account exports, signed URLs or raw private conversations in public repositories. Keep private transfer material in an authorized private home; publish only suitable project findings and references.

## Multiple windows and work claims

A markdown claim is an advisory coordination record, not a filesystem lock, security permission or guarantee that another window has stopped.

Before a mutation batch, commit a scoped claim against fresh HEAD using a non-forced update. If another writer advanced the branch, reread and reconcile. Never force a push to win a race. Separate worktrees/branches can isolate work, but overlapping shared files still require coordination.

A claim must name a bounded task and paths. Use an explicit UTC review/expiry time. Expiry means inspect and resolve ownership; it does not authorize overwriting uncommitted work. Preserve unrelated claims. Release the claim at handoff; mark interrupted work accurately. Do not claim all repositories indefinitely.

The shared map records dependencies and ownership. Each repository remains authoritative for its implementation and product decisions. Do not copy every private detail into every repo.

## Update and handoff

Update WORK-STATE and the existing queue/scorecard/audit in the same meaningful batch as the work they describe, before a final handoff or known context limit. Record exact paths, commits, tests, unresolved failures and the next action. Preserve dated historical evidence, but label superseded current-state text.

Claims use QUEUED, RESEARCHED, SPECIFIED, IMPLEMENTED, TESTED and VERIFIED with explicit scope. Research discovery, acquisition, end-to-end reading and execution are separate. A source link alone is not a completed read. Code and test files existing is not evidence that tests ran. Unit tests do not establish live-provider, device, database or production success. Percentages require a defined denominator.

Conserve hosted CI: use relevant local checks for documentation and batch meaningful runtime CI when required. Never weaken a repository gate to avoid its cost. Do not imply background continuation unless a real running mechanism exists.

## Transfer from an older conversation

Request an evidence packet: work method, repo/branch/commit inventory, exact changes, uncommitted artifacts, approved decisions versus proposals, source read coverage, tests and CI evidence, unresolved contradictions, failures, next batch and running-process state. Ask for missing/unknown fields explicitly. Reconcile the packet with fresh repositories before accepting it as current truth.

## Recovery boundary

These files preserve recorded working context. They cannot restore inaccessible local originals, hidden tool payloads, lost credentials or an earlier model's internal memory. Record those gaps rather than claiming complete recovery.
