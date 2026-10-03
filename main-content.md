# Risikoeinstufung nach EU AI Act — Volltext

Dieses Dokument fasst den Inhalt des Repositories in einem Stück zusammen, für Leser und Systeme, die nicht zwischen Dateien springen wollen. Die Einzeldokumente in [knowledge-base/eu-ai-act](./knowledge-base/eu-ai-act/) gehen jeweils tiefer.

## Der Ausgangspunkt

Die Verordnung (EU) 2024/1689 reguliert Verwendung, nicht Technologie. Dasselbe Sprachmodell kann in der Produktsuche folgenlos und in der Bewerbervorauswahl ein Hochrisikosystem sein. Die Klasse hängt an der **Zweckbestimmung** und am Betroffenenkreis, nicht am Modell.

Daraus folgt die Grundregel: **Eingestuft wird ein Einsatzzweck, nicht ein Werkzeug.** Ein Werkzeug mit drei Einsatzzwecken braucht drei Einstufungen. Eine Zeile wie „ChatGPT: minimales Risiko" ist keine Einstufung, sondern eine Abkürzung, die in einer Prüfung nicht hält.

## Die Reihenfolge der Prüfung

1. **Ist es ein KI-System** nach Art. 3 Nr. 1? Maschinengestützt, mit einem Maß an Autonomie, aus Eingaben Ausgaben ableitend. Eine feste Regel in einer Tabelle ist es nicht; der Übergang ist unscharf, und die Begründung gehört festgehalten — auch bei einem Nein.
2. **Greift eine Ausnahme?** Militär und nationale Sicherheit, reine Forschung und Entwicklung vor dem Inverkehrbringen, rein private nicht-berufliche Nutzung.
3. **Ist es eine verbotene Praktik** nach Art. 5? Zehn Praktiken, anwendbar seit 2.2.2025. Ein Treffer beendet die Prüfung: Ein Verbot lässt sich nicht durch Dokumentation heilen.
4. **Ist es Hochrisiko?** Anhang I knüpft an bestehende Produktsicherheitsvorschriften an, Anhang III an acht Einsatzbereiche. Bei Anhang III ist die Ausnahme nach Art. 6 Abs. 3 zu prüfen — mit der Rückausnahme: Wird profiliert, greift sie nicht.
5. **Greift eine Transparenzpflicht** nach Art. 50? Diese Ebene liegt **neben** den anderen, nicht darunter. Sie gilt auch für Systeme mit minimalem Risiko.

Quer zu allem: Liegt ein **Modell mit allgemeinem Verwendungszweck** zugrunde, gelten dessen Pflichten auf einer eigenen Achse. Und Art. 4 KI-Kompetenz gilt unabhängig von der Klasse.

## Die Fristen, und warum sie verwechselt werden

Nach dem Digital Omnibus (Verordnung (EU) 2026/1744, in Kraft seit 27.7.2026):

| Datum | Was |
|---|---|
| 2.2.2025 | Art. 5 verbotene Praktiken, Art. 4 KI-Kompetenz |
| 2.8.2025 | GPAI-Pflichten, Governance, Sanktionen |
| 2.8.2026 | Art. 50 Transparenz — **nicht verschoben** |
| 2.12.2026 | Zwei neue verbotene Praktiken nach Art. 5 (intime Darstellungen ohne Einwilligung, Missbrauchsdarstellungen); Ende der Art.-50-Abs.-2-Übergangsfrist für Bestandssysteme |
| 2.12.2027 | Anhang III Hochrisiko — um 16 Monate **verschoben** |
| 2.8.2028 | Anhang I Hochrisiko |
| 2.8.2030 | Hochrisiko-Bestandssysteme bei Behörden |

Die verbreitete Lesart „der AI Act ist verschoben" ist falsch und teuer: Transparenzpflichten gelten seit August 2026. Wer heute einen Chatbot ohne Kennzeichnung betreibt, ist in der Pflicht, auch wenn Anhang III noch Zeit hat.

## Rollen

