# PUBLIC-MAINT-20261125 — contribution and ownership cleanup

Owner: CTO. Mode: 1. Status: source checks pending. Deadline: UNKNOWN.
PR: https://github.com/fishprovider/kho-bot-public/pull/2

Goal/value: keep this public artifact separate from private exporter/runtime code;
make review, simulation caveats and secret handling unambiguous.
Inputs: current main, existing PR2, unchanged index.html and public contribution rules.
Output: consolidated maintained docs/template/tree; no report or hosting changes.
Method: reconcile main's corrected report URL, remove duplicated draft-status prose,
check every Markdown link and preserved HTML hash, obtain independent exact-source QA.
Acceptance: updated source tree, public-safe docs, artifact unchanged, no secrets/local
.env interface, independent source review and verified merge. Browser/export/served
revision remain separate unrun checks for this documentation-only change.
Next: finish source checks and independent review; merge only accepted candidate.
Gates/dependencies: repository protections, independent reviewer, publication authority.
No historical/private evidence is removed; no runtime or publication action is requested.
