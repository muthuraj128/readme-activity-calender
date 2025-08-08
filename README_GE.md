<!-- Banner Image -->
<div align="center">
  <img src="./assets/fewinfos-banner.png" alt="Willkommen bei FEWINFOS Contribution - GitHub Repository Statistik Widget" width="100%">
</div>

# 📦 GitHub Repository Statistik Widget

Ein Open-Source, vollständig clientseitiges Tool, das **Echtzeit-GitHub-Repository-Statistiken** in einem interaktiven und anpassbaren Format visualisiert — perfekt für Entwickler, Open-Source-Maintainer und Portfolio-Ersteller.

---

## 🎯 Zielsetzung

Dieses Widget verwendet die GitHub REST API, um verschiedene Metadaten und Einblicke in jedes öffentliche GitHub-Repository abzurufen und anzuzeigen. Es funktioniert **vollständig im Browser** ohne Backend oder Authentifizierung.

---

## ✨ Funktionen

- 🔄 Echtzeit-Datenabruf über GitHub REST API
- ⭐ Anzeige von Stars, Forks, Watchers, Issues und Pull Requests
- 👥 Visualisierung von Top-Mitwirkenden mit Avataren und Commit-Anzahl
- 📊 Anzeige verwendeter Sprachen mit interaktiven Diagrammen
- 📅 Anzeige von Repository-Erstellungsdatum und letzter Aktualisierung
- 📜 Lizenzinformationen
- 🎨 Klare, responsive und anpassbare Benutzeroberfläche
- 💻 Läuft direkt in jedem Browser (keine Server-Einrichtung)
- 🧩 Einfach in Websites oder README.md-Dateien einbettbar
- 📈 Optionale Visualisierungen über Chart.js

---

## 🧱 Tech Stack

- **HTML** – Struktur und Layout
- **CSS** – Styling und Responsiveness
- **JavaScript** – Logik und API-Verarbeitung
- **GitHub REST API** – Datenquelle
- **Chart.js** – Für die Darstellung von Diagrammen und Grafiken (optional)

---

## 📊 Verfügbare Widgets

### 🔍 Repository-Statistiken

- ⭐ Stars / 🍴 Forks / 👁️ Watchers Zähler
- 📅 Repository-Erstellungs- und letztes Aktualisierungsdatum
- 📜 Lizenztyp-Anzeige
- 📊 Sprachgebrauch (Kreis-, Balken-, Donut-Diagramm)
- 📦 Abhängigkeitsdiagramm (npm, pip, etc.)
- 📈 Commit-Aktivitäts-Heatmap
- 🕐 Durchschnittliche PR-Zusammenführungszeit
- 🧵 Issue-Status-Aufschlüsselung (Offen / Geschlossen / Angepinnt)

### 👥 Mitwirkende Widgets

- 👥 Top-Mitwirkende (Avatare + Commit-Anzahl)
- 📊 Beiträge nach Wochentag
- 🗺️ Mitwirkenden-Standortkarte (öffentliche Daten)
- ⏱️ Kürzliche Mitwirkende (letzte 7 / 30 Tage)
- 📈 Beiträge im Zeitverlauf (gestapeltes Flächendiagramm)

### 📊 Diagramm-basierte Widgets

- 📊 Radar-Diagramm der Repository-Gesundheit (Stars, Forks, PRs, Issues)
- 📉 Liniendiagramm für Star/Fork-Wachstumstrends
- 🍩 Donut-Diagramm für Sprachgebrauch
- 📈 Flächendiagramm für Issue/PR-Trends
- 📆 GitHub-Stil Kalender-Heatmap

### ⚙️ DevOps & CI/CD Widgets

- 🚦 GitHub Actions CI/CD Status-Abzeichen
- 🧪 Code Coverage Abzeichen (Codecov, Coveralls)
- 🔄 Letzter Workflow-Ausführungsstatus Widget
- 🛠️ Build-Historie-Zeitleiste (Erfolgs-/Fehlschlagvisualisierung)

### 📌 Issue & PR Widgets

- 📋 Angepinnte Issues oder Diskussionen
- 🔍 Issue-Label-Wortwolke
- 📬 PR-Zusammenführungsstatus/Verhältnis-Tracker
- 📈 Issue-Stimmungsindikator (basierend auf Schlüsselwörtern)

### 🧩 Verschiedene Widgets

- 📌 Lesezeichen/Favoriten-Repository-Schaltfläche
- 🔍 Inline-Suche zum Eingeben anderer Repositories
- 🧠 KI-gestützte Commit-Zusammenfassung (optional)
- 🔗 Verwandte Repository-Widgets
- 🪄 Exportieren von Widgets als iframe / HTML-Einbettung

---

## 📂 Projektstruktur

```
github-repo-stats-widget/
├── index.html         # Haupt-HTML-Datei
├── style.css          # CSS-Stile
├── repo.js            # Kern-JavaScript-Logik
├── charts.js          # Diagramm-Rendering-Logik
├── assets/            # Icons, Screenshots
├── README.md          # Diese Dokumentationsdatei
└── LICENSE            # MIT-Lizenz
```

---

## 🚀 Bereitstellung

Dieses Widget kann auf **GitHub Pages** oder mit jedem statischen Hosting-Dienst wie Netlify, Vercel oder Firebase bereitgestellt werden.

### Bereitstellung über GitHub Pages

1. Pushen Sie Ihr Projekt zu GitHub
2. Gehen Sie zu **Einstellungen → Pages**
3. Wählen Sie Branch: `main` und Ordner: `/ (root)`
4. Ihr Widget wird gehostet unter:  
   `https://yourusername.github.io/github-repo-stats-widget/`
