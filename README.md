# ⛳ Fairway 3D

Ein 3D-Golfspiel für den Browser, gebaut mit [Three.js](https://threejs.org/), alles in einer einzigen `index.html`.

## Spielen

`index.html` im Browser öffnen, fertig. Es braucht keinen Build-Schritt. Three.js wird von cdnjs geladen, du brauchst also eine Internetverbindung.

Für GitHub Pages: in den Repo-Einstellungen *Pages → Deploy from branch* auswählen, dann ist das Spiel unter `https://<user>.github.io/golf-game/` erreichbar.

## Steuerung

| Taste | Aktion |
|---|---|
| `←` `→` / `A` `D` / Maus ziehen | Zielen (`Shift` = fein) |
| `Q` `E` / `1`–`5` | Schläger wechseln |
| `Leertaste` halten / loslassen | Kraftbalken pendelt / Schlag |
| `C` | Übersicht ein/aus |
| `R` | Ziel zurücksetzen |

Auf Touch-Geräten gibt es eigene Buttons.

## Features

- 9 Löcher (Par 35): Doglegs, ein Inselgrün, Wasserhindernisse, Bunker, Hügel und Bäume
- Ballphysik mit Luftwiderstand, Backspin-Auftrieb, Wind, Abprallen und Rollen am Hang
- Je nach Lage verhält sich der Ball anders: Fairway, Rough, Bunker, Grün
- 5 Schläger (Driver, Holz 3, Eisen 5, Wedge, Putter), der passende wird automatisch vorgewählt
- Flugbahn-Vorschau, Strafschläge bei Wasser und Aus, Scorekarte
- Synthetische Soundeffekte über WebAudio
