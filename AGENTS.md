# Public artifact contribution rules

- Keep index.html a reviewed public projection; no private strategy/configuration, credentials, account identifiers, journals or raw broker/history data, including compressed payloads.
- Preserve simulation/selection caveats. A published simulation is not live performance.
- This repository contains only the deployable artifact and maintenance guidance; production exporter/tests remain in the private research repository.
- Use the default PR template and docs/templates/PR-REVIEW-PROMPT.md. Run real affected checks; never substitute mocks or fabricate validation. Preserve historical evidence with its date and scope.
- Obtain independent exact-source QA before an authorised Mode 1 merge. A merge is not proof of publication. Do not enable/change hosting or deploy without applicable authority.
- No local env files, legacy launch paths or browser secrets. If an authorised publication needs a credential, use Doppler at that boundary only.
- Maintain docs/reference/repository-structure.md when tracked paths change.
