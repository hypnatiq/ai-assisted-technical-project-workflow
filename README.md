# AI-Assisted Technical Project Workflow

## What this project is

I use AI to speed up research, documentation, testing, and project work while keeping validation and final decisions in my hands.

That means I define what the project should do, set the safety and privacy boundaries, review the work, check the evidence, and decide what is ready to use. AI can help with implementation and troubleshooting, but I do not treat generated output as proof.

This repository documents that workflow without publishing the private instructions or personal context that make my assistant specific to me.

## Why I documented it

AI can make a project move faster, but speed is not the same as proof. I wanted one public record of the checks I use to keep requirements, privacy, evidence, failed results, and final approval under my control.

## How I work

1. Define the result I want and the limits that must stay in place.
2. Separate verified facts from assumptions, suggestions, and unfinished work.
3. Turn the idea into a draft, test, script, document, or working project.
4. Review the result against the original requirements.
5. Check evidence such as test output, file hashes, screenshots, rendered documents, or source references.
6. Fix failed or unclear results instead of hiding them.
7. Remove private information before anything is shared.
8. Decide whether the result is ready, needs more testing, or should remain private.

## What I remain responsible for

- Project requirements and priorities
- Technical and privacy limits
- Evidence review and interpretation
- Test acceptance and failed-result review
- Final wording and public claims
- Approval before installation, publishing, submission, or sharing

AI can help produce and review work, but it does not replace those decisions.

## Where I have used it

### HypNO

I used the workflow to define investigation requirements, review source changes, separate source testing from installed behavior, organize QA evidence, and prepare technical documentation. A source-test result applies only to the tested candidate. It does not prove installation or live network behavior on another computer.

### AstrasGZ network traffic analysis

I used the workflow to organize packet-capture evidence, separate observations from unsupported security conclusions, prepare sanitized screenshots, and document what remained unverified before the case study could be shared.

### IT support documentation

I used the workflow to structure runbooks and troubleshooting guides around evidence, controlled changes, escalation, rollback, and validation so another technician can follow the work.

### Enterprise home network virtual lab

I used the workflow to define the isolated Hyper-V architecture, preserve recovery boundaries, review failures and corrections, validate accepted and denied network paths, and separate virtual lab results from physical or production claims.

### Project handoffs

I use manifests, SHA-256 hashes, decision records, and acceptance checks when work moves between computers. A copied package is treated as transferred, not automatically accepted or synchronized.

## What this repository does not include

- Private prompt libraries or complete assistant instructions
- Personal memory or correction records
- Machine-specific paths, settings, or security configuration
- Credentials, tokens, browser sessions, or account access
- Raw private project evidence
- Unpublished application source or customer information

The public method is meant to show how I work. It is not a complete copy of the private assistant environment.

## Where to start

1. Read [`docs/Workflow.md`](docs/Workflow.md) for the repeatable process.
2. Read [`docs/Project Examples.md`](docs/Project%20Examples.md) for real examples and their limits.
3. Read [`docs/Public and Private Boundaries.md`](docs/Public%20and%20Private%20Boundaries.md) for what I share and what stays private.
