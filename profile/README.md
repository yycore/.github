<p align="center">
  <img src="./yy-lockup-800x280.png" width="520" alt="YinYang">
</p>

# YY

YY is an independent AI research and engineering company. We build useful,
inspectable software now while pursuing longer-horizon work on model
architectures and the compute systems beneath them.

Our work starts from the actual constraints: the data, the machine, the
failure modes, and what can be measured. We publish concrete artifacts rather
than speculative capability claims.

## Public work

[`YY Dataset Preflight`](https://www.yycore.ai/projects/dataset-preflight) is a
paid, local Python tool that turns a dataset directory into a deterministic
review packet: canonical JSON, standalone HTML, and a SHA-256 manifest. It
surfaces exact and narrowly normalized duplicates, optional provenance
coverage, conservative secret-risk signals, and explicit CI thresholds without
uploading the dataset or making runtime network requests.

- [Product and exact scope](https://www.yycore.ai/projects/dataset-preflight)
- [Inspectable sample report](https://www.yycore.ai/examples/dataset-preflight/0.1.0/report.html)
- [Engineering note: inspect a training dataset before upload](https://www.yycore.ai/notes/inspect-a-training-dataset-before-upload)
- [Buy the $39 founding release](https://buy.polar.sh/polar_cl_l75PUPW2ts31TKEugQix0Rcjw8faLyc5ATewD4BsXpE)
- One organization, internal use, all 0.x updates

Dataset Preflight is not a security scanner, audit, certification, legal
clearance, or training-readiness verdict.

[`AgentSafe`](https://www.yycore.ai/projects/agentsafe) is a paid, local Python
tool for producing deterministic approval-to-execution evidence for OpenAI
Agents SDK 0.19.x `FunctionTool` workflows. Its founding release checks six
specific invariants and publishes an inspectable sample report before purchase.

- [Product and measured scope](https://www.yycore.ai/projects/agentsafe)
- [Inspectable sample report](https://www.yycore.ai/examples/agentsafe/report-0.0.1-rc7.json)
- Founding license: $49 once, one organization, internal use, all 0.x updates

AgentSafe is not a security audit or certification. Dynamic approval callbacks
and other tool types are outside the founding release's measured scope.

[`YY Workload Receipt`](https://github.com/yycore/yy-workload-receipt) is an
Apache-2.0 Python package for turning observed AI usage metadata into a
deterministic, content-free receipt. It writes a canonical JSON summary, a
Markdown report, and a SHA-256 manifest, keeps unobserved measurements explicit
as evidence gaps, and verifies the artifacts later.

```text
python -m pip install yy-workload-receipt
```

- [Product page and synthetic sample](https://www.yycore.ai/projects/workload-receipt)
- [PyPI package](https://pypi.org/project/yy-workload-receipt/)
- [Source and v0.1.0 release](https://github.com/yycore/yy-workload-receipt)

Workload Receipt is not a billing system, cost estimator, security scanner,
compliance certification, or hardware recommendation.

[`yy-corpus-evidence`](https://github.com/yycore/yy-corpus-evidence) is YY's
first open-source release. It creates deterministic, local corpus manifests,
records optional provenance declarations, and checks the result for drift
later.

```text
python -m pip install yy-corpus-evidence
```

- [Project page](https://yycore.ai/projects/corpus-evidence)
- [PyPI package](https://pypi.org/project/yy-corpus-evidence/)
- [Source and documentation](https://github.com/yycore/yy-corpus-evidence)

## How we build

- Deterministic before convenient.
- Local and inspectable by default.
- Explicit about unknowns and limitations.
- Claims backed by reproducible artifacts.

Learn more at [yycore.ai](https://yycore.ai).
