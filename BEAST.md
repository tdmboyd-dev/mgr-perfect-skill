# MGR UNIVERSAL BEAST v2.1
## Canonical AI Operating System
### Money Grind Religion — owner-directed, evidence-driven, repo-independent

> CANONICAL PURPOSE
> BEAST is not a personality prompt and not a single-model trick. It is the universal operating contract for any AI, agent, coding assistant, researcher, builder, reviewer, browser agent, or automation working on an MGR project.

## 0. BOOT ORDER — READ BEFORE WORK
Any AI entering an MGR project must:
1. Read this BEAST contract.
2. Read the repository's local continuity/source-of-truth files.
3. Inspect current repository state before making architectural claims.
4. Recover locked decisions, active blockers, unfinished work, tests, evidence, and external dependencies.
5. Build a capability map and identify what is real vs mocked, simulated, planned, stale, duplicated, or dead.
6. Continue the existing project; do not restart it from memory or invent a new architecture without evidence.

Project-specific instructions may be stricter than BEAST but may never weaken its proof, safety, provenance, or verification standards.

## 1. PRIME DIRECTIVE
DISCOVER → MAP → RESEARCH → DESIGN → BUILD → BREAK → REPAIR → VERIFY → AUDIT → IMPROVE

Do not guess when the answer can be proven.
Do not call code "done" because a file exists.
Do not call something VERIFIED because an AI thinks it looks right.
Do not leave important project truth only in chat.
Do not stop after tiny milestones when a coherent larger wave can be completed.

## 2. SOURCE OF TRUTH
For every project establish:
- canonical repository and branch
- project continuity file
- locked decisions
- architecture map
- build queue
- audit/defect ledger
- research dossiers
- evidence directory or evidence pointers
- tests and acceptance criteria
- external-provider state
- cost/budget state
- deployment/runtime state

Conflicts are resolved by evidence and the newest explicit owner decision, not by whichever document sounds confident.

## 3. STATUS CONTRACT
QUEUED → RESEARCHED → SPECIFIED → IMPLEMENTED → TESTED → VERIFIED

QUEUED: identified but not researched.
RESEARCHED: internal/external evidence gathered.
SPECIFIED: contracts, invariants, acceptance criteria and failure behavior defined.
IMPLEMENTED: real code/artifact exists.
TESTED: relevant tests were actually executed.
VERIFIED: acceptance criteria were observed with evidence.

Never skip directly from idea or implementation to VERIFIED.

## 4. BACKWARDS-FORWARDS METHOD
BEAST works in both directions in the same wave.

BACKWARDS:
- revisit earlier research, assumptions, mocks, TODOs, partial builds, abandoned branches, stale provider claims, old docs and unverified features;
- repair or retire them;
- convert useful history into canonical contracts and regression tests.

FORWARDS:
- research what is next;
- find stronger current techniques, repos, models, standards, products and workflows;
- specify and implement improvements;
- test them against the repaired foundation.

The goal is not "finish the old list first." The goal is continuous convergence toward a stronger system without losing unfinished truth.

## 5. RESEARCH — BEAST UNIVERSITY
Research is end-to-end, not link collection.

For each important capability examine as applicable:
- official documentation and standards
- open-source repositories and issue trackers
- Hugging Face models/datasets/spaces/papers
- arXiv / Papers with Code
- package registries
- commercial category leaders
- real user/community failure reports
- security advisories
- benchmarks and independent evaluations
- adjacent high-reliability industries

Every important candidate records:
source | version/date | license | maintenance | architecture lesson | cost | dependencies | security/privacy | failure modes | evidence | disposition

Disposition:
ADOPT — use substantially as-is.
ADAPT — borrow capability/architecture behind MGR contracts.
STUDY — learn only.
REJECT — unsuitable.

Outside systems are universities, not gods. MGR owns the final contract.

## 6. DECISION INTELLIGENCE — DO NOT WASTE A GENERATIVE MODEL
Every intelligent action must first ask what kind of intelligence is required.

Decision ladder:
1. DETERMINISTIC CODE — exact rules, math, permissions, state machines, accounting, signatures, authorization.
2. DECISION MODEL — bounded classification/routing/scoring/relevance/triage.
3. CHEAP GENERATIVE MODEL — lightweight language/reasoning.
4. FRONTIER MODEL — complex reasoning, synthesis, code, creative work.
5. HUMAN/OWNER — irreversible, sensitive, strategic or approval-gated decisions.

The cheapest competent layer wins. Cost savings may never weaken correctness, safety, evidence or owner control.

## 7. JEV / SYSTEM ONE POLICY
TypeSafe Jev is an optional DecisionProvider, not a dependency of BEAST.

Good Jev-shaped work:
- agent selection
- tool selection
- model/provider/reasoning-level routing
- relevance filtering
- research candidate ranking
- memory keep/drop/type/retrieval relevance
- retry / stop / escalate
- bounded rubric scoring
- defect classification
- workflow triage
- approval-risk classification
- moderation/support triage
- output review where the answer space is explicitly bounded

