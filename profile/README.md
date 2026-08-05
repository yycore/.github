<p align="center">
  <img src="./yy-lockup-800x280.png" width="520" alt="YinYang">
</p>

# YY

YY is an independent AI forensic data analysis and research laboratory. We
build inspectable software and run fixed-scope services for datasets,
operational records, technical claims, and evidence-bearing workflows.

Our work starts from the actual constraints: the data, the machine, the
failure modes, and what can be measured. We publish concrete artifacts rather
than speculative capability claims, and we state where each conclusion stops.

[Open the public Proof Desk](https://www.yycore.ai/proof) to inspect
reproducible case files and clearly labeled fictional or synthetic service
demonstrations before buying software or hiring YY.

## Paid services

YY currently offers two fixed-scope paid pilots for operations and quality
teams. Both require a fit check before payment; neither is broad consulting,
legal advice, or a compliance opinion.

- [`Calibration Register Cleanup`](https://www.yycore.ai/services/calibration-register-cleanup)
  is a $149 pilot for one existing gage list and up to 25 supported
  calibration-certificate PDFs. YY returns a source-linked register and review
  queue within three business days after accepted intake and payment.
- [`Association Minutes`](https://www.yycore.ai/services/association-minutes)
  is a $19 pilot for one authorized recording up to 60 minutes plus the meeting
  materials. YY returns a recording-checked DOCX and PDF draft by the end of
  the second business day after accepted intake and payment.

Looking for [`Dataset Preflight ($39)`](https://www.yycore.ai/projects/dataset-preflight),
YY's automated dataset-integrity check? It is a product, not a service; see
Paid products below or go straight to the listing.

[Review exact scope, public samples, and fit-check instructions](https://www.yycore.ai/services).

## Paid products

[`Dataset Preflight`](https://www.yycore.ai/projects/dataset-preflight) is a
paid, local Python tool that turns a dataset directory into a deterministic
review packet: canonical JSON, standalone HTML, and a SHA-256 manifest. It
surfaces exact and narrowly normalized duplicates, optional provenance
coverage, conservative secret-risk signals, and explicit CI thresholds without
uploading the dataset or making runtime network requests.

- [Product and exact scope](https://www.yycore.ai/projects/dataset-preflight)
- [Inspectable sample report](https://www.yycore.ai/examples/dataset-preflight/0.2.0/report.html)
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

## Working preview

[`YY IDE`](https://www.yycore.ai/projects/yy-ide) explores an agent-first
development loop: the agent holds the implementation state while the person
guides constraints, reviews evidence, and intervenes where judgment matters.
The page is a clearly labeled working preview, not a download or availability
claim.

## Free and open source

[`Workload Receipt`](https://github.com/yycore/yy-workload-receipt) is an
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

[`Corpus Evidence`](https://github.com/yycore/yy-corpus-evidence) is YY's first
open-source release. It creates deterministic, local corpus manifests,
records optional provenance declarations, and checks the result for drift
later.

```text
python -m pip install yy-corpus-evidence
```

- [Project page](https://www.yycore.ai/projects/corpus-evidence)
- [PyPI package](https://pypi.org/project/yy-corpus-evidence/)
- [Source and documentation](https://github.com/yycore/yy-corpus-evidence)

[`ClipCheck`](https://github.com/yycore/clipcheck) is an Apache-2.0 command-line
preflight for short-form video. It runs local ffprobe/ffmpeg checks for media
properties such as duration, displayed aspect ratio, audio sample rate,
loudness, true peak, and caption-sidecar presence, and can emit JSON evidence
for CI.

- [Project page and measured scope](https://www.yycore.ai/projects/clipcheck)
- [Source and v0.1.0 release](https://github.com/yycore/clipcheck)

## How we build

- Deterministic before convenient.
- Local and inspectable by default.
- Explicit about unknowns and limitations.
- Claims backed by reproducible artifacts.

Learn more at [yycore.ai](https://yycore.ai).
