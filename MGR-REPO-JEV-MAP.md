# MGR ACCOUNT-WIDE JEV / DECISION INTELLIGENCE MAP
## Canonical companion to Universal BEAST v2
Updated: 2026-09-27

This file is the cross-repository map for the connected `tdmboyd-dev` GitHub account. It prevents each project from inventing its own meaning of Jev, routing, verification or cost optimization.

## Global architecture

```
USER / EVENT
    |
DETERMINISTIC POLICY + EXACT COMPUTATION
    |
MGR DECISION ENGINE
    |-- rules provider
    |-- Jev / System One provider
    |-- local/open decision provider
    |-- cheap LLM fallback
    |-- frontier LLM fallback
    '-- owner/human escalation
    |
EXISTING PRODUCT ORCHESTRATOR
    |
TOOLS / MODELS / WORKFLOWS / AGENTS
    |
DETERMINISTIC AUTHORIZATION + SIDE-EFFECT CONTROLS
    |
VERIFY WITH EVIDENCE
```

Jev is a nervous-system component. It is not the brain, permission system, ledger, tax engine, trading engine, renderer, or source of truth.

---

## 1. iKickItz
### Existing systems
- FreeAPIRouter
- aiProxy
- Heirloom agent coordinator/spawner/governors
- conversation/character memory
- economy/wallet/blockchain services
- content/community/battle systems

### Verdict
FreeAPIRouter: WRAP + REPAIR.
Heirloom coordination: KEEP + REPAIR.
Memory: KEEP + REPAIR.
Economy authorization/calculation: KEEP DETERMINISTIC; NO JEV AUTHORITY.

### Jev placement
- classify task/modality/complexity before provider choice
- choose cheap/standard/frontier reasoning lane
- agent selection/handoff/no-handoff
- memory relevance/write triage
- research candidate filtering
- retry/stop/escalation
- moderation/support categorization
- duplicate-work detection

### Must repair first
Static provider/model/free-tier assumptions, stale price/limit metadata, capability registry, route telemetry, health/circuit-breaker behavior and evaluation data.

---

## 2. MGR Elite Hub
### Existing systems
Tax preparation, OCR/document intake, AI tax advisor, e-file workflow, CRM, bank-product services, fee splits, business/preparer management.

### Verdict
Domain separation exists, but regulated calculations/actions must remain deterministic and evidence-backed.

### Jev placement
- document classification after OCR
- workflow/form/advisor routing
- CRM/support intent and urgency
- reject/error-family classification
- evidence/source relevance
- cheap-vs-strong-model-vs-preparer escalation

### Never
Tax calculation, eligibility, IRS rule override, signature, transmission authorization, bank/fee calculation, identity permissions or money movement.

---

## 3. Dii Heirloom / HEIRLOOM-v1.0
### Existing system
Repo is currently skeletal.

### Verdict
DESIGN CORRECTLY NOW rather than retrofit later.

### Jev placement
Intent, skill, agent, tool and model routing; memory triage; retrieval filtering; task priority; retry/stop/escalate; bounded approval-risk classification.

### Architecture requirement
Heirloom must call MGR DecisionEngine, not Jev directly.

---

## 4. TIME
### Existing systems
AgentSwarm, BotBrain, BotResearchPipeline, Governor, risk/trading/execution systems.

### Verdict
AgentSwarm: REPAIR.
BotBrain: REPAIR.
BotResearchPipeline source ingestion: REPLACE MOCKS WITH REAL EVIDENCE.
Risk/execution math: KEEP DETERMINISTIC.

### Jev placement
Research relevance and prioritization, agent/task assignment, non-trading AI model routing, operational alert triage, duplicate-work detection, retry/stop/escalation.

### Never
Signals, strategy choice, risk math, position sizing, order routing, trade approval, capital allocation, compliance approval or fund movement.

---

## 5. MGR Capital Assistance
### Existing systems
Surplus-recovery intake, case/document workflows, AI modules and operational/legal process support.

### Jev placement
Case classification, jurisdiction/process routing, document type/missing-doc triage, urgency, anomaly/fraud review triage, evidence relevance and model routing.

### Never
Final ownership/eligibility/legal determination, notarization, payout math, signatures, submissions or funds.

---

## 6. MGR Perfect Code
### Existing systems
Universal coding/build package, agents, recipes, bibles, model router, token/cost research, checkpoints.

### Verdict
KEEP as reusable engineering toolkit; make BEAST the proof/decision layer above it.

### Jev placement
Templates for model/agent/tool routing, context filtering, test-failure classification, research ranking, memory triage and retry/escalation.

---

## 7. MGR Perfect Skill
### Existing systems
Universal portable skill distribution.

### Verdict
This is the current canonical distribution home for BEAST v2.

### Jev placement
BEAST defines when Jev is allowed, how it is evaluated, and how providers remain replaceable.

