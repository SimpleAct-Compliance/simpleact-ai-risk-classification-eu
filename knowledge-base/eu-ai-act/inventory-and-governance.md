# Einstufung, Inventar und Governance

Eine Einstufung, die nirgends hängt, ist eine Notiz. Zum Nachweis wird sie erst, wenn klar ist, woher sie kommt und was aus ihr folgt.

## Woher die Einträge kommen

Die Einstufung setzt voraus, dass das System überhaupt bekannt ist. Das ist die größere Hürde: Der kleinere Teil der KI im Unternehmen wurde als KI-Projekt beschafft.

| Quelle | Was sie findet |
|---|---|
| Beschaffung und Kreditorenliste | eingekaufte Werkzeuge, auch unangemeldete |
| Auslagenerstattung | Einzelabos, die an der Beschaffung vorbeigehen |
| Anmeldedienst (SSO) | was über die zentrale Anmeldung läuft |
| Netzprotokolle, aggregiert | Dienste ohne Vertrag und ohne Anmeldung |
| Release-Notes bestehender Software | nachträglich ergänzte KI-Funktionen |

Die letzte Zeile ist der häufigste Fall: Ein CRM bekommt eine Zusammenfassungsfunktion, und damit verarbeitet ein KI-System Kundendaten, ohne dass irgendwo ein Projekt dazu existiert.

Ausführlich im [KI-Inventar](https://github.com/SimpleAct-Compliance/simpleact-ai-system-inventory).

## Was aus der Einstufung folgt

| Ergebnis | Nächster Schritt |
|---|---|
| Verboten | Betrieb einstellen, Entscheidung dokumentieren, Alternativen prüfen |
| Hochrisiko | voller Pflichtenkatalog; technische Dokumentation nach Anhang IV |
| Transparenz (Art. 50) | Kennzeichnung und Hinweise umsetzen, Nachweis ablegen |
| Minimal | Eintrag im Inventar, KI-Kompetenz, Wiedervorlage |
| Nicht bewertet | Verantwortlichen und Termin eintragen — ein gültiges Zwischenergebnis |

Die letzte Zeile ist bewusst vorgesehen. Ein offener Punkt mit Namen und Datum ist in einer Prüfung besser als eine geratene Einstufung, die niemand belegen kann.

## Die Verbindungen, die ein Eintrag tragen muss

Eine Einstufung steht nie allein. In den Eintrag gehören Verweise auf:

- **Verarbeitungsverzeichnis** — verarbeitet das System personenbezogene Daten, braucht es dort einen eigenen Eintrag nach Art. 30 DSGVO
- **Folgenabschätzungen** — DSFA nach Art. 35 DSGVO und, bei Hochrisiko in bestimmten Konstellationen, die Grundrechte-Folgenabschätzung nach Art. 27 AI Act
- **Anbieterregister** — wer liefert das Modell, mit welchen Zusagen
- **Vorfallverfahren** — wohin eine Fehlfunktion gemeldet wird
- **Schulungsstand** — wer darf das System bedienen und beaufsichtigen

Fehlt eine dieser Verbindungen, fällt das nicht im Alltag auf, sondern in der Prüfung — und dann als Lücke in der Governance, nicht als vergessenes Feld.

## Wer entscheidet

Die Einstufung ist eine Bewertung, keine Erfassung. Sie braucht eine **namentlich benannte Person**, die sie verantwortet, und ein Datum. Fachbereich oder Compliance genügt nicht: In einer Prüfung wird gefragt, wer entschieden hat und auf welcher Grundlage.

## Verwandtes

- [Die Einstufungslogik](./risk-logic.md)
- [Wann neu eingestuft wird](./reclassification-logic.md)
