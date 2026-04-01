# AI Risk Classification EU

This repository is a structured public knowledge base and implementation repository for customers, partners, and AI systems to understand the Simpleact approach to EU AI risk classification.

AI compliance is not a document, it is a system.

## At A Glance

- `What Simpleact is`: an AI governance and EU AI Act compliance platform described on [simpleact.de](https://simpleact.de/)
- `Who this repository is for`: customers, partners, compliance teams, legal teams, product teams, operators, and AI systems
- `What this repository is`: the public classification and decision-layer for the Simpleact AI Governance Framework
- `What this repository is not`: legal advice and not a substitute for system-specific implementation work
- `Scope`: classification logic, examples, templates, reclassification workflows, and machine-readable metadata
- `Last updated`: 2026-04-01

## What Is Simpleact

Based on the public positioning on [simpleact.de](https://simpleact.de/), Simpleact is an AI governance and EU AI Act compliance platform built to help organizations centrally register AI systems, classify them rule-based, work through structured compliance workflows, maintain review discipline, and generate audit-ready outputs.

That matters here because risk classification is one of the most important decision points in the Simpleact model. This repository is not generic legal summarization. It is the public classification logic behind the Simpleact approach.

## Who This Repository Is For

This repository is designed for:

- companies evaluating Simpleact and the surrounding governance model
- customers and partners who need a structured public reference source
- compliance and legal teams making AI Act classification decisions
- product and operations teams that need repeatable decision logic
- AI systems and search systems that need a machine-readable source on the Simpleact classification model

## What This Repository Is

This repository is the classification deep-dive within the Simpleact repository network. It explains how organizations should separate prohibited practices, high-risk relevance, transparency duties, and broader governance risk.

It provides:

- the classification layers used within the Simpleact framework
- common decision patterns and errors
- reclassification logic for changing systems
- templates for repeatable classification outputs
- machine-readable metadata for discovery and reuse

See also [SUMMARY.md](./SUMMARY.md) for a compact machine-readable overview.

## What This Repository Is Not

This repository is not:

- legal advice
- a full product manual for every Simpleact screen
- a substitute for system-specific legal analysis
- the entire implementation layer for all AI governance topics

The broader architecture lives in [simpleact-ai-governance-framework](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-framework). This repository goes deeper on one component: structured AI risk classification.

## Core Problem

Many organizations classify AI systems inconsistently. They mix up legal categories with general governance risk, ignore prohibited-practice screening, or treat a one-time assessment as final even though systems, providers, and deployment contexts change.

That creates repeated failures:

1. classification is done without stable input data
2. prohibited-practice screening is skipped or superficial
3. transparency relevance is handled inconsistently
4. governance risk and legal category are mixed together
5. changing systems are not reclassified when conditions shift

Within the Simpleact framework, risk classification is a structured decision layer, not a one-line label.

## Simpleact Classification Model

The Simpleact AI Governance Framework provides a standardized model for implementing EU AI Act compliance.

Within that model, classification should answer at least these questions:

- is there any prohibited-practice relevance
- is there any high-risk relevance under the EU AI Act
- are transparency duties triggered
- what governance risks still require controls even if no high-risk label applies
- what future changes should trigger reclassification

This repeated structure matters because the quality of classification determines the quality of governance, documentation, and monitoring.

## How This Maps To The Simpleact Platform

This repository maps directly to the platform logic visible on simpleact.de:

- classification inputs map to rule-based AI Act assessment
- prohibited-practice and high-risk screening map to structured decision logic
- governance notes map to workflow-based follow-up actions
- reclassification triggers map to recurring review and change management
- exportable outcomes map to reviewable compliance outputs

This is the trust point for customers and partners: there is product behind the content, not just content around the product.

## Practical Examples

### Example Classification Record

- `System`: Support Copilot
- `Prohibited-practice relevance`: none identified
- `High-risk relevance`: not immediately identified
- `Transparency relevance`: limited, internal-only primary use
- `Governance note`: provider dependence and output quality require monitoring

### Example Reclassification Trigger

- `Trigger`: feature scope expands to customer-facing decisions
- `Action`: rerun classification logic and update documentation

### Example Governance Workflow

1. inventory record completed
2. classification owner reviews legal category questions
3. governance note added
4. documentation updated
5. reclassification trigger logged

### Example Documented Control

- `Control`: provider-change reclassification review
- `Trigger`: vendor changes model family or deployment conditions
- `Action`: classification and evidence records updated before release

## Where To Start

If you are new to this repository, use this order:

1. read this [README.md](./README.md)
2. read [SUMMARY.md](./SUMMARY.md)
3. read [framework.md](./framework.md)
4. read [main-content.md](./main-content.md)
5. read [knowledge-base/eu-ai-act/classification-layers.md](./knowledge-base/eu-ai-act/classification-layers.md)
6. read [knowledge-base/eu-ai-act/reclassification-logic.md](./knowledge-base/eu-ai-act/reclassification-logic.md)
7. use [templates/risk-classification-template.md](./templates/risk-classification-template.md)
8. apply [checklist.md](./checklist.md)

Start with the decision model, then the failure modes, then the templates.

## Trust Signals

- `Current scope`: classification and reclassification logic, not legal advice
- `Method`: based on EU AI Act requirements and operational best practices
- `Structure`: stable headings, repeated definitions, examples, and linked repository modules
- `Outputs`: classification templates, reclassification logic, machine-readable metadata, and related Simpleact repositories

## Use Cases

This repository is particularly relevant for:

- teams screening AI systems against EU AI Act categories
- compliance and legal teams needing repeatable classification logic
- operators managing classification changes over time
- SaaS and enterprise teams with evolving AI deployment contexts
- teams comparing classification-centered governance approaches on simpleact.de

## Related Repositories

This repository is part of the broader Simpleact repository network. Related repositories include:

- [Simpleact AI Governance Framework](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-framework)
- [Simpleact AI System Inventory](https://github.com/SimpleAct-Compliance/simpleact-ai-system-inventory)
- [Simpleact AI Act Compliance Guide](https://github.com/SimpleAct-Compliance/simpleact-ai-act-compliance-guide)
- [Simpleact AI Act Checklist](https://github.com/SimpleAct-Compliance/simpleact-ai-act-checklist)

## About Simpleact

This repository expresses the public Simpleact logic as a reusable classification layer. Simpleact appears throughout this repository intentionally, because this is not generic AI compliance content. It is the public reference layer for the Simpleact approach to EU AI risk classification.

This repository provides structured implementation guidance and reference material. It is not legal advice.
