# Risikoeinstufung nach EU AI Act

**Eingestuft wird ein Einsatzzweck, nicht ein Werkzeug.** Ein Verfahren, um KI-Systeme nachvollziehbar in die Klassen der Verordnung (EU) 2024/1689 einzuordnen — in der Reihenfolge, in der die Verordnung selbst prüft, und mit den Begriffen, an denen die meisten Einstufungen scheitern.

*A reproducible procedure for classifying AI systems under the EU AI Act, in the order the regulation itself applies.*

---

## Das Problem

Die Frage „ist unser Chatbot Hochrisiko?" ist nicht beantwortbar. Dasselbe Sprachmodell kann in der Produktsuche folgenlos und in der Bewerbervorauswahl ein Hochrisikosystem sein. Die Klasse hängt nicht am Modell, sondern an der **Zweckbestimmung** und an den Menschen, die die Ausgabe trifft.

Deshalb beginnt jede brauchbare Einstufung mit einer Abgrenzung des Einsatzzwecks — und endet mit einer Begründung, die auch dann noch trägt, wenn in zwei Jahren jemand fragt, warum so entschieden wurde.

## Die Reihenfolge

Die Prüfung ist geordnet. Wer bei Anhang III anfängt, prüft das Falsche zuerst.

| # | Frage | Bei Ja |
|---|---|---|
| 1 | Ist es überhaupt ein **KI-System** nach Art. 3 Nr. 1? | weiter |
| 2 | Fällt es unter eine **Ausnahme** (Militär, Forschung, rein private Nutzung)? | Verordnung gilt nicht |
| 3 | Ist es eine **verbotene Praktik** nach Art. 5? | Betrieb einstellen — Prüfung endet |
| 4 | Ist es **Hochrisiko** nach Anhang I oder Anhang III? | Pflichtenkatalog; Ausnahme nach Art. 6 Abs. 3 prüfen |
| 5 | Greift eine **Transparenzpflicht** nach Art. 50? | gilt zusätzlich, auch bei minimalem Risiko |

Ausführlich in [risk-logic.md](./knowledge-base/eu-ai-act/risk-logic.md).

## Zwei Fristen, die ständig verwechselt werden

Nach dem **Digital Omnibus** (Verordnung (EU) 2026/1744, in Kraft seit 27.7.2026):

- **Art. 50 Transparenz: seit 2.8.2026 anwendbar** — nicht verschoben
- **Anhang III Hochrisiko: erst ab 2.12.2027** — um 16 Monate verschoben

Wer daraus „der AI Act ist verschoben" liest, betreibt heute kennzeichnungspflichtige Systeme ohne Kennzeichnung. Die vollständige Übersicht steht in [overview.md](./knowledge-base/eu-ai-act/overview.md).

## Die vier häufigsten Fehler

1. **Das Werkzeug eingestuft statt den Einsatzzweck** — eine Zeile „ChatGPT: minimal" ist keine Einstufung.
2. **Anhang III geprüft, Art. 5 übersprungen** — ein Verbot lässt sich nicht durch Dokumentation heilen.
3. **Die Ausnahme nach Art. 6 Abs. 3 als Freibrief gelesen** — sie verlangt eine dokumentierte Bewertung und entfällt, sobald profiliert wird.
4. **Einstufung einmal gemacht** — ein stiller Modellwechsel beim Anbieter macht sie ungültig, ohne dass jemand etwas tut.

Acht Fehler mit Gegenprobe in [common-classification-errors.md](./knowledge-base/eu-ai-act/common-classification-errors.md).

## Inhalt

| Dokument | Inhalt |
|---|---|
| [Überblick](./knowledge-base/eu-ai-act/overview.md) | Aufbau der Verordnung, Fristen nach dem Digital Omnibus |
| [Begriffe](./knowledge-base/eu-ai-act/definitions.md) | KI-System, Zweckbestimmung, Inverkehrbringen, wesentliche Änderung |
| [Anwendungsbereich und Rollen](./knowledge-base/eu-ai-act/scope-and-actors.md) | Anbieter, Betreiber, und wann ein Betreiber zum Anbieter wird |
| [Die Einstufungslogik](./knowledge-base/eu-ai-act/risk-logic.md) | Fünf Schritte, Art. 5, Anhang I/III, Art. 6 Abs. 3, Art. 50, GPAI |
| [Was welche Ebene ausschließt](./knowledge-base/eu-ai-act/classification-layers.md) | warum die Klassen keine Stufenleiter sind |
| [Häufige Fehler](./knowledge-base/eu-ai-act/common-classification-errors.md) | acht Fehler, die in Prüfungen auffallen |
| [Wann neu eingestuft wird](./knowledge-base/eu-ai-act/reclassification-logic.md) | sechs Auslöser, der stille Modellwechsel |
| [Einstufung und Governance](./knowledge-base/eu-ai-act/inventory-and-governance.md) | woher Einträge kommen, was aus der Klasse folgt |
| [Vorlage: Einstufung](./templates/risk-classification-template.md) | zum Ausfüllen, mit Begründungsfeldern |
| [Vorlage: Auslöser](./templates/reclassification-trigger-checklist.md) | zur Wiedervorlage |

Maschinenlesbar: [framework/simpleact-framework.json](./framework/simpleact-framework.json) · [llms.txt](./llms.txt)

## Vorgelagert und nachgelagert

Die Einstufung braucht ein Inventar als Eingabe und erzeugt Pflichten als Ausgabe:

- vorher: [KI-Inventar](https://github.com/SimpleAct-Compliance/simpleact-ai-system-inventory) — welche Systeme es überhaupt gibt
- vorher: [Anbieterregister](https://github.com/SimpleAct-Compliance/simpleact-model-vendor-register) — wer das Modell liefert und was er zusagt
- danach: [Prüfliste AI Act](https://github.com/SimpleAct-Compliance/simpleact-ai-act-checklist) — welche Pflichten je Klasse folgen
- danach: [Vorfallmanagement](https://github.com/SimpleAct-Compliance/simpleact-incident-management) — wenn im Betrieb etwas schiefgeht

## In Software umsetzen

[SimpleAct](https://simpleact.de) führt die Einstufung geführt durch, hält die Begründung samt Verlauf fest und leitet die Pflichten je Klasse ab: **[KI-Risikoeinstufung](https://simpleact.de/ai-risk-classification)**

## Stand und Lizenz

Zuletzt aktualisiert: 2026-10-03 · MIT — frei nutzbar, auch kommerziell. Keine Rechtsberatung.