Canonical files:
- AGENTS.md
- BEAST-BOOT.md
- BEAST.md
- JEV-DECISION-CONTRACT.md
- SKILL.md

---

## 8. MGR Visual Forge
### Existing system
Portable visual/3D creation skill.

### Jev placement
After vision/measurement creates structured state: defect type, repair operator, provider/model lane, retry/stop/escalate, asset relevance and cost-quality routing.

### Never
Raw vision, pixel/geometry/physics/camera math, rendering or visual proof.

---

## 9. MGR Agents
### Existing systems
Mega LLM router, Brain pre-router, 36-agent runner, tool authorization, memory, collaboration/handoff, parallel delegation and DAG workflow runner.

### Verdict
DAG: KEEP + REPAIR.
Mega LLM router: KEEP + REPAIR.
Brain bounded routing: WRAP / shift simple decisions to DecisionEngine.
Tool authorization: KEEP.
Keyword collaboration/auto-handoff: REPAIR.
Delegation primitives: KEEP + REPAIR.

### Jev already implemented
- `src/lib/decision/jev.ts`
- Brain pre-route attempts Jev bounded tool choice first
- only agent-authorized tools are presented as choices
- confidence threshold before use
- existing Brain remains fallback
- test file exists for tool-choice boundary

### Still needed
CI workflow, graph pre-validation, durable workflow state, budget-aware fanout, decision logs, calibrated eval datasets, model-tier routing through DecisionEngine and keyword-handoff replacement.

---

## 10. MGR Compliance Buddy
### Jev placement
Document/work-item classification, risk/urgency triage, checklist routing, evidence relevance, exception categories, model escalation.

### Never
Final legal/compliance determination, exact statutory calculations/deadlines when code can compute them, permissions or sign-off.

---

## 11. Horribly Unorthodox (HU)
### Existing systems
Master HU creator intelligence, Mind Room specialist system, persistent canon/truth/continuity concepts, approval gateway.

### Verdict
Creative architecture remains generative + deterministic canon governance.

### Jev placement
Mind routing, specialist-review selection, context packet relevance, continuity/conflict-risk triage, memory relevance, model tiering, bounded QA and large clip/topic/research classification.

### Never
Story/dialogue generation, final creative synthesis, canon choice, APPROVE/CHANGE/DENY, creator approval or exact timeline computation.

---

## 12. MGR Create Loco
### Existing systems
Current repo is primarily BEAST/research doctrine; README defines visual IR, reconstruction, causal repair, reimagine and model/provider routing goals.

### Verdict
DIRECTION GOOD; EXECUTABLE ROUTER NOT YET PROVEN.

### Jev placement
Post-vision defect class, repair operator, provider/model selection, retry/stop/escalate, convergence triage, asset/reference relevance and expensive-reasoning gate.

### Never
Raw visual analysis, DOM/pixel measurements, rendering, geometry/camera/physics math or proof of fidelity.

---

## 13. MGR Creation OS
### Existing systems
Core lifecycle, factories, approval/policy/evidence/cost/state machinery, adapters, verification framework and runtime.

### Verdict
Correct owner for the reusable DecisionEngine interface. Several surrounding modules remain thin foundations and must not be mistaken for mature production implementations.

### Jev already implemented
- typed `src/decision/types.ts`
- `DecisionEngine` with provider fallback/confidence policy
- `JevDecisionProvider` using TypeSafe System One endpoint
- `src/decision/index.ts`
- DecisionEngine exposed by `createCreationOS()`
- unit tests
- CI executes typecheck + tests and is green after implementation

### Next
Add deterministic provider, LLM fallback adapters, durable decision telemetry, cost records, shadow/assist/active modes, calibration/eval harness and consumer SDK/API.

---

# Migration order

## Wave A — foundation
1. Universal BEAST v2 canonicalized.
2. Decision contract canonicalized.
3. Creation OS DecisionEngine established.
4. MGR Agents first real Jev route established.
5. Per-repo read-first contracts established.

## Wave B — reliability before expansion
1. Build provider capability/price/health registry.
2. Add decision telemetry/eval schema.
3. Add shadow mode.
4. Repair MGR Agents DAG guarantees.
5. Replace TIME mock research ingestion.
6. Audit iKickItz stale/free provider assumptions.

## Wave C — product adoption
1. MGR Agents model/agent/handoff routing.
2. iKickItz router/Heirloom/memory.
3. Create Loco repair/operator routing.
4. HU Mind Room routing/context.
5. Dii Heirloom foundational routing.
6. Tax/compliance/capital triage lanes.
7. TIME non-trading decision lanes.
8. Visual Forge bounded QA routing.

## Universal success metric
Do not optimize for "percentage of calls sent to Jev."
Optimize for:
COST PER VERIFIED OUTCOME + LATENCY + ERROR RATE + ESCALATION QUALITY + OWNER CONTROL.

A cheaper wrong decision is not a saving.
