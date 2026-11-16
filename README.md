# Änderungsprozess-Demo

Interaktive Demo: Ein Änderungswunsch im Anlagenbau läuft durch fünf Schritte (erfassen, Betroffene finden, bewerten, freigeben, Unterlagen anpassen). Am Ende zeigt sie, wo die Zeit hängt, wo KI oder Automatisierung helfen könnte und wie eine Einführung aussehen würde.

**Demo öffnen:** https://rroessger.github.io/aenderungsprozess-demo/

Erstellt im November 2026 von René Rößger für eine Bewerbung als Prozessmanager Digitalisierung und Automatisierung. Dauer eines Durchlaufs: etwa 5 bis 10 Minuten.

## Was die Demo zeigt

- **Prozessanalyse mit Lean-Sicht:** Je Schritt werden Bearbeitungszeit und Wartezeit getrennt erfasst, dazu die acht Verschwendungsarten. Das Ergebnis zeigt Durchlaufzeit, Anteil Wartezeit und Flussgrad.
- **Use-Case-Bewertung:** Für den Schritt mit der längsten Wartezeit wird ein KI- oder Automatisierungsansatz nach Nutzen, Machbarkeit und Risiko bewertet. Die Bewertungsregel steht offen auf der Seite.
- **Einführung:** Problem klären, Pilot mit Prüfkriterien, Rollout in Stufen, Mitarbeitende befähigen, Controlling.

## Was simuliert ist

- Die Fälle und alle vorbelegten Zeiten sind erfunden. Sie beschreiben keine internen Abläufe eines bestimmten Unternehmens.
- Die "KI-Schritte" sind feste Schlagwortregeln. Es ist kein Sprachmodell eingebaut. Jede Regel wird im Durchlauf angezeigt, und jeder Vorschlag lässt sich ändern.
- Die Zahlen im Ergebnis stammen aus den Eingaben im Durchlauf. Sie zeigen die Methode, keine gemessene Wirkung.

## Datenschutz und Technik

- Eine einzelne Datei `index.html` mit HTML, CSS und JavaScript. Keine externen Bibliotheken, Schriften oder Tracker, keine Cookies, kein Server.
- Eingaben bleiben im Browserfenster und sind nach dem Schließen weg.
- Die Datei funktioniert auch lokal ohne Internet: herunterladen und im Browser öffnen.
- Inhalte und Regeln stehen als Datenobjekte am Anfang des Skripts (`STEPS`, `CASES`, `CAT_RULES`, `AREA_RULES` usw.) und lassen sich dort anpassen.

## Was eine echte Lösung bräuchte

Zugriff auf ERP und PDM mit Rechteprüfung, eine Datenschutzprüfung, eine Einordnung nach EU-KI-Verordnung, die Einbindung von IT-Sicherheit und Betriebsrat und einen Pilot mit Messung des Ist-Zustands.

## Entstehung

Mit Claude Code gebaut (Agentic Coding). Geprüft durch vollständige Durchläufe aller Fälle und eines freien Themas auf Handy- und Desktopbreite.

## Lizenz

MIT, siehe [LICENSE](LICENSE).
