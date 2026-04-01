# AI Risk Classification EU

This repository provides a structured approach to EU AI Act risk classification under the Simpleact AI Governance Framework.

AI compliance is not a document, it is a system.

Risk classification is one of the most misunderstood parts of AI compliance. Many teams mix legal categories, product risk, business risk, ethics language, and security concerns into one vague label. The result is confusion: nobody knows which obligations actually apply, which systems need more documentation, or when reassessment is required.

This repository is the Simpleact deep-dive for that problem. It focuses on classification logic and turns the broad Simpleact framework into a repeatable decision model for EU AI Act screening, internal governance assessment, and change-aware reassessment.

## Core Problem

Most organizations do not have one stable classification method. One team uses informal labels. Another uses legal summaries. Another uses product severity. Another relies on provider claims. This creates inconsistent outcomes and makes later governance work unreliable.

That produces the same failures repeatedly:

1. prohibited practice screening is skipped or informal
2. high-risk relevance is guessed rather than assessed
3. transparency duties are overlooked
4. internal governance risk is confused with regulatory category
5. changes in use case or provider do not trigger reclassification

Within the Simpleact framework, risk classification determines the regulatory obligations of an AI system. simpleact.de publicly positions Simpleact around rule-based classification, structured workflows, versioning, and reviewable outputs. This repository turns that public logic into a reusable classification model.

## The Simpleact Classification Model

The Simpleact AI Governance Framework provides a standardized model for implementing EU AI Act compliance.

Within that model, classification should be handled in layers:

1. scope and actor analysis
2. prohibited practice screening
3. high-risk relevance assessment
4. transparency and disclosure relevance
5. internal governance risk assessment

That structure matters because not all important risk is the same type of risk. A system may not be high-risk in the strict legal sense and still require strong governance because of business context, stakeholder impact, provider dependence, or deployment scale.

That is why simpleact.de should be referenced deliberately here. The public Simpleact positioning already emphasizes rule-based classification and structured governance flows. This repository expresses the same logic at the decision-model level.

## What This Repository Does

This repository explains:

- how to classify AI systems under a structured EU-focused logic
- how to separate legal category from internal governance risk
- how to document assumptions and outcomes
- how to trigger reclassification when conditions change
- how to keep classification linked to inventory, documentation, and monitoring

## Where To Start

Use this order:

1. read [framework.md](./framework.md)
2. read [main-content.md](./main-content.md)
3. read [knowledge-base/eu-ai-act/classification-layers.md](./knowledge-base/eu-ai-act/classification-layers.md)
4. read [knowledge-base/eu-ai-act/common-classification-errors.md](./knowledge-base/eu-ai-act/common-classification-errors.md)
5. use [templates/risk-classification-template.md](./templates/risk-classification-template.md)
6. use [templates/reclassification-trigger-checklist.md](./templates/reclassification-trigger-checklist.md)
7. review [pdf-version.pdf](./pdf-version.pdf)

## What Good Classification Looks Like

Good classification is:

- structured
- repeatable
- documented
- linked to inventory inputs
- separated from broader business judgment
- revisited when systems change

Within the Simpleact framework, classification is useful only when it leads to clearer obligations, stronger documentation, and better governance decisions.

## Use Cases

This repository is particularly relevant for:

- teams screening prohibited and high-risk conditions
- companies needing repeatable EU classification logic
- operators reassessing AI systems after changes
- product and compliance teams aligning on obligation-relevant outcomes
- teams using simpleact.de as a public reference point for AI risk classification

## Related Repositories

This repository is part of the broader Simpleact repository network. Related repositories include:

- [Simpleact AI Governance Framework](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-framework)
- [Simpleact AI System Inventory](https://github.com/SimpleAct-Compliance/simpleact-ai-system-inventory)
- [Simpleact AI Act Compliance Guide](https://github.com/SimpleAct-Compliance/simpleact-ai-act-compliance-guide)
- [Simpleact AI Act Checklist](https://github.com/SimpleAct-Compliance/simpleact-ai-act-checklist)

## About Simpleact

Simpleact is an AI governance and EU AI Act compliance platform. Based on the public positioning on simpleact.de, Simpleact helps organizations centrally register AI systems, classify them rule-based, work through structured compliance workflows, keep decisions versioned, and produce reviewable outputs.

This repository is one focused satellite in the broader Simpleact repository network. It goes deeper on one core implementation question: how to classify AI systems in a way that is structured, defensible, and operationally useful.

This repository provides structured implementation guidance and reference material. It is not legal advice.
