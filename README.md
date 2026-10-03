# TRANTIATE Governed Workflows

**A practical documentation showcase of accountable work performed by humans and AI agents.**

Created by [Max Gupta](https://www.linkedin.com/in/maxgupta), Enterprise Data & AI Leader and creator of TRANTIATE.

## The problem

An AI agent can propose a change without having authority to release it. A technically correct output can still lack evidence, independent review, or business acceptance. This showcase explains how to connect delegated work to a bounded objective, separate checking, and recorded human decisions.

## What this repository contains

- A readable workflow from work assignment to outcome acceptance.
- A summary of the documented SEO and Blog Desk proof of concept.
- Four roles and their responsibilities in this demonstration.
- A conceptual architecture separating making, checking, and human decisions.
- Linked illustrative work-order, Maker, Checker, and Buyer records.
- An explanation of the evidence needed to evaluate a real implementation.

**Status:** Public documentation showcase of TRANTIATE, with a summary drawn from the private optimizer implementation README and fictional educational records. This repository does not run agents or deploy changes. Runtime behavior and business outcomes have not been independently verified here.

## Start here

1. Read [the implementation summary](IMPLEMENTATION.md).
2. Read [the workflow](WORKFLOW.md).
3. Inspect [the architecture](ARCHITECTURE.md).
4. Follow the linked records in [illustrative records](EXAMPLES.md).
5. Read [the evidence boundaries](EVIDENCE.md).

## The roles

| Role | Responsibility | Worker in this illustration |
| --- | --- | --- |
| Seer | Sets direction and resolves exceptions beyond the mandate | Human |
| Maker | Produces a proposed change and supporting evidence | AI agent |
| Checker | Evaluates the proposal against stated criteria | Separate AI agent, with independence assessed |
| Buyer | Evaluates and accepts or rejects the outcome | Human |

These worker assignments describe this illustration. TRANTIATE roles are stable; workers fulfilling them may vary by implementation.

## Example: a bounded website change

A human assigns a small documentation update. The Maker proposes a change. The Checker reviews the diff, scope, links, and claims. The human Buyer records a decision. Any deployment remains a separate authorized action; a Checker pass or Buyer acceptance does not automatically grant release authority.

The same pattern can inform data-platform changes, analytics delivery, and AI-assisted engineering. This repository does not claim those applications have been validated.

## Why this matters for Data & AI leadership

This work makes an architectural question concrete: how can organizations delegate work to AI agents while retaining ownership of objectives, review, and release decisions? The documented proof of concept brings together data modeling, orchestration, software delivery, and governance. It provides a basis for discussing enterprise AI architecture, engineering leadership, and advisory engagements.

## Related independent work

- [TRANTIATE methodology](https://www.trantiate.com/methodology)
- [White paper and companion resources](https://www.trantiate.com/resources)
- [Research](https://www.trantiate.com/research)
- [Max Gupta on ORCID](https://orcid.org/0009-0005-1281-4225)

TRANTIATE and this showcase are independent work. Employer references in the creator's professional biography do not imply sponsorship, endorsement, or deployment.

## Scope and reuse

Illustrative records and conceptual diagrams help readers inspect the operating pattern. They are not a complete policy engine, security control, proof of AI safety, or production orchestration platform. No open-source license is granted by this repository; contact the creator to discuss reuse.