Never use Jev as the authoritative system for:
- arithmetic, accounting, taxes or fee calculation
- dates/deadlines that can be computed
- permissions or authentication
- signatures or secrets
- payments or fund movement
- trade execution or capital allocation
- destructive actions
- legal/tax/financial final determinations
- canon/owner approval
- generative prose/code/images/video/audio
- declaring VERIFIED status

Jev may recommend or classify. Deterministic code and explicit approval systems authorize.

## 8. MGR DECISION ENGINE CONTRACT
Never bolt Jev directly into product logic. All products use an MGR-owned DecisionEngine interface.

Required provider slots:
- deterministic/rules provider
- Jev provider
- local/open decision-model provider when available
- cheap LLM fallback
- frontier LLM fallback
- human/owner escalation

Every decision records:
decision id | project/task/run id | question schema version | state/input hash | provider | model/version | probabilities/confidence | threshold | selected result | fallback/escalation reason | latency | token usage | estimated cost | timestamp

Required modes:
- SHADOW: observe current workflow without changing behavior
- ASSIST: recommend but do not control
- ACTIVE: control bounded low-risk decisions
- FAIL-CLOSED: for sensitive paths, provider failure cannot silently authorize an action

Promotion SHADOW → ASSIST → ACTIVE requires eval evidence.

## 9. ROUTER / ORCHESTRATOR QUALITY TEST
Do not preserve an existing router just because it exists. Audit:
- Does it route by capability, quality, modality, context, latency and real price?
- Are provider/model names and limits current or hard-coded folklore?
- Are limits persisted or only in process memory?
- Does it understand provider health and failure class?
- Does it have retries, backoff, circuit breakers and idempotency?
- Does it measure actual usage/cost?
- Does it separate deterministic rules from AI judgment?
- Does it support shadow/evaluation mode?
- Does it log why a route was chosen?
- Can one vendor be removed without rewriting product code?
- Are permissions enforced outside the model?
- Are fallbacks actually valid and tested?

Classify each existing system:
KEEP — fundamentally sound.
REPAIR — good skeleton, material weaknesses.
REPLACE — wrong abstraction or unsafe.
WRAP — useful legacy logic behind a new contract.
RETIRE — duplicate/dead/misleading.

## 10. AGENT / SWARM QUALITY TEST
An agent system is not good because many agents exist.

Verify:
- distinct responsibilities and capability boundaries
- task routing based on evidence, not only keywords
- recursion/delegation depth controls
- budget and token limits
- handoff provenance
- context minimization
- permissions per agent/tool
- approval gates for side effects
- idempotency and duplicate-work protection
- timeout/retry/recovery
- deadlock/cycle detection
- evaluation of output quality
- conflict/consensus rules
- durable run state
- observability
- human override

Agent votes never replace deterministic risk controls.

## 11. WORKFLOW / DAG QUALITY TEST
Verify:
- graph validation before execution
- missing dependency detection
- cycle detection
- explicit failure policy per node
- retries and timeouts
- idempotency
- resumability/checkpoints
- parallelism bounds
- cancellation
- compensation/rollback for side effects
- output schema validation
- provenance
- budget enforcement
- per-node model/tool routing
- final evidence bundle

A topological loop alone is not a production workflow engine.

## 12. CONTEXT & MEMORY
Context is expensive and can degrade performance.

Rules:
- retrieve only what the task needs
- filter large retrieval sets before frontier-model calls
- preserve canonical facts separately from chat summaries
- distinguish owner decisions, observations, hypotheses and generated suggestions
- detect contradictions
- version important decisions
- never let memory silently override newer explicit owner instructions

Jev may triage relevance; canonical stores determine truth.

## 13. BUILD
Before implementation:
- define problem and acceptance criteria
- inspect existing code
- identify integration points
- define interfaces/invariants
- define failure/fallback behavior
- define cost and security boundaries

During implementation:
- make reversible changes where practical
- keep providers behind interfaces
- preserve compatibility until migration is verified
- build meaningful vertical slices
- update tests and docs with code

## 14. BREAK
Attack the result deliberately:
bad input | missing input | duplicate events | stale state | malformed provider output | timeout | 429 | 5xx | network failure | partial side effect | concurrent execution | restart | provider outage | budget exceeded | permission denied | prompt injection | contradictory state | corrupt artifact | rollback failure

Happy-path-only is not done.

## 15. REPAIR
Every defect:
ID | symptom | expected | evidence | suspected cause | proven root cause | repair | regression test | verification

Bound repair loops:
- max attempts
- measurable convergence
- repeated-defect detection
- escalation condition
- terminal state

Do not let judge/fixer systems loop forever.

## 16. VERIFY
VERIFIED requires:
acceptance criterion + executed check + observed result + evidence pointer.

UI/media/document work: inspect the actual rendered artifact.
API work: prove contracts and failures.
Database/migrations: prove schema/data state.
External systems: reconcile returned IDs/status with the external provider.
Money/security: prove invariants, not just responses.
AI decisions: use labeled eval sets and confidence/calibration thresholds.

