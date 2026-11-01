# NeverGate Virtual Control · fortgeschriebene Planung

Stand: **01.11.2026**. [Aktueller Nachweisstand](STATUS.md).

## Nachgetragene Entwicklung bis 0.3.3

Die Entwicklungsberichte vom 23./24.10. melden inzwischen eine Auftragszeile (0.3.0), kompaktere Bedienoberfläche (0.3.1), durchgehende linke Seitenleiste (0.3.2) und ein Overlay-Untermenü mit NG-Kennung (0.3.3). Layout-/Installerprüfungen wurden gemeldet; echte Windows-/Spieltests bleiben offen. Details: [Status](STATUS.md) und [Änderungsübersicht](CHANGELOG.md).

Die folgenden Anforderungen sind daher teils als umgesetzt gemeldet, aber nicht vollständig abgenommen. Die historische Planung unten bleibt als damaliger Ausgangspunkt erhalten.

## Priorität nach dem Versuch

Die gemeldete Versuchsfassung 0.2.0 war schließlich sichtbar, beanspruchte mit allen Funktionen aber zu viel Platz. Die weitere Abstimmung sah kompakte Fahrzeugzeilen plus eine dünne Auftragszeile vor; die Auftragszeile wurde anschließend für 0.3.0 als umgesetzt gemeldet. Entscheidend bleibt eine kleine, geordnete Darstellung statt großer überdeckender Kästen. Das Ziel ist eine eigene geordnete Oberfläche mit eigener Gestaltung.

## Festgehaltener Umfang

- ETS2 und ATS, randloser Fensterbetrieb, mehrere Monitore.
- Fahrzeugzustand: Licht, Blinker/Warnblinker, Parkbremse, Retarder, Drehzahl und Lkw-Infos.
- Session/Server, Auftrag und Ortung mit gezielter Auswahl; dekorative Leiste optional.
- Windows-Oberfläche NeverGate Virtual Control, linke Navigation bis unten, Overlay-Unterpunkte und Spielversionen unten links.
- Erkennung üblicher Spielpfade, Telemetrie mitinstallieren, Spielstart/Overlay-Autostart und zentraler Ein-/Ausschalter.
- Bestehende Installation aktualisieren können, feste nachvollziehbare Pfade; zehn vorhandene Themes bereits bei Einrichtung.

## Offene Abnahme

- [ ] Source-/Installer-/Telemetrieversionen und Prüfsummen nachführen.
- [ ] Kompaktes Overlay und vollständige Anzeigeauswahl auf Windows praktisch prüfen.
- [ ] ETS2 und ATS einzeln mit randlosem Fensterbetrieb und mehreren Monitoren abnehmen.
- [ ] Plugininstallation, automatischer Start, Gesamtschalter, Themeauswahl und erhaltene Einstellungen nach Neustart prüfen.
- [ ] Veraltete Messwerte/fehlendes Spiel/abweichende Pfade verständlich behandeln.

Virtuelle Spedition bleibt spätere Erweiterung. Kein neuer Implementierungs- oder Releaseabschluss durch diese Dokumentation.

<details><summary>Ursprüngliche Planung vom 23.10.2026</summary>

Die damalige Aussage „nur Planung, kein sichtbarer Versuch belegt“ wird durch den neueren Nutzerbericht ergänzt; fehlende technische Buildnachweise bleiben offen.

# NeverGate ETS-/ATS-Overlay · Planung
Stand: 23.10.2026. Quelle: Eigentümerplanung vom 23.10.2026 und ausdrücklicher Auftrag zur Dokumentation auf GitHub und Discord.

## Ziel und aktueller Stand
Eigenständiges NeverGate-Overlay für Euro Truck Simulator 2 und American Truck Simulator. Gewünscht ist eine übersichtliche Windows-Bedienoberfläche mit einem ähnlich vertrauten Bedienkonzept wie Trucky; eigener Code und eigene Gestaltung. Keine Übernahme fremder Anwendung oder Assets.

Das öffentliche Repository ist angelegt. Zum Dokumentationsbeginn war ausschließlich eine README vorhanden. Ein funktionierendes Overlay, Telemetrie-Plugin, Windows-Installer oder geprüfter Build ist hier noch nicht nachgewiesen. Die erste installierbare Versuchsfassung wurde im Planungsgespräch freigegeben; diese Dokumentation ist kein Buildnachweis.

