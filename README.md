# Civilization Microtools

An indexed program of small, independently maintained open-source tools for research reproducibility, data quality, security, accessibility, open standards, and trustworthy AI workflows.

## Active research infrastructure

| Project | Public-interest problem | Evidence status | Engineering status | External validation | Repository |
|---|---|---|---|---|---|
| Agent Completion Ledger | Coding-agent workflows can conflate producing output with having executable evidence that supports completion. | `pilot-supported`; `second-source-supported` within documented benchmark-oracle scope | v0.2.0 merged; 177 tests; 95.39% line / 90.81% branch coverage; cross-platform CI, composite Action, and two real-repository dogfood runs passed | `ready-for-external-reproduction`; independent reproduction pending | https://github.com/kodlbegiko/agent-completion-ledger |

### Agent Completion Ledger evidence boundaries

- v0.1.0 fixed pilot: 3,364 generated patches; 2,041 lacked support from the supplied executable oracle under a deliberately weak generated-output baseline; 60.67% inclusive unsupported rate.
- v0.2.0 fixed second source: Multi-SWE-bench Go/MagentLess, 341 completed patches, 25 resolved, 316 unresolved; 92.67% unsupported within the supplied oracle.
- Dogfood: Shipcheck and CSV Snapshot each produced the expected controlled `SUPPORTED`, `FAILED`, and `UNVERIFIABLE` states.
- These results do not establish real-world prevalence, natural-language dishonesty, user adoption, saved reviewer time, or improved patch quality.
- The v0.2.0 Git tag and GitHub Release remain owner actions until separately verified.

Only evidence-supported states are recorded. Projects are not marked released, externally reproduced, or adopted until those events have actually occurred.
