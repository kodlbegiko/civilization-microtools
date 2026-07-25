# Civilization Microtools

An indexed program of small, independently maintained open-source tools for research reproducibility, data quality, security, accessibility, open standards, and trustworthy AI workflows.

## Active research infrastructure

| Project | Public-interest problem | Evidence status | Engineering status | External validation | Repository |
|---|---|---|---|---|---|
| Agent Completion Ledger | Coding-agent workflows can conflate producing output with having repository and CI evidence that supports completion. | v0.1.0 pilot-supported and v0.2.0 second-source-supported only within documented benchmark-oracle scope; real reviewer value remains untested | `ENGINEERING COMPLETE`; v0.3.0 released; 189-test cross-platform release CI passed; `FEATURE FREEZE`; mixed-case remote-URL source fix merged under a security exception, v0.3.1 patch release pending | `READY FOR EXTERNAL VALIDATION`; 0 real participants, 0 non-author repositories, 0 independent reproductions, 0 independent security reviewers; 30-target owner-reviewed recruitment package prepared; executable-mode external integration paused until verified v0.3.1 | https://github.com/kodlbegiko/agent-completion-ledger |

### Agent Completion Ledger evidence boundaries

- v0.1.0 fixed pilot: 3,364 generated patches; 2,041 lacked support from the supplied executable oracle under a deliberately weak generated-output baseline; 60.67% inclusive unsupported rate.
- v0.2.0 fixed second source: Multi-SWE-bench Go/MagentLess, 341 completed patches, 25 resolved, 316 unresolved; 92.67% unsupported within the supplied oracle.
- v0.3.0 engineering release: Trusted Contract Mode, `--no-exec`, provenance-rich reports, experimental in-toto output, GitHub Artifact Attestation guidance, and interoperability documentation.
- Release engineering: 189 tests passed with Linux, Windows, and macOS CI; wheel and sdist build/smoke tests passed. The package is not yet published on PyPI, and project-built wheel/sdist/checksum Release assets remain owner actions.
- Author-owned evidence: Shipcheck, CSV Snapshot, and external-validation-operations dogfood cannot count as external adoption or human outcome evidence.
- External study: fixed research question, preregistered H1/H0/H2, participant-balanced primary analysis, 30-candidate recruitment matrix, non-sent outreach drafts, integration template, and independent security-review package are prepared.
- Security status: v0.3.0 has a case-sensitive remote-URL rejection defect. The source fix is merged, but the immutable v0.3.0 release remains affected until a verified v0.3.1 patch is published. ACL is not a sandbox.
- These results do not establish real-world prevalence, adoption, saved reviewer time, improved decisions, software correctness, independent security adequacy, or public impact.

Only evidence-supported states are recorded. Projects are not marked externally validated, adopted, or impactful until qualifying non-author evidence exists.
