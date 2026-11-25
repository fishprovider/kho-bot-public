# Public change review

Review the complete diff as a reviewer other than its author. Pin actual base/head.
Use public-safe source references; never expose private receipts or identities.

1. Confirm the requested scope and no private data, including embedded compressed payloads.
2. Explain actual before/after technical and strategy effects. Preserve simulation caveats.
3. Check changed references/paths, whitespace and report byte/payload identity when preserved.
4. Run real affected exporter/browser checks if report behavior/data changes. Documentation-only
   checks cannot prove those results; label unrun work and historical evidence honestly.
5. Check environment handling: no secret files/loaders or browser credentials; Doppler belongs
   only at an authorised publication boundary. No mocks, hacks or legacy fallback support.
6. Verify independent exact-candidate disposition, repository merge gates and publication triggers.
   Keep source merge, preview and observed deployed revision separate.
7. Record findings, passed/failed/unrun checks, remaining public-safe task links, owner and next gate.
