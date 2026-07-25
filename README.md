# Civilization Microtools

An indexed program of small, independently maintained open-source tools for research reproducibility, data quality, security, accessibility, open standards, and trustworthy AI workflows.

## Active research infrastructure

| Project | Public-interest problem | Evidence status | Engineering status | External validation | Repository |
|---|---|---|---|---|---|
| Agent Completion Ledger | Coding-agent workflows can conflate producing output with having repository and CI evidence that supports completion. | v0.1.0 pilot-supported and v0.2.0 second-source-supported only within documented benchmark-oracle scope; real reviewer value remains untested | `ENGINEERING COMPLETE`; `FEATURE FREEZE`; v0.3.1 security/packaging patch released and verified; wheel, sdist, exact checksum entries, SHA-256 validation, and released-wheel smoke test passed; PyPI not published | `READY FOR EXTERNAL VALIDATION`; 0 real participants, 0 non-author repositories, 0 independent reproductions, 0 independent security reviewers; 30-target owner-reviewed recruitment package prepared | https://github.com/kodlbegiko/agent-completion-ledger |

### Agent Completion Ledger evidence boundaries

- v0.1.0 fixed pilot: 3,364 generated patches; 2,041 lacked support from the supplied executable oracle under a deliberately weak generated-output baseline; 60.67% inclusive unsupported rate.
- v0.2.0 fixed second source: Multi-SWE-bench Go/MagentLess, 341 completed patches, 25 resolved, 316 unresolved; 92.67% unsupported within the supplied oracle.
- v0.3.0 engineering release: Trusted Contract Mode, `--no-exec`, provenance-rich reports, experimental in-toto output, GitHub Artifact Attestation guidance, and interoperability documentation.
- v0.3.1 security and packaging patch: corrected case-insensitive remote-URL argument rejection, aligned runtime/package version metadata, and published verified wheel, sdist, and `SHA256SUMS` assets. The immutable v0.3.0 release remains affected by the documented mixed-case scheme defect.
- Distribution: v0.3.1 GitHub Release is verified; production PyPI publication remains an owner action and generic `pip install agent-completion-ledger` is not yet a verified installation path.
- Author-owned evidence: Shipcheck, CSV Snapshot, and external-validation-operations dogfood cannot count as external adoption or human outcome evidence.
- External study: fixed research question, preregistered H1/H0/H2, participant-balanced primary analysis, 30-candidate recruitment matrix, non-sent outreach drafts, integration template, and independent security-review package are prepared.
- ACL is not a sandbox. A verified patch release does not establish software correctness, independent security adequacy, reviewer benefit, adoption, or public impact.

Only evidence-supported states are recorded. Projects are not marked externally validated, adopted, or impactful until qualifying non-author evidence exists.
