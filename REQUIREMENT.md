# 📋 REQUIREMENT.md

This document outlines all the functional, technical, and tooling requirements for the **GitHub Repository Stats Widget** open-source project.

---

## ✅ Functional Requirements

- Fetch and display **real-time GitHub repository statistics** using the GitHub REST API.
- Work **entirely in the browser** with no server or backend setup.
- Provide widgets for:
  - ⭐ Stars / 🍴 Forks / 👁️ Watchers
  - 👥 Contributors info
  - 📜 License and metadata
  - 📊 Programming language usage
  - 📅 Activity heatmaps and commit trends
  - 🧩 Misc tools like CI badges, PR/issue metrics, and charts
- Allow **embedding** in websites, portfolios, or README.md files.
- Be **responsive, accessible, and customizable**.

---

## 🔌 GitHub API (Core Dependency)

This project relies entirely on the **GitHub REST API** to fetch repository data.

| API              | Purpose                                                   | Required | Docs Link                                           |
|------------------|-----------------------------------------------------------|----------|----------------------------------------------------|
| GitHub REST API  | Fetch repo info, issues, PRs, languages, contributors     | ✅ Yes   | [GitHub API Docs](https://docs.github.com/en/rest) |

### 🔑 Key Endpoints Used

- `GET /repos/:owner/:repo` – Repository metadata
- `GET /repos/:owner/:repo/languages` – Language usage
- `GET /repos/:owner/:repo/contributors` – Contributor stats
- `GET /repos/:owner/:repo/issues` – Open/closed issues
- `GET /repos/:owner/:repo/pulls` – Pull request metrics
- `GET /repos/:owner/:repo/commits` – Commit history (optional)
- `GET /repos/:owner/:repo/actions/runs` – CI/CD workflows (optional)

> ⚠️ Works without authentication but may hit GitHub’s public rate limit (60 requests/hour). For higher limits, users can provide a **Personal Access Token (PAT)**.

---

## 🧱 Tech Stack

| Technology      | Purpose                     |
|------------------|-----------------------------|
| **HTML**         | Page structure              |
| **CSS**          | Styling & responsiveness    |
| **JavaScript**   | Data handling and logic     |
| **Chart.js**     | Graphs and charts (optional)|
| **GitHub REST API** | Core data source         |

---

## 📂 Project Structure

```
github-repo-stats-widget/
├── index.html         # Main HTML file
├── style.css          # CSS styles
├── repo.js            # Core JavaScript logic
├── charts.js          # Chart rendering logic
├── assets/            # Icons, screenshots
├── README.md          # This documentation file
└── LICENSE            # MIT License
```
---



---

## 🌐 Deployment Options

You can deploy this widget using any **static hosting** platform:

- **GitHub Pages**
- **Vercel**
- **Netlify**
- **Firebase Hosting**

### 📦 GitHub Pages Steps

1. Push the code to your GitHub repo
2. Navigate to **Settings → Pages**
3. Choose source: `main` branch and `/root`
4. Access the widget via:
   `https://yourusername.github.io/github-repo-stats-widget/`

---

## 🔧 Optional Tools (Used if Required)

| Tool           | Purpose                        | Optional |
|----------------|----------------------------------|----------|
| Chart.js       | Interactive graphs and charts   | ✅ Yes    |
| Codecov / Coveralls | Code coverage badges      | ✅ Yes    |
| GitHub Actions | CI/CD badge integration         | ✅ Yes    |
| Leaflet.js / Mapbox | Contributor maps           | ✅ Yes    |

---

