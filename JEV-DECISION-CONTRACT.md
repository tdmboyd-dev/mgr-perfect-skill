# MGR Decision Intelligence Contract — Jev Adapter

This contract is portable across MGR products.

## What a decision model is for
A decision model handles bounded outputs where the allowed answers are known in advance: choice, score, probability, classification, relevance, route, retry, stop, or escalation.

## Required architecture
Product code -> MGR DecisionEngine -> provider adapters.

Provider order may include:
1. deterministic rules
2. Jev
3. local/open decision model
4. cheap generative model
5. frontier generative model
6. owner/human escalation

Never let product code depend directly on Jev's vendor API when a shared adapter can be used.

## Required operating modes
SHADOW: log what Jev would choose; do not alter behavior.
ASSIST: Jev recommends; existing system chooses.
ACTIVE: Jev controls only evaluated bounded low-impact decisions.
FAIL-CLOSED: sensitive workflows do not silently authorize on provider failure.

## Promotion gate
Before ACTIVE:
- labeled evaluation set exists
- baseline/current system measured
- Jev measured on same set
- confidence threshold calibrated
- low-confidence fallback tested
- timeout/provider outage tested
- prompt-injection/contradiction cases tested
- cost and latency measured
- rollback exists

## Decision record
decisionId
project/task/runId
question/schema version
state hash
provider/model/version
choice/score/probability
confidence/threshold
selected action
fallback/escalation reason
latency
token usage
estimated/actual cost
timestamp

## Forbidden authority
Jev does not authorize permissions, signatures, payments, trades, destructive changes, legal/tax final decisions, canon/owner decisions, or VERIFIED status.
