# Risk classification under the EU AI Act

**You classify a purpose, not a tool.** A procedure for placing AI systems into the classes of Regulation (EU) 2024/1689 in a way others can follow: in the order the regulation itself checks, and with the terms where most classifications go wrong.

[Deutsche Fassung](README.md)

---

## The problem

"Is our chatbot high-risk?" cannot be answered. The same language model can be harmless in product search and a high-risk system in candidate screening. The class does not depend on the model but on the **intended purpose** and on the people its output affects.

That is why every useful classification starts by pinning down the purpose, and ends with a justification that still holds when someone asks in two years why it was decided that way.

## The order

The check has a sequence. Starting with Annex III means checking the wrong thing first.

| # | Question | If yes |
|---|---|---|
| 1 | Is it an **AI system** under Art. 3(1) at all? | continue |
| 2 | Does an **exclusion** apply (military, research, purely personal use)? | the regulation does not apply |
| 3 | Is it a **prohibited practice** under Art. 5? | stop operating it, the check ends here |
| 4 | Is it **high-risk** under Annex I or Annex III? | obligations apply; check the Art. 6(3) derogation |
| 5 | Does a **transparency obligation** under Art. 50 apply? | applies on top, even at minimal risk |

In detail (German): [risk-logic.md](./knowledge-base/eu-ai-act/risk-logic.md)

## Two dates that keep getting mixed up

After the **Digital Omnibus** (Regulation (EU) 2026/1744, in force since 27 Jul 2026):

- **Art. 50 transparency: applies since 2 Aug 2026**, not postponed
- **Annex III high-risk: only from 2 Dec 2027**, postponed by 16 months

Reading this as "the AI Act has been postponed" means running systems that need labelling without labels today. Full overview (German): [overview.md](./knowledge-base/eu-ai-act/overview.md). All dates as JSON and calendar file: [eu-ai-act-dataset](https://github.com/SimpleAct-Compliance/eu-ai-act-dataset).

## The four most common mistakes

1. **Classifying the tool instead of the purpose.** A line saying "ChatGPT: minimal" is not a classification.
2. **Checking Annex III and skipping Art. 5.** Documentation cannot cure a prohibition.
3. **Reading the Art. 6(3) derogation as a free pass.** It requires a documented assessment and falls away as soon as profiling is involved.
4. **Classifying once.** A silent model change at the provider invalidates it without anyone doing anything.

Eight mistakes with a cross-check (German): [common-classification-errors.md](./knowledge-base/eu-ai-act/common-classification-errors.md)

## Contents (German)

| Document | Content |
|---|---|
| [Overview](./knowledge-base/eu-ai-act/overview.md) | structure of the regulation, dates after the Digital Omnibus |
| [Terms](./knowledge-base/eu-ai-act/definitions.md) | AI system, intended purpose, placing on the market, substantial modification |
| [Scope and roles](./knowledge-base/eu-ai-act/scope-and-actors.md) | provider, deployer, and when a deployer becomes a provider |
| [The classification logic](./knowledge-base/eu-ai-act/risk-logic.md) | five steps, Art. 5, Annex I/III, Art. 6(3), Art. 50, GPAI |
| [What each layer rules out](./knowledge-base/eu-ai-act/classification-layers.md) | why the classes are not a ladder |
| [Common mistakes](./knowledge-base/eu-ai-act/common-classification-errors.md) | eight mistakes auditors notice |
| [When to reclassify](./knowledge-base/eu-ai-act/reclassification-logic.md) | six triggers, the silent model change |
| [Classification and governance](./knowledge-base/eu-ai-act/inventory-and-governance.md) | where entries come from, what follows from the class |
| [Template: classification](./templates/risk-classification-template.md) | to fill in, with fields for the reasoning |
| [Template: triggers](./templates/reclassification-trigger-checklist.md) | for periodic review |

Machine-readable: [framework/simpleact-framework.json](./framework/simpleact-framework.json), [llms.txt](./llms.txt)

## Before and after

Classification needs an inventory as input and produces obligations as output:

- before: [AI inventory](https://github.com/SimpleAct-Compliance/simpleact-ai-system-inventory), which systems exist at all
- before: [vendor register](https://github.com/SimpleAct-Compliance/simpleact-model-vendor-register), who supplies the model and what they commit to
- after: [AI Act checklist](https://github.com/SimpleAct-Compliance/simpleact-ai-act-checklist), which obligations follow per class
- after: [incident management](https://github.com/SimpleAct-Compliance/simpleact-incident-management), when something goes wrong in operation

## In software

[SimpleAct](https://simpleact.eu) guides the classification, keeps the reasoning with its history and derives the obligations per class: **[AI risk classification](https://simpleact.eu/ai-risk-classification)**. All 25 Annex III use cases explained: [Annex III](https://simpleact.eu/annex-iii-high-risk-ai).

## Status and licence

Last updated: 2026-11-26. MIT licence, free to use, also commercially. Not legal advice.
