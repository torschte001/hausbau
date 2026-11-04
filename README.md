# Haus Oschatz – Sanierungswissen

Versionierte Wissensbasis für Planung, Geräte, Materialien, Einkäufe und Kosten der Haussanierung in Oschatz.

## Arbeitsregeln

- Diese Dateien sind der gemeinsame Projektstand. Neue Informationen werden hier eingetragen und im Chat besprochen.
- Fehlende Angaben bleiben leer oder erhalten den Status `offen`; Vermutungen werden nicht als Fakten gespeichert.
- Zeitabhängige Preise und Verfügbarkeiten tragen einen Recherchezeitpunkt und müssen vor dem Kauf erneut geprüft werden.
- Technische Herstellerwerte, besonders Schlagenergie, sind ohne gleiche Messmethode nicht direkt vergleichbar.
- Änderungen an Plänen und Entscheidungen werden in `projekt/entscheidungen.md` mit Datum und Status festgehalten.
- Käufe werden als einzelne Zeilen in `kosten/ausgaben.csv` erfasst. Budgetwerte stehen in `kosten/budget.md`.

## Struktur

- `projekt/`: Ausgangslage, Räume, Reihenfolge und Entscheidungen
- `geraete/`: vorhandene und geplante Werkzeuge
- `anhaenger/`: Maße, Gewichte und Ladungssicherung
- `material/`: Anforderungen und Produktoptionen nach Gewerk
- `einkauf/`: Händler- und Preisvergleiche
- `kosten/`: Budget und laufende Buchungen
- `daten/`: gemeinsame CSV-Dateien für wiederkehrende strukturierte Datensätze

## Pflege im Chat

Neue Daten können als Stichpunkte, Fotos, Typenschilder, Angebote oder Rechnungen eingebracht werden. Ich ordne sie ein, kennzeichne Unsicherheiten und aktualisiere die passenden Dateien. Für Änderungen genügt eine Nachricht wie „gekauft: …“ oder „Maß bestätigt: …“; Datum, Menge und Beleg können nachgereicht werden.

## Datenformate

Markdown eignet sich für Kontext, Entscheidungen und offene Fragen. CSV eignet sich für sortierbare Inventare und Ausgaben; Dateien verwenden UTF-8, Semikolon als Trennzeichen und Dezimalkomma. Geldbeträge werden in EUR geführt. Jede Angabe kann in `status` als `bestätigt`, `Arbeitsannahme`, `unsicher` oder `offen` markiert werden.
