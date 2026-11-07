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

Sechs **Aktivitäten** – Plan, Engage, Design & Transition, Obtain/Build, Deliver & Support, Improve – werden als interaktive Karte dargestellt. Diese Abfolge ist nur der didaktische Lernpfad, **keine** feste Reihenfolge oder Prozessdefinition der ITIL 4 Service Value Chain.

Vier durchgehende, aus der Berufspraxis abgeleitete Szenarien:

1. **Fachinformatiker:in für Systemintegration:** instabiles Schul-WLAN, Incident Management, Monitoring, Changes, Assets und Continual Improvement.
2. **Fachinformatiker:in für Anwendungsentwicklung:** doppelte Terminbuchungen, Anforderungsanalyse, Tests, Softwareentwicklung, Deployment und Qualitätsmessung.
3. **Fachinformatiker:in für Daten- und Prozessanalyse:** fehlerhafte Auftragsdaten, Datenqualität, Business Analysis, Service Design und Monitoring.
4. **Kaufmann/-frau für Digitalisierungsmanagement:** digitaler Beschaffungsprozess, Business Case, Stakeholder, Supplier Management, Service Requests und Prozessverbesserung.

Für jede der 24 Stationen: Einordnung in die Value Chain, passende Practices, echte berufstypische Entscheidung mit begründetem Feedback, offene Transferaufgabe, lokale Notizen und Selbsteinschätzung. Practices können über Schaltflächen im Glossar nachgeschlagen werden. Die Kennzahlen in den Szenarien sind ausdrücklich fiktiv. Eine Entscheidung wirkt sich auf einen *didaktischen Entscheidungswert* aus, nicht auf einen simulierten realen Servicezustand.

Die vier Dimensionen, Output/Outcome, Kundenwert, Servicebeziehungen und Risikobewusstsein werden begleitend sichtbar gehalten. Auswertung und Textexport ergeben ein persönliches Entscheidungspapier.

## Originalmaterialien

Die vom Repository-Inhaber selbst erstellte Grafik `ITIL_Überblick_simple.png` ist als **optionale** Referenz in der Oberfläche eingebettet. Die interaktive Value-Chain-Grafik ist neu als HTML/CSS gestaltet. Die Inhalte sind unabhängig formuliert; keine offiziellen PeopleCert-Fragen oder Originaltexte.

## Datenschutz und Barrierearmut

Keine Tracker, CDN-Schriften oder externen Skripte. `localStorage` speichert die eigenen Antworten ausschließlich im aktuellen Browser. Zurücksetzen und Export sind verfügbar. Fokus- und Tastaturbedienung, kontrastreiche Layouts, Dark Mode und mobile Darstellung wurden implementiert. Eine formale WCAG-Prüfung steht aus.

## Überprüfung vor Unterrichtseinsatz

- Alle 4 Szenarien und je 6 Stationen navigieren.
- Entscheidungen treffen, Feedback und Lernstand beobachten.
- Notizen und Checkboxen nach einem Reload prüfen.
- Text exportieren und Dateiinhalte prüfen.
- Originalübersicht einblenden und Darstellung prüfen.
- Mit Tastatur, Screenreader, engem Viewport sowie hellem und dunklem Farbschema testen.

Hinweise zu den Rechten siehe [RECHTE.md](RECHTE.md). Keine offizielle Zertifizierungsvorbereitung.
