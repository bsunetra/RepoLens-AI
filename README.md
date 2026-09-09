# 🔎 RepoLens AI

> **GitHub Repository Intelligence — understand any public repository in seconds.**

RepoLens AI converts GitHub repository metadata into an interactive engineering dashboard covering **repository health, detected technology stack, project structure, and recruiter-readiness signals**.

## ✨ Features

- 🔗 Analyze any public GitHub repository by URL
- 📊 Language distribution from GitHub's language API
- 🧠 Engineering-health scoring
- 🎯 Recruiter-readiness scoring
- 🏗️ Repository structure explorer
- ⚙️ CI/CD and testing signal detection
- 💡 Actionable engineering recommendations
- 📱 Responsive, premium developer-tool UI
- 🔐 No repository data is stored

## 🛠️ Tech Stack

**Frontend:** HTML5 · CSS3 · Vanilla JavaScript  
**API:** GitHub REST API  
**Architecture:** Client-side application with zero backend dependency

## 🚀 Run locally

```bash
git clone https://github.com/bsunetra/RepoLens-AI.git
cd RepoLens-AI
```

Open `index.html` in a browser.

No API key or build step is required for public repositories.

## 🧩 How it works

```text
GitHub URL
    ↓
Parse owner/repository
    ↓
GitHub REST API
    ├── Repository metadata
    ├── Language statistics
    └── Recursive file tree
    ↓
Signal extraction
    ├── Testing
    ├── CI/CD
    ├── Documentation
    └── Project complexity
    ↓
RepoLens Intelligence Dashboard
```

## 📈 Scoring model

RepoLens uses transparent heuristic signals rather than pretending a black-box model is accurate. The current prototype scores:

- Testing presence
- GitHub Actions / CI presence
- Documentation
- License
- Issue hygiene
- Repository activity
- Technology diversity
- Project description and homepage

## 🔮 Roadmap

- [ ] Gemini-powered README and architecture analysis
- [ ] Dependency vulnerability insights
- [ ] Commit activity visualization
- [ ] Contributor health analysis
- [ ] Exportable PDF report
- [ ] GitHub OAuth for private repositories
- [ ] Historical repository health tracking

## ⚠️ API limits

GitHub's unauthenticated REST API has rate limits. For a production version, authenticated requests or a small backend proxy should be added.

## 👩‍💻 Author

**B. Sunetra**  
AI & Data Science · Full-stack & AI/ML enthusiast

---

⭐ If this project is useful, consider starring the repository.
