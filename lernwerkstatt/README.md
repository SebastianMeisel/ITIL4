# IT-Service-Werkstatt: interaktive ITIL-4-Lernroute

Eine unabhängige, deutschsprachige Web-Lernanwendung, die sich an der **Service Value Chain** orientiert und von angeleiteten Entscheidungen zu eigenständigen Arbeitsaufträgen führt.

## Einstieg

Im Repository-Verzeichnis:
```bash
cd lernwerkstatt
python3 -m http.server 8000
```
Öffnen: http://localhost:8000

Alternativ `index.html` direkt im Browser öffnen. Die Anwendung benötigt weder externe Fonts noch fremde Skripte oder einen Server für den Lernfortschritt.

## Lernpfad und Berufsszenarien

Die sechs **Aktivitäten** – Plan, Engage, Design & Transition, Obtain/Build, Deliver & Support, Improve – sind als frei betretbare Bereiche einer interaktiven Service-Value-Chain-Karte dargestellt. **Es gibt keine Pflichtreihenfolge und keine Pflicht, alle Bereiche zu besuchen.** Jede Aktivität kann wiederholt werden, wenn neue Informationen, Rückfragen oder Fehler auftauchen. Die vorgeschlagene nächste Aktivität ist nur eine Empfehlung. Unterschiedliche Szenarien starten an unterschiedlichen Stellen (WLAN: Deliver & Support; Terminbuchung/Datenqualität: Engage; Beschaffung: Plan).

Vier durchgehende, aus der Berufspraxis abgeleitete Szenarien:

1. **Fachinformatiker:in für Systemintegration:** instabiles Schul-WLAN, Incident Management, Monitoring, Changes, Assets und Continual Improvement.
2. **Fachinformatiker:in für Anwendungsentwicklung:** doppelte Terminbuchungen, Anforderungsanalyse, Tests, Softwareentwicklung, Deployment und Qualitätsmessung.
3. **Fachinformatiker:in für Daten- und Prozessanalyse:** fehlerhafte Auftragsdaten, Datenqualität, Business Analysis, Service Design und Monitoring.
4. **Kaufmann/-frau für Digitalisierungsmanagement:** digitaler Beschaffungsprozess, Business Case, Stakeholder, Supplier Management, Service Requests und Prozessverbesserung.

Für jeden der vier Fälle gibt es sechs **frei zugängliche Aktivitätsräume** mit berufstypischen Entscheidungen, begründetem Feedback, offenen Transferaufgaben und Notizen. Jedes Szenario hat exemplarische verantwortliche und beteiligte **Organisationseinheiten**. Eine Practice ist *nicht* gleichbedeutend mit einer Abteilung. Lernende verfolgen ihren individuell gewählten Weg und dokumentieren Übergaben zwischen Einheiten sowie erneute Besuche. Nicht besuchte Aktivitäten gelten nicht automatisch als Fehler. Practices können über Schaltflächen im Glossar nachgeschlagen werden. Die Kennzahlen in den Szenarien sind ausdrücklich fiktiv. Entscheidungen werden in einem **chronologischen Verlauf** protokolliert; ein erneuter Besuch kann weitere Entscheidungen ergänzen. Ein didaktischer Reflexionswert ist ausdrücklich **kein realer Servicezustand und kein offizieller Lernerfolg**.

Die vier Dimensionen, Output/Outcome, Kundenwert, Servicebeziehungen und Risikobewusstsein werden begleitend sichtbar gehalten. Auswertung und Textexport ergeben ein persönliches Entscheidungspapier.

## Originalmaterialien

Die vom Repository-Inhaber selbst erstellte Grafik `ITIL_Überblick_simple.png` ist als **optionale** Referenz in der Oberfläche eingebettet. Die interaktive Value-Chain-Grafik ist neu als HTML/CSS gestaltet. Die Inhalte sind unabhängig formuliert; keine offiziellen PeopleCert-Fragen oder Originaltexte.

## Datenschutz und Barrierearmut

Keine Tracker, CDN-Schriften oder externen Skripte. `localStorage` speichert die eigenen Antworten ausschließlich im aktuellen Browser. Zurücksetzen und Export sind verfügbar. Fokus- und Tastaturbedienung, kontrastreiche Layouts, Dark Mode und mobile Darstellung wurden implementiert. Eine formale WCAG-Prüfung steht aus.

## Überprüfung vor Unterrichtseinsatz

- Alle 4 Szenarien und je 6 Bereiche in **beliebiger Reihenfolge** betreten; einige Bereiche absichtlich auslassen.
- Dieselbe Aktivität mehrfach besuchen und entscheiden, dabei Verlauf, Teams, Übergaben und Reflexionswert prüfen.
- Notizen und Checkboxen nach einem Reload prüfen.
- Text exportieren und Dateiinhalte prüfen.
- Originalübersicht einblenden und Darstellung prüfen.
- Mit Tastatur, Screenreader, engem Viewport sowie hellem und dunklem Farbschema testen.

Hinweise zu den Rechten siehe [RECHTE.md](RECHTE.md). Keine offizielle Zertifizierungsvorbereitung.

## Didaktisches Leitbild: Ein Raum, kein Fließband

Das Service Value System liefert einen Rahmen, keine starr nummerierten Zuständigkeiten. Die Service Value Chain ist ein flexibles, vernetztes Aktivitätsmodell. Manche Wertströme beginnen bei einem Incident direkt mit Deliver & Support, andere mit Engage oder Plan. Aktivitäten können ausgelassen, parallel bearbeitet, wiederholt oder von unterschiedlichen Organisationseinheiten gemeinsam gestaltet werden. Die exemplarischen Teams sind **keine von ITIL vorgeschriebene Organisationsstruktur**; Verantwortlichkeiten sind nach Projekt und Unternehmen unterschiedlich. Bei einer Übergabe müssen Beobachtungen, Anforderungen und Entscheidungen weitergegeben werden.