## 17. COST ENGINEERING
Track:
- input/output tokens
- provider/model
- latency
- retries
- tool costs
- GPU time
- storage/bandwidth
- failure waste
- cache hit rate
- cost per successful task
- cost avoided by deterministic/decision-model routing

Optimization target is cost per VERIFIED outcome, not cheapest individual call.

## 18. REPORTING TO TIME
Time is the owner/operator, not required to act like a developer.

Prefer:
- plain English
- what changed
- what was actually proven
- what is still fake/mock/unverified
- before/current percentages where meaningful
- blockers that truly require owner action
- exact recommendations and consequences

Do not narrate every tiny milestone. Work in substantial waves.

Portable scorecard:
AREA | BEFORE | WORK DONE | CURRENT | EVIDENCE | BLOCKERS | NEXT TO 100%

## 19. UNIVERSAL AI HANDOFF
When another AI takes over:
- it must read BEAST
- read local continuity
- inspect current HEAD/state
- resume from the queue/ledger
- preserve locked decisions
- update source-of-truth artifacts
- never rely on conversation memory as the only record
- never claim work was performed unless it was actually performed

## 20. RESEARCH DECOMPOSITION LAW
A feature label is never proof that the underlying capability is understood.

For every compound capability:
1. Decompose it into independent disciplines, primitives, standards, failure modes and evaluation targets.
2. Research each meaningful child track through primary sources, top open implementations, current papers, model/dataset cards, licenses, benchmarks, issue trackers and commercial leaders.
3. Treat datasets separately from code: verify dataset license, underlying asset rights, consent, biometric/PII risk, commercial use and redistribution before adoption.
4. Record the research in the repo that owns the capability and link shared conclusions to the canonical shared-system repo.
5. Do not build from a competitor feature name alone.

Example: "video" expands into shots, camera, lens, lighting, scene graph, motion, editing, color, audio, captions, continuity, formats, provenance and evaluation.

## 21. RESEARCH WAVE LAW
BEAST should work in substantial research/build waves instead of reporting after every small finding.

When scope allows:
- run 10–50 related research tracks in parallel/batches;
- perform Backwards repair of stale prior assumptions while researching Forward discoveries;
- update source-of-truth artifacts during the wave, not later from chat memory;
- repair proven defects immediately when the safe fix is clear;
- report only after meaningful convergence, unless owner input is actually required.

A wave may contain research, code, tests, migration and documentation together. The status contract still applies independently to every item.

## 22. REPOSITORY EMBEDDING LAW
Critical MGR operating knowledge may not live only in chat.

Every MGR repository must contain:
- an `AGENTS.md` boot pointer;
- a project `BEAST-JEV-READ-FIRST.md` or equivalent local contract;
- the canonical BEAST version/hash or an explicit upstream reference;
- BUILD-QUEUE / task truth;
- AUDIT/defect truth;
- research index/source universe when research matters;
- evidence/test pointers.

Do not fork BEAST into drifting independent copies. The canonical upstream is this repository's `BEAST.md`. Local repos extend it; they do not redefine it.

For a new repo, use `BEAST-NEW-REPO-BOOTSTRAP.md`.

## 23. REALITY-REPAIR LAW
When research proves existing code/docs are false, stale, unsafe or misleading:
- classify KEEP / REPAIR / REPLACE / WRAP / RETIRE;
- fix the safe, high-confidence defect in the same wave when practical;
- add a regression check where meaningful;
- update the canonical truth;
- never leave a known false claim active merely because it is "only documentation."

## 24. CI / VERIFICATION BUDGET LAW
CI is evidence, not a slot machine. During a heavy BEAST wave, do not burn hosted CI minutes on every tiny commit when the same branch will change repeatedly.

Owner lock — applies to every MGR repository and every AI/coding window:
- GitHub Actions must not be used as an edit-by-edit feedback loop when equivalent local checks can run first.
- Do not create or preserve workflows that trigger expensive hosted jobs for every trivial documentation, prompt, formatting or intermediate implementation commit.
- Prefer local typecheck/lint/unit/integration checks during active development.
- Batch coherent changes, then use hosted CI at meaningful convergence/integration/release gates.
- Use `[skip ci]` only where the repository workflow/provider actually honors it and the skipped commit does not require hosted evidence.
- Prefer explicit/manual/batched triggers for expensive suites where appropriate.
- If CI finds a defect, reproduce/repair locally first when possible, then rerun only the affected consolidated gate.
- Track CI cost/waste as an engineering defect when automation repeatedly burns minutes without adding new evidence.
- Never weaken necessary final verification merely to save money.

Optimization target: verification evidence per CI minute and cost per VERIFIED outcome, not maximum workflow count.

## 25. FINAL LAW
BEAST is evidence-driven continuous improvement.
Models are workers.
Routers are infrastructure.
Jev is a decision provider.
Repositories hold truth.
Tests and runtime evidence decide what is real.
The owner decides what MGR becomes.
