# ETS/ATS-Overlay · aktueller Stand

Dokumentation geprüft am **01.11.2026**. Projektbezeichnung: **NeverGate Virtual Control**; die gemeldete Oberfläche 0.3.3 verwendet „NeverGate Virtuell Control“.

## Nachgetragene Entwicklungsberichte

| Datum | Version | Gemeldeter Inhalt | Prüfgrenze |
| --- | --- | --- | --- |
| 23.10.2026 | 0.2.0 | Fahrzeugleiste; Nutzer meldete nach anfänglicher Verzögerung sichtbares Overlay | Zu große Darstellung beanstandet |
| 23.10.2026 | 0.3.0 | Dünne Auftragszeile: Fracht, Gewicht, Start, Ziel, Reststrecke, Fahrzeit; Angaben einzeln schaltbar | Datenprüfungen/Installerprüfung gemeldet; echter Spieltest offen |
| 23.10.2026 | 0.3.1 | Kompaktere Schrift, Buttons und Zeilen; verbessertes Verhalten beim Vergrößern | Layout-/Installerprüfung gemeldet; Windows-Test offen |
| 24.10.2026 | 0.3.2 | Seitenleiste bis unten, Spielkennung und Version unten links | Layout-/Installerprüfung gemeldet; Windows-Test offen |
| 24.10.2026 | 0.3.3 | Aufklappbarer Overlay-Bereich mit Unterseiten und NG-Kennung | Menü-/Installerprüfung gemeldet; Windows-Test offen |

Diese Tabelle gibt frisch gelesene Entwicklungsberichte wieder. Die Dateien und die damaligen Prüfsummen wurden bei dieser Dokumentationspflege nicht erneut technisch geprüft. Die Sichtprüfung einer früheren Fassung ist keine Gesamtabnahme späterer Fassungen.

## Offene Abnahme

- Tatsächlich installierte Version eindeutig feststellen und gegen den Testbuild abgleichen.
- Plugin-Version und Bedarf einer Installation/Aktualisierung verständlich anzeigen.
- Kompakte Fahrzeugdarstellung plus dünne Auftragszeile bei vielen aktiven Angaben im Spiel prüfen.
- Beide Spiele einzeln: aktueller Auftrag, frische Telemetrie, Pause, Spielende und Neustart.
- Verzögerte Anzeige nach Einschalten prüfen.
- Automatischer Programmstart beim Spielstart auch nach vollständig beendetem Programm: ausdrücklich gewünscht, im gelesenen Bericht noch nicht vollständig umgesetzt.
- Gesamtschalter und Auswahl nach Neustart erhalten; Standard- und abweichende Spielpfade, vorhandenes Plugin, randloser Betrieb und mehrere Monitore testen.
- Zehn Themes einschließlich Einrichtung getrennt nachweisen.

## Veröffentlichung

Das Repository enthält Dokumentation, keinen aktuellen Programmquellstand und keinen Installer. Die GitHub-Release-Liste war bei der Prüfung leer. Es wurde hier weder ein Build erstellt noch ein Spieltest ausgeführt oder ein Download veröffentlicht.

[Planung](PLANUNG.md) · [Änderungsübersicht](CHANGELOG.md)
