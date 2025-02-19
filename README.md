# Raketenspiel

## Beschreibung
Ein einfaches Raketenspiel mit HTML, JavaScript und der PixiJS-Bibliothek. Der Spieler steuert eine Rakete, die sich nach links und rechts bewegen kann. Es erscheinen UFOs, die nach unten fliegen, und der Spieler kann Schüsse abfeuern, um diese zu zerstören. Falls ein UFO die Rakete trifft, endet das Spiel.

## Voraussetzungen
- Ein Webbrowser (Chrome, Firefox, Edge, etc.)
- Ein lokaler Webserver (z. B. Live Server für VS Code) oder direkter Zugriff auf die HTML-Datei im Browser
- Internetverbindung zum Laden der PixiJS-Bibliothek oder eine lokale Kopie von PixiJS

## Technologien
- **HTML**: Struktur der Webseite
- **JavaScript**: Spiel-Logik
- **PixiJS**: 2D-Rendering

## Installation & Ausführung
1. Stelle sicher, dass du eine Umgebung hast, die statische HTML-Dateien ausführen kann (z. B. direkt im Browser oder mit einem lokalen Server).
2. Lade die Dateien in ein gemeinsames Verzeichnis:
   - `index.html`
   - `gameloop.js`
   - `app.js`
   - Assets-Bilder (`rocket.png`, `ufo1.png`, `ufo2.png`, `bullet.png`)
3. Öffne `index.html` in einem Browser.

## Spielsteuerung
- **Pfeiltaste Links (←)**: Bewegt die Rakete nach links.
- **Pfeiltaste Rechts (→)**: Bewegt die Rakete nach rechts.
- **Leertaste**: Schießt ein Projektil nach oben.

## Spielmechanik
- UFOs erscheinen zufällig am oberen Bildschirmrand und bewegen sich nach unten.
- Wird ein UFO von einem Projektil getroffen, verschwindet es.
- Falls ein UFO die Rakete berührt, endet das Spiel.

## Abhängigkeiten
- PixiJS wird über ein CDN geladen:
  ```html
  <script src="https://cdn.jsdelivr.net/npm/pixi.js@7.x/dist/pixi.min.js"></script>
  ```

## Erweiterungsmöglichkeiten
- Punkteanzeige für zerstörte UFOs
- Verschiedene Schwierigkeitsstufen
- Animationen und Soundeffekte

Viel Spaß beim Spielen! 🚀

