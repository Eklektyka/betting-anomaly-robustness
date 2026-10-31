# Do Published Betting-Market Anomalies Survive?

Whether anomalies reported in the betting-markets literature survive
re-testing under one common protocol on sharp closing prices, and whether
they decay after publication.

**Status:** In progress — design stage. Registered on OSF on 27 October 2026.
Pre-analysis plan to be filed before any estimation. The OSF registration
timestamps the research question and design; the pre-analysis plan will be
registered before any data is touched.

---

## Why this matters

Hundreds of papers report mispricing in pre-match sports betting markets.
Researcher degrees of freedom — the de-vigging method, the price source and
its timestamp, look-ahead covariates, subgroup mining — can create anomalies
that are not there. Finance has done population-level re-tests for stock-return
anomalies (McLean and Pontiff 2016; Hou, Xue and Zhang 2020; Chen and
Zimmermann 2022). To my knowledge, no population-level re-test exists for betting markets.

## Planned scope

First leg: association football and tennis, where free odds data with closing
prices exist.

## Approach

- Census of published claims of mispricing, bias or profitable strategies in
  pre-match betting markets (~290 papers screened).
- Tiering by whether each claim can be reproduced or re-estimated on free data.
- One pre-registered re-test protocol (de-vig method, test forms, sample
  window, staking rule), applied uniformly, with every deviation from the
  original specification recorded.
- Post-publication decay comparison: each claim's effect across in-sample,
  post-sample pre-publication and post-publication windows.

## What is not in this repo yet

The census, protocol and code are kept private until the pre-analysis plan is
registered.

## License

Code: [MIT](LICENSE). Text and figures: [CC BY 4.0](LICENSE).
