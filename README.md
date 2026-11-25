# KHO Bot public research

[Open the published report](https://fishprovider.github.io/kho-bot-public/) or open
[index.html](index.html) from disk. This self-contained public artifact needs no
server, dependencies, credentials or environment configuration.

## What the report contains

The November 2026 campaign contains 15 representative choices across three preset
objectives and 65,476 recorded simulated exits. Visitors can inspect monthly equity,
month-end drawdown, rolling/yearly returns, trade details, setup statistics and
strategy-selection timelines. Setup/position names are anonymous.

The historical search used all shown periods. These are simulations, not forward
tests or live account records. Month-end drawdown can understate full-path drawdown;
exit profit/charges do not represent every account profit/cost. Unknown values stay
unknown. No within-minute path or unrealized excursion is invented.

Exact strategy rules/configuration, raw journals, broker data, market history and
private research provenance remain private. Full simulated trade projections are
intentionally public; private archives must never be copied wholesale.

## Export and publication

The maintained exporter and its real tests live in the private research repository.
Its supported command is:

```sh
npm run report:public -- --archive studies/<study>/index.html --template /path/to/kho-bot-public/index.html --output /path/to/new-public.html
```

It validates the reviewed selections and allowed-field projection, refuses to
overwrite output, and never commits, pushes or deploys. Review both HTML and its
decompressed payload before replacing this page. A different campaign/selection
needs a reviewed summary template. This repository stores no exporter copy.

The original presentation handoff reported exit reconciliation and offline browser
checks. Those historical results are not fresh validation of a future replacement.
This documentation cleanup preserves index.html byte for byte; browser/export tests
are unrun for it. Source merge and a simulation preview do not prove a served revision.

## Structure and secrets

[Full source tree](docs/reference/repository-structure.md) distinguishes the deployed
artifact from contribution/review/task documentation. There is no production backend
or local secret-file loader here. Do not introduce .env files or embed secrets in
HTML. Public reporting needs no Doppler config. Any separately authorised publication
credential belongs at the operator/CI boundary in the existing fishprovider Doppler
project; never in browser output. No additional Doppler project is needed here.

Follow [contribution rules](AGENTS.md), the [review checklist](docs/templates/PR-REVIEW-PROMPT.md)
and [.github/pull_request_template.md](.github/pull_request_template.md). Maintained
changes use Mode 1: real affected checks and independent source review before merge.
Publication, hosting settings and research promotion retain their separate gates.
