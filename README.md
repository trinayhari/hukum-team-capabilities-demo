# Northstar · AI capabilities

A fictional product engineering team's shared skills, agents and operating procedures.
Northstar maintains a subscription API and an internal support console. Engineers use
this library to make agent-assisted changes consistent, reviewable and safe.

**This is a hukum demo repository.** Team details, tickets and operational examples
are synthetic. The branch skill is attributed to the Sentry skills library.

## Capability library

| Capability | Purpose | Demo evaluation |
| --- | --- | --- |
| [Create branch](skills/create-branch/SKILL.md) | Start work without losing existing changes | Six accepted tasks; fresh paired run planned |
| [Draft commit](skills/draft-commit/SKILL.md) | Describe a change and link its ticket | Context only; not evaluated in this demo |
| [Review change](skills/review-change/SKILL.md) | Find actionable defects and missing evidence | Context only |
| [Triage incident](skills/triage-incident/SKILL.md) | Diagnose from evidence and escalate safely | Context only |
| [Document API](skills/document-api/SKILL.md) | Explain behavior and examples accurately | Context only |
| [Write release notes](skills/release-notes/SKILL.md) | Communicate user-visible changes | Context only |

## How our team works

The [developer agent](agents/developer.md) prepares changes. The
[reviewer agent](agents/reviewer.md) challenges correctness and evidence.
Both use the [change review SOP](sops/change-review.md), [incident SOP](sops/incident-escalation.md)
and [release SOP](sops/release-preparation.md). Team rules live in
[engineering conventions](references/engineering-conventions.md).

## What hukum demonstrates

A skill-changing PR compares the current and proposed instructions on the same six
approved branch tasks. A real model selects bounded actions that execute in disposable
Git repositories. Deterministic state checks and separate LLM judgments produce a PR
comment and HTML/JSON report with concrete findings for the skill author.

This walkthrough is operator-assisted. Opening a PR here does not yet trigger a hosted
managed evaluation automatically. Fresh model outputs may differ from earlier demos;
we report observed outcomes rather than promise improvement. See [the demo guide](demo/README.md).

## License and attribution

The create-branch skill is copied from the Sentry-derived controlled skills repository.
See [NOTICE.md](NOTICE.md) and the retained [Apache 2.0 license](LICENSE).
