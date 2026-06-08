# DSI Lernapp

Statische Lern-Website für das Modul **Data Science Introduction** (30 Themen).
Enthält ein interaktives Quiz (300 Fragen), einen Spickzettel und alle Probeklausuren/Lernunterlagen als PDF.

## Inhalt
- `index.html` – Startseite / Dashboard (Einstiegspunkt)
- `quiz.html` – interaktives Quiz (Single Choice, Auswertung pro Thema)
- `notes.html` – Spickzettel als Webseite (handytauglich)
- `pdf/` – Zusammenfassung, Lernunterlagen, Spickzettel, 5 Probeklausuren + Gesamtprüfung (90) inkl. Lösungen

## Online stellen

### Variante A – Netlify (Drag & Drop, am einfachsten)
1. https://app.netlify.com/drop öffnen.
2. **Den gesamten Ordner `dsi-lernapp`** ins Fenster ziehen (nicht nur eine Datei!).
3. Fertig – du bekommst sofort eine URL. Auf dem iPhone in Safari öffnen.

### Variante B – GitHub + Netlify
1. Den Inhalt von `dsi-lernapp/` ins Repo legen, sodass **`index.html` im Stammverzeichnis** liegt (nicht in einem Unterordner!).
2. Push zu GitHub.
3. Netlify → „Add new site“ → „Import an existing project“ → Repo wählen.
   - **Build command:** leer lassen
   - **Publish directory:** `.` (Punkt) bzw. Stammverzeichnis
4. Deploy.

### Variante C – GitHub Pages
1. `index.html` muss im Repo-Stamm liegen.
2. Repo → Settings → Pages → Source: `main` / `/ (root)` → Save.

## Häufiger Fehler
Wenn die Seite „Page not found“ zeigt: Die Startdatei muss **`index.html`** heißen und im **Stammverzeichnis** liegen. Genau das ist hier schon so eingerichtet.
