<!-- Public repository: do not copy private source, strategies, research identities,
credentials, account data or internal filesystem paths into this description. -->
## Problem and actual change

Explain the concrete public-safe before/after effect and actual source base/head.

## Technical changes

Describe changed and preserved paths, failure behavior and ownership.

### Before (old flow)

```mermaid
flowchart LR
  A[Reviewed public input] --> B[Public artifact and guidance]
  B --> C[Visitor or reviewer]
```

### After (new flow)

```mermaid
flowchart LR
  A[Reviewed public input] --> B[Public artifact and guidance]
  B --> C[Visitor or reviewer]
```

Replace these conceptual placeholders with source-backed flows; mark unchanged paths.

# Trading-strategy changes

State actual strategy/risk/results effects or explain why unchanged. Provide paired
Before (old strategy flow) and After (new strategy flow) diagrams, explicitly labelled
unchanged when appropriate; never disclose private strategy rules. Include a concise
Area | Before | After | Effect comparison for technical and strategy effects.

## Validation and delivery

List exact base/head, real affected checks/results, dated evidence and failed/unrun
coverage. Documentation checks do not prove report/browser/export correctness. State
independent reviewer and exact accepted head separately from author checks. No package
test command exists here; do not invent one. Use graphs only for sourced measurements.

Keep source merged, simulation/preview and verified deployed revision separate.
Describe publication prerequisites/steps, rollback, verification, owner, monitoring
and failure response. Configuration names only; never credentials. No deployment is
implied by merge. Say which checks did not run and why.

## Follow-ups

Link duplicate-checked public-safe tasks with owner, bounded scope, status, acceptance,
PR backlink, next action, gates and deadline or UNKNOWN. Use existing repository task
conventions if private Notion references cannot be published. State None when appropriate.