## Vereinbarter erster Umfang
| Bereich | Anforderung |
|---|---|
| Spiele | ETS2 und ATS unterstützen; gestartetes Spiel automatisch erkennen. |
| Telemetrie | Eigenes Telemetrie-Plugin für die Anbindung der Spieldaten entwickeln; technische SDK-/Versionsdetails vor Implementierung prüfen. |
| Installation | Spiele möglichst automatisch in ihren Standardverzeichnissen erkennen und das passende Telemetrie-Plugin dort installieren. |
| Automatischer Betrieb | Telemetrie soll mit dem Start des jeweiligen Spiels verfügbar werden. Technischer Ablauf und tatsächlicher Spielstart müssen geprüft werden. |
| Windows-Oberfläche | Installierbares Windows-Programm mit zentralen Overlay-Einstellungen. Einstellungen sollen beim Einrichten und anschließend im installierten Programm erreichbar sein. |
| Gesamtschalter | Das komplette Overlay ausdrücklich ein- und ausschalten können; zentrale Pflichtfunktion. |
| Anzeigeauswahl | Nutzer wählen, welche Overlay-Funktionen und Informationen sichtbar sein sollen. Konkrete Widgets/Datenfelder werden noch festgelegt. |
| Themes | Von Anfang an dieselben zehn Themes wie im NeverGate-Browser anbieten; Auswahl bereits während der Einrichtung und anschließend im Programm. Namen und Farbwerte aus der vorhandenen Quelle übernehmen, keine Ersatz-Themes erfinden. |
| Priorität | Zuerst ein zuverlässig funktionierendes Overlay als installierbare Versuchsfassung. |
| Spätere Erweiterung | Virtuelle Speditionsgründung gehört nicht zum ersten Umfang; kann später separat geplant werden. |

## Vorgesehene Arbeitsschritte
- [ ] Aktuelle vorhandene Quellen, Browser-Themes und technische Voraussetzungen prüfen.
- [ ] Windows-Grundprogramm, Speicherung der Einstellungen und Gesamtschalter bauen.
- [ ] Telemetrie-Plugin und Spielzustandserkennung für beide Spiele implementieren.
- [ ] Overlay und auswählbare Anzeigen anbinden.
- [ ] Alle zehn bestehenden Themes übernehmen und auswählbar machen.
- [ ] Windows-Installer mit automatischer Spiele-/Plugin-Erkennung erstellen.
- [ ] Erste installierbare Versuchsfassung mit Prüfsummen und verständlicher Anleitung bereitstellen.
- [ ] Auf echtem Windows-System mit ETS2 und ATS prüfen und Eigentümerabnahme dokumentieren.

Diese Schritte sind Planung; keine davon wird hier als bereits implementiert gemeldet. Eine belastbare Zeitabschätzung setzt die technische Bestandsaufnahme voraus.

## Vor Implementierung zu klären
- Unterstützte Windows-/Spielversionen und gewähltes Telemetrie-SDK.
- Verbindliche Liste der ersten Anzeigen, Positionierung und Bedienung des Overlays.
- Quelle, Namen und Farbwerte der zehn Browser-Themes.
- Verhalten bei abweichendem Installationspfad, mehreren Spielinstallationen und bereits vorhandenem Telemetrie-Plugin.
- Tatsächlicher Overlay-Betrieb in den unterstützten Fenster-/Bildschirmmodi.

## Abnahme der ersten Versuchsfassung
- Installation und Start auf Windows; beide Spiele einzeln erkennen.
- Automatische Plugin-Einrichtung in gefundenen Standardpfaden; fehlende Spiele und andere Pfade verständlich behandeln.
- Telemetrie bei Spielstart, Pause, Spielende und erneutem Start korrekt behandeln; keine alten Daten als aktuelle Messwerte anzeigen.
- Gesamtes Overlay ein-/ausschalten, einzelne Anzeigen ändern und Einstellungen nach Programmneustart erhalten.
- Alle zehn vorhandenen Themes vollständig anzeigen und wechseln.
- Echtes Zusammenspiel von Installer, Windows-Programm, Telemetrie und Overlay je Spiel nachweisen; Simulation oder erfolgreicher Build allein ist keine Spielabnahme.

## Projektkommunikation
Gewünscht sind ein Discord-Projektforum, öffentliche Projektbeschreibung, eigener Projektbereich mit Infos/Austausch/Fehler-und-Ideen/GitHub-Updates sowie eine einzeln wählbare Projektrolle im bestehenden Stil. Zugang soll wie bei den vorhandenen Projekten an bestätigte Aufnahme und die jeweilige Projektwahl gebunden sein.

GitHub-Meldungen des neuen Projekts sollen sowohl im eigenen Projektkanal als auch im allgemeinen GitHub-Kanal erscheinen. Bestehende Zuordnungen anderer Projekte sollen dabei erhalten bleiben. Die Einrichtung und tatsächliche Zustellung werden getrennt von dieser Planung nachgewiesen.


</details>
