# ⛳ Putt Paradies

3D-Minigolf für den Browser, gebaut mit [Three.js](https://threejs.org/). Das ganze Spiel steckt in einer einzigen `index.html`.

## Spielen

`index.html` im Browser öffnen. Three.js und die Schriften kommen von einem CDN, du brauchst also Internet.

## Features

- **3 Strecken mit je 6 Löchern:** Sonnenwiese (leicht), Piratenbucht (mittel) und Lavakrater (schwer)
- **Hindernisse:** Windmühle, Rampen, Sprungschanzen, Schiebeplanken, Drehbalken, Pendel, Drehkreuz, eine Fähre und Beschleuniger
- **Wetter:** Sonnig, Bewölkt, Regen (die Bahn ist nass, der Ball rollt kürzer), Schnee (glatt, der Ball rollt weiter), Nebel und Sturm mit Blitzen
- **Wind** mit Richtung und Stärke, der den Ball ablenkt. Die Fahne weht mit.
- **Schlaghärte:** Leertaste (oder SCHLAG-Button) halten, der Balken pendelt, loslassen schlägt
- **Garderobe:** Ballfarbe (Palette oder frei wählbar), Muster und 11 Hüte
- **Rangliste** pro Strecke. Als claude.ai-Artifact ist sie für alle gemeinsam, sonst wird sie lokal im Browser gespeichert.

## Steuerung

| Eingabe | Aktion |
|---|---|
| Maus oder Finger ziehen / `←` `→` | Kamera drehen und zielen |
| Mausrad / Pinch / `↑` `↓` | Zoom und Neigung |
| `Leertaste` halten / loslassen | Schlag aufladen / schlagen |
| `C` | Übersichtskarte |
| `Esc` | Pause |

## Weitere Spiele im Repo

- `fairway.html`: das ursprüngliche 3D-Golfspiel *Fairway 3D* mit 9 Löchern
