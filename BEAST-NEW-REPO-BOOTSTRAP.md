# BEAST New-Repo Bootstrap — v2.1

Use this whenever a new MGR repository is created.

## 1. Canonical upstream
Canonical operating doctrine is `tdmboyd-dev/mgr-perfect-skill/BEAST.md`.
Local repos extend BEAST; they do not fork a competing doctrine.

## 2. Minimum files in every repo
- `AGENTS.md` — tells any AI what to read first.
- `BEAST-JEV-READ-FIRST.md` — project-specific decisions, boundaries and current truth.
- `BUILD-QUEUE.md` or `BuildList.md` — implementation truth.
- `AUDIT-LEDGER.md` — defects, corrections and evidence.
- `research/README.md` — research index when research matters.
- `evidence/` or explicit test/run references — proof.

## 3. AGENTS.md minimum
```md
# MGR AI boot
1. Read BEAST-JEV-READ-FIRST.md.
2. Read canonical MGR BEAST v2.1 from tdmboyd-dev/mgr-perfect-skill/BEAST.md when connected.
3. Read the local build queue, audit ledger and research index before editing.
4. Preserve status truth: DISCOVERED/RESEARCHED/SPECIFIED/IMPLEMENTED/TESTED/VERIFIED are not interchangeable.
5. Use Backwards-Forwards: repair stale assumptions while researching/building forward.
```

## 4. Local project contract
Record:
- purpose and non-goals;
- canonical shared services this repo consumes;
- what this repo alone owns;
- source-of-truth paths;
- current blockers;
- provider-independent contracts;
- owner-locked decisions;
- verification commands/evidence.

## 5. Research rule
A compound feature must be decomposed into disciplines. Research batches may cover 10–50 tracks, but every track keeps its own source/license/eval/status record.

## 6. Sync rule
When canonical BEAST changes:
- update local version references;
- migrate only applicable new rules;
- record the migration in AUDIT-LEDGER;
- never overwrite project-specific owner decisions blindly.

## 7. No-chat-only architecture
If a discovery changes how MGR operates, it must be written into the owning repo during the same wave. Chat is a report, not the database.
