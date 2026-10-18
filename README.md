# Portiva-Downloads

Fertige Programme von **Fundbrüder AI** (Fundbrüder GbR) · https://fundbrueder-ai.de
Hier liegen nur die Installationsdateien – kein Quellcode.

## Programme

| Software | Für | Ordner |
|---|---|---|
| **Portiva KI-Transkribierung** + **Portiva Diktat für Word** | Android-Handy, Windows-PC | [📁 KI-Transkribierung](KI-Transkribierung/) |

Jeder Ordner zeigt die aktuelle Version mit direkten Download-Links und Installationshinweisen.
Die Dateien selbst hängen an den [Releases](https://github.com/Schnielz87/Portiva-Downloads/releases)
(je Software mit eigenem Namen, z. B. `ki-transkribierung-v1.3.35`).

## Aufbau (für weitere Programme)

```
Portiva-Downloads/
├── README.md                  ← diese Übersicht
├── KI-Transkribierung/        ← Portiva KI-Transkribierung (Android) + Portiva Diktat für Word (Windows)
│   └── README.md              ← wird bei jedem Build automatisch auf die neue Version gesetzt
└── <Weitere-Software>/        ← neuer Ordner je Programm, Release-Tags mit eigenem Präfix
    └── README.md
```

Neue Software: eigenen Ordner anlegen, Releases mit eigenem Tag-Präfix veröffentlichen
(`<software>-v<Version>`), Zeile in der Tabelle oben ergänzen. Die Update-Funktion jeder App sucht
nur nach Releases mit ihrem eigenen Präfix – Programme kommen sich so nicht in die Quere.

Kontakt: kontakt@fundbrueder-ai.de · +49 152 26667212
