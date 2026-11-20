# ⛳ Putt Paradies

3D-Minigolf für den Browser, gebaut mit [Three.js](https://threejs.org/). Das ganze Spiel steckt in einer einzigen `index.html`.

## Spielen

`index.html` im Browser öffnen. Three.js und die Schriften kommen von einem CDN, du brauchst also Internet.

## Features

- **10 Strecken mit je 6 Löchern (60 Löcher):** Sonnenwiese, Piratenbucht, Lavakrater, Regenwald, Pyramiden, Geisterfriedhof, Weihnachtsdorf, Weltraumstation (geringe Schwerkraft), Zuckerland und Kirschblütengarten
- **Echte Vorschau** in der Streckenauswahl: Jedes Loch wird als 3D-Bild gerendert
- **Hochauflösende, prozedural erzeugte Texturen:** gemähtes Karomuster, Holz, Stein, Sandstein mit Hieroglyphen, Eis, Metall, Zuckerstangen und mehr
- **Hindernisse:** Windmühle, Rampen, Sprungschanzen, Schiebeplanken, Drehbalken, Pendel, Drehkreuz, Grabtüren, Teleporter, Flöße, Eisflächen, Treibsand und Beschleuniger
- **Zufälliges Wetter je Loch**, passend zum Thema: Sonnig, Bewölkt, Regen (die Bahn ist nass, der Ball rollt kürzer), Schnee (glatt, der Ball rollt weiter), Nebel, Sturm mit Blitzen und Sandsturm
- **Wind** mit Richtung und Stärke, der den Ball ablenkt. Die Fahne weht mit.
- **Schlaghärte:** Leertaste (oder SCHLAG-Button) halten, der Balken pendelt, loslassen schlägt
- **Garderobe:** Ballfarbe (Palette oder frei wählbar), Muster, 11 Hüte und 7 Spuren (Feuer, Eis, Blitz, Sterne, Regenbogen, Regen, Klassisch)
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