Die Pflichten hängen an der Rolle. **Anbieter** entwickeln ein System oder bringen es unter eigenem Namen in Verkehr; **Betreiber** setzen es unter eigener Verantwortung ein. Ein Betreiber wird nach Art. 25 zum Anbieter, wenn er seinen Namen auf ein Hochrisikosystem setzt, es wesentlich ändert, seine Zweckbestimmung ändert oder ein nicht als Hochrisiko bestimmtes System für einen Hochrisikozweck einsetzt.

Der letzte Fall ist der unbemerkte: Niemand schließt dabei einen Vertrag, niemand ändert Software. Es genügt, ein allgemeines Werkzeug in einem Anhang-III-Bereich einzusetzen.

## Was eine Einstufung festhalten muss

Ergebnis, Begründung mit Artikelbezug, **Annahmen**, offene Punkte mit Namen und Termin, Folgepflichten, Auslöser für eine Neueinstufung, und die entscheidende Person mit Datum.

Das Feld **Annahmen** wird am häufigsten weggelassen und ist am wertvollsten. Es unterscheidet eine erklärbare Einstufung von einer Behauptung. Ebenso gehören **rechtliche Klasse** und **interne Risikoeinschätzung** in getrennte Felder: Ein System kann rechtlich minimal und betrieblich riskant sein.

## Warum Einstufungen veralten

Sechs Auslöser: geänderte Zweckbestimmung, Modellwechsel beim Anbieter, neue Datenquelle oder Datenart, erweiterter Nutzerkreis, Wegfall der menschlichen Aufsicht, Rechtsänderung.

Der unauffälligste ist der **stille Modellwechsel**: Der Anbieter tauscht das Modell, die Schnittstelle bleibt identisch, das Verhalten nicht. Drei Wege, es zu bemerken — Versionsangabe in der Antwort, abonnierter Änderungsverlauf, und ein fester Testsatz von etwa zwanzig Eingaben mit erwarteten Ausgaben, der monatlich durchläuft. Der Testsatz ist der einzige, der ohne Mitwirkung des Anbieters funktioniert.

Eine neue Einstufung ersetzt die alte nicht. In einer Prüfung lautet die Frage nicht, wie ein System heute eingestuft ist, sondern wie es eingestuft war, als ein bestimmter Vorfall passierte.

## Häufige Fehler

- Das Werkzeug eingestuft statt den Einsatzzweck
- Anhang III geprüft, Art. 5 übersprungen
- Art. 6 Abs. 3 als Freibrief gelesen, ohne die Bewertung zu dokumentieren und ohne die Profiling-Rückausnahme zu prüfen
- Die Marketingaussage des Anbieters als Einstufungsnachweis verwendet
- Rechtliche Klasse und interne Risikoeinschätzung vermengt
- „Es entscheidet ja ein Mensch" als Aufsicht gezählt, wo niemand widersprechen kann
- Einstufung einmal gemacht und nie wieder angesehen
- GPAI-Pflichten mit der Risikoklasse des eigenen Systems verwechselt

Jeder mit Gegenprobe in [common-classification-errors.md](./knowledge-base/eu-ai-act/common-classification-errors.md).

## Weg durch das Repository

1. [Überblick](./knowledge-base/eu-ai-act/overview.md) — Aufbau und Fristen
2. [Begriffe](./knowledge-base/eu-ai-act/definitions.md) — die Anker der Einstufung
3. [Rollen](./knowledge-base/eu-ai-act/scope-and-actors.md) — Anbieter oder Betreiber
4. [Einstufungslogik](./knowledge-base/eu-ai-act/risk-logic.md) — die fünf Schritte im Detail
5. [Häufige Fehler](./knowledge-base/eu-ai-act/common-classification-errors.md)
6. [Prüfliste](./checklist.md) anwenden
7. [Vorlage](./templates/risk-classification-template.md) ausfüllen
8. [Auslöser](./templates/reclassification-trigger-checklist.md) zur Wiedervorlage setzen

---

Keine Rechtsberatung. Stand: Oktober 2026.
