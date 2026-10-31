# ETS/ATS-Overlay · aktueller Stand

Stand: **31.10.2026**. Projekt-/Oberflächenname: **NeverGate Virtual Control**.

| Bereich | Nachweis / Stand |
|---|---|
| GitHub | Öffentliches Repository mit Planung und Projektbeschreibung; aktueller Programmquellstand/Installer noch nachzuführen |
| Versuchsfassung | 0.2.0 aus begleitetem Nutzerbericht; anfangs nicht sichtbar, später sichtbar |
| Bedien-/Spielansicht | Bei eingeschalteten Funktionen verdeckte das Overlay zu viel Spielsicht; große Symbole und drei Zeilen abgelehnt |
| Öffentlicher Release | Noch kein GitHub-Release vorhanden |
| Spielprüfung | Keine vollständige getrennte ETS2-/ATS-Abnahme mit exakten Build-/Telemetrieversionen im Repository |

## Verbindliche nächste Gestaltung

Fahrzeugdaten in einer kompakten Zeile, Auftragsdaten in einer dünnen Zeile darunter. Kleine Symbole möglichst in einer Reihe; einzeiliger Fortschritt mit Prozentzahl und weiß/grünem Balken. Beleuchtung, Blinker/Warnblinker, Parkbremse, Retarder, Drehzahl und Lkw-Daten sowie Session/Auftrag/Ortung gezielt auswählbar. Keine dauerhafte große dreizeilige Überlagerung.

Bedienoberfläche mit linker Navigation bis unten, Overlay-Unterpunkten, Versionsangaben unten links und NeverGate-Virtual-Control-Kennung. Zehn vorhandene Themes bereits im Installer auswählbar. Diese Anforderungen sind kein Implementierungsnachweis.

## Noch technisch nachzuweisen

- Aktuelle Quellen, Windows-Installer und Telemetrie mit Version, Dateigröße und Prüfsumme.
- Erkennung der Standard-Spielpfade, automatische Plugin-Einrichtung sowie Verhalten bei abweichenden Pfaden/bestehendem Plugin.
- Automatischer Start im Zusammenhang mit dem Spiel, Gesamtschalter und dauerhaft gespeicherte Anzeigeauswahl.
- Beide Spiele einzeln: frische Telemetrie, Pause/Spielende/Neustart, kein Anzeigen alter Daten als aktuelle Messwerte.
- Randloser Fensterbetrieb und Mehrmonitorpositionierung; kompakte Ansicht mit allen gewünschten Funktionen.

[Planung](PLANUNG.md). Nutzerrückmeldung zur sichtbaren Versuchsfassung, technischer Buildnachweis und vollständige Spielabnahme bleiben getrennt. Die Dokumentationspflege vom 31.10. führt keinen neuen Build oder Spieltest aus und veröffentlicht keinen Installer.
