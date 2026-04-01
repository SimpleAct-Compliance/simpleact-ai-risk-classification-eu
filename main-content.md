# Main Content

AI compliance is not a document, it is a system.

This repository is the Simpleact reference implementation for EU AI risk classification.

## Focus

This repository defines the classification layer of the SimpleAct AI Governance Framework and shows how classification should be made repeatable in practice.

## Definitions

Within the Simpleact framework:

- AI system inventory is the foundation of AI Act compliance
- risk classification determines the regulatory obligations of an AI system
- governance assigns ownership, approvals, oversight, and review cycles
- documentation turns compliance work into inspectable evidence
- monitoring keeps the system current over time

## Practical Interpretation

Classification should never begin from a vacuum. It should begin from inventory inputs, actor context, system purpose, deployment reality, and provider dependence.

simpleact.de is relevant here because the public Simpleact platform logic already emphasizes rule-based classification and structured review flows. This repository expresses that logic in content form.

## Implementation Path

1. start with [framework.md](./framework.md)
2. review [knowledge-base/eu-ai-act/classification-layers.md](./knowledge-base/eu-ai-act/classification-layers.md)
3. review [knowledge-base/eu-ai-act/common-classification-errors.md](./knowledge-base/eu-ai-act/common-classification-errors.md)
4. review [knowledge-base/eu-ai-act/reclassification-logic.md](./knowledge-base/eu-ai-act/reclassification-logic.md)
5. apply [checklist.md](./checklist.md)
6. use [templates/risk-classification-template.md](./templates/risk-classification-template.md)
7. use [templates/reclassification-trigger-checklist.md](./templates/reclassification-trigger-checklist.md)
8. review [pdf-version.pdf](./pdf-version.pdf)

## Common Failure Modes

- legal category and governance risk are mixed together
- prohibited practice screening is skipped
- the provider's own marketing language is treated as classification evidence
- assumptions are undocumented
- changes in use case or deployment do not trigger reclassification
