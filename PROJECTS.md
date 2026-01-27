# Projekt-Struktur Clawd Workspace

## Verzeichnis-Baum

```
/root/clawd/
├── projekte/                    # Alle Projekte
│   ├── foerderungen-mair.de/    # Förderberatung Website
│   │   ├── index.html           # Landingpage
│   │   ├── admin.html           # Admin Dashboard
│   │   ├── status.html          # Alte Status-Seite (deprecated)
│   │   ├── css/style.css        # Styles
│   │   ├── js/app.js            # Frontend JS
│   │   ├── js/admin.js          # Admin JS
│   │   └── data/foerderungen.json
│   │
│   └── status-board/            # 🌟 NEU: Multi-Projekt Status Board
│       ├── index.html           # Haupt-Status Board (öffnen!)
│       ├── css/style.css        # Styles
│       └── data/projects.json   # Projekt-Konfiguration
│
├── memory/                      # Arbeitsgedächtnis
├── notizen/                     # Persönliche Notizen
├── skripte/                     # Hilfsskripte
└── canvas/                      # Canvas-Dateien
```

## Status Board (status-board/)

**Features:**
- ✅ Mehrere Projekte verwalten
- ✅ 3 Spalten: Zu erledigen | In Bearbeitung | Fertig
- ✅ Drag & Drop zwischen Spalten
- ✅ Aufgaben zuweisen: Ich, Mair, AI / Clawdbot
- ✅ Kategorien: Entwicklung, Design, Content, Marketing, Organisation
- ✅ Prioritäten: Hoch, Mittel, Niedrig
- ✅ Fälligkeitsdaten mit Überfällig-Markierung
- ✅ Suche & Filter
- ✅ Aktivitäts-Protokoll
- ✅ Alles in localStorage gespeichert

**Start:** `/root/clawd/projekte/status-board/index.html`

## Vorinstallierte Projekte

| Projekt | Beschreibung | Farbe |
|---------|--------------|-------|
| förderungen-mair.de | Förderberatung Website | Gold #C9A962 |
| Clawdbot | Persönlicher AI Assistent | Lila #8B5CF6 |
| Hauptwebsite | Hauptpräsenz im Web | Blau #1E3A5F |

## Beispiel-Aufgaben

- Website online schalten (förderungen-mair.de)
- SEO optimieren (AI zugewiesen)
- Neue Skills entwickeln (Clawdbot, AI)
- Design überarbeiten (Hauptwebsite, Mair)

## Tastenkürzel

- `Escape` = Modal schließen
- Drag & Drop = Aufgabe verschieben
