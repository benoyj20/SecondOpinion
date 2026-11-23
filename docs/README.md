# Documentation

## Using SecondOpinion

- [Full guide](GUIDE.md): step-by-step setup for macOS, Linux and Windows, every screen, the verdict rules,
  sealed envelopes, configuration, tests, troubleshooting and limitations
- [Architecture](ARCHITECTURE.md): diagrams of the system, how one claim is routed and the decision rules; every
  tolerance and where it lives in the code; what the AI helper sees; API routes, screens and the module map
- [Web design system](../apps/web/DESIGN.md): typography, colour tokens and the rules every screen follows

Diagrams and screenshots live in [`media/`](media). The SVG diagrams are hand-written and can be edited as text.

## Project

- [Build plan and scope](PLAN.md), as written at the start of the hackathon
- [Implementation plan: tasks, owners, timeline](superpowers/plans/2026-11-12-secondopinion-claim-auditor.md)
- Feature designs and plans: [claim split and join](superpowers/specs/2026-11-14-claim-split-and-join-design.md),
  [role-aware review](superpowers/specs/2026-11-14-role-aware-review-design.md),
  [review claim layout](superpowers/specs/2026-11-14-review-claim-layout-design.md),
  [three-column review](superpowers/specs/2026-11-14-review-three-column-design.md)
  (each has a matching plan in [`superpowers/plans/`](superpowers/plans))
- [Idea analysis](Idea_Analysis_Report.pdf) and [idea and build guide](Evidentia_Idea_and_Build_Guide.pdf)
- [Stack implementation references](STACK_REFERENCES.md), collected from official framework docs on 2026-11-12

## Test logs

- [Hard cases](HARD_CASES_BUGS.md): sentences with hand-worked verdicts, rules only versus rules plus AI, and the
  bugs they found (baseline 2026-11-14)
- [Blind-set baseline](../tests/blind/BASELINE.md): scores on the blind dev sets before the coverage gate and
  AI split (2026-11-14)

## Official challenge

The organizers' challenge repository is bundled in
[`oncosys-hackathon-challenge/`](../oncosys-hackathon-challenge) (the app uses its `fetch.py` and
`envelopes/unseal.py`; its TCGA data is downloaded, not committed). A selected snapshot of the documents is
also kept here:

- [Source and snapshot commit](challenge/SOURCE.md)
- [Challenge overview](challenge/README.md)
- [Rules](challenge/RULES.md)
- [Submission checklist](challenge/SUBMISSION_CHECKLIST.md)
- [Research Claim Auditor specification](challenge/products/research-claim-auditor.md)
- [Practice brief](challenge/products/research-claim-auditor/practice_brief.md)
- [TCGA-BRCA dataset guide](challenge/data/tcga-brca/README.md)
- [Shared findings format](challenge/format/README.md)
- [JSON schema](challenge/format/findings.schema.json)
- [Validator](challenge/format/validate.py)
- [Data licenses](challenge/DATA_LICENSES.md)

The snapshot is not a live sync. See the source note for provenance and omitted files.
