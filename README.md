# URBAN LEGENDS · Palm Coast · Alpha 0.3

Ein eigenständiges 3D-Browserspiel auf Basis der Alpha 0.2 von Grizzlys-club/urban-legends.

## Spielen

[GitHub Pages](https://grizzlys-club.github.io/urban-legends/)

Für die lokale Vorschau im Projektordner `python3 -m http.server 8765` starten und [localhost öffnen](http://127.0.0.1:8765/). Die 3D-Engine Three.js 0.160.1 liegt mit ihrer MIT-Lizenz bei. Ein Browser mit WebGL ist erforderlich.

- **Laptop** · WASD oder Pfeiltasten für Bewegung und Fahrzeuge, F für Ein- und Ausstieg, C für die Kamera, Maus ziehen zum Umschauen zu Fuss. Umschalt sprintet. Leertaste springt oder bremst. P öffnet das Spielmenü.
- **Handy** · Richtungstasten und Aktionen am unteren Rand. Zum Umschauen zu Fuss über die Szene wischen.
- **Aufträge** · Goldene Markierungen zeigen sechs Ziele einer Auftragskette. Das HUD zeigt an, ob du laufen oder fahren musst. Nach der Lieferung am Pier folgen drei Kontrollpunkte und der Abschluss am Café.
- **Spielstand** · Der Browser speichert Position, Geld und neue Aufträge. Beim Wechsel von Alpha 0.2 bleiben Geld und Position erhalten. Die neue Auftragskette beginnt bei Schritt eins.

## Umsetzung und Grenzen

Die Küste hat einen Pier, eine Promenade und drei markierte Gebäude. Fahrzeuge und Fussgänger folgen einfachen Routen. Verkehr reagiert auf belegte Fahrspuren mit Anhalten. Fahrphysik und Kollisionen sind vereinfacht. Gebäude sind Kulissen. Das Spiel bietet frei umschaltbares Wetter und Tag/Nacht. Schatten sind bei kleinen Bildschirmen und Touch-Geräten standardmässig aus. Die häufig wiederholten Gebäude und Strassenobjekte werden nach Material gemeinsam gezeichnet. Für konkrete Handy-Modelle liegen keine FPS-Messungen vor.

## Rockstar-Recherche · Stand 26. November 2026

| Thema | Durch Rockstar bestätigt |
| --- | --- |
| Veröffentlichung | Rockstar meldet den weltweiten Start am 19. November 2026 für PS5 und Xbox Series X/S. Die Vorbestell-Ankündigung beschreibt das Spiel als Einzelspieler-Erlebnis. [Startmeldung](https://www.rockstargames.com/newswire/article/39akk424a9oo53/grand-theft-auto-vi-now-available) · [Vorbestell-Ankündigung](https://www.rockstargames.com/newswire/article/5171972o3ak5oa/pre-order-grand-theft-auto-vi-on-june-25) |
| Handlung und Orte | Jason und Lucia geraten nach einem misslungenen Coup in eine Verschwörung in Leonida. Rockstar stellt Vice City und die Umgebung in offiziellen Ortsprofilen vor und stellt eine Karte von Leonida bereit. [Offizielle Spielseite](https://www.rockstargames.com/VI) |
| Gezeigte Szenen | Rockstar bezeichnet das Material in *An Extended Look* als vollständig aus dem Spiel auf PS5 aufgenommen. Das belegt die Herkunft der Szenen. Aus Einzelbildern lassen sich weder dauerhaft spielbare Aktionen noch die genauen Regeln für Verkehr und Nebenfiguren ableiten. [An Extended Look](https://www.rockstargames.com/VI/an-extended-look) |
| Leistung und PS5-Funktionen | Rockstar nennt 30 FPS als Ziel für beide Konsolen. Für PS5 beschreibt Rockstar DualSense-Haptik und Tempest-3D-Audio. [Preload und Plattformdetails](https://www.rockstargames.com/newswire/article/89834o94713o21/pre-load-grand-theft-auto-vi-now) |
| Musik und Audio | Rockstar bestätigt In-Game-Radio, Podcasts auf Abruf sowie Kopfhörer für Radio und Podcasts zu Fuss. Justice komponierten den adaptiven Score für die Geschichte. [Radio und Podcasts](https://www.rockstargames.com/newswire/article/o3982oa93a23k4/the-music-of-grand-theft-auto-vi-in-game-radio-stations) · [Original Score](https://www.rockstargames.com/newswire/article/39ak8a12395591/grand-theft-auto-vi-original-score-by-justice) |

Die ausgewerteten Rockstar-Quellen belegen keinen PC-Starttermin, keinen konkreten Online-Zeitplan, keinen 60-FPS-Modus, keinen Prozentsatz begehbarer Gebäude und keine vollständige Simulation individueller Tagesabläufe für alle NPCs. Das sind offene Punkte für diese Recherche. Palm Coast verwendet eigene Orte, Figuren, Aufträge und prozedural erzeugte 3D-Modelle.

## GitHub Pages

Die öffentliche URL lieferte bei der Prüfung vor dem Update bereits HTTP 200 und zeigte Alpha 0.2. Der frühere 404 war zu diesem Zeitpunkt nicht mehr reproduzierbar. Die Dateien liegen für das bestehende Projekt-Hosting im Wurzelordner von `main`. `.nojekyll` stellt die Dateien statisch bereit. [GitHub-Dokumentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
