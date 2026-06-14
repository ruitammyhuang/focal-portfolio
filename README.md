# Focal Case Portfolio
### Human–AI Collaborative System Design: A Faculty Case Study

A structured case portfolio documenting the design and development of [Focal](https://github.com/ruitammyhuang) — a faculty workload management system — through iterative collaboration with Claude AI. Designed to generate knowledge for **CS Education** and **Instructional Design** research.

---

## 🚀 Deploy to GitHub Pages (one-time setup)

### 1. Create a new GitHub repository

Go to [github.com/new](https://github.com/new) and create a repo named:
```
focal-portfolio
```
Make it **public** (required for free GitHub Pages).

### 2. Push the portfolio files

Open Terminal and run:

```bash
# Navigate to this portfolio folder
cd /path/to/Notion_Auto_PM/portfolio

# Initialize git and push
git init
git add .
git commit -m "Initial portfolio launch"
git branch -M main
git remote add origin https://github.com/ruitammyhuang/focal-portfolio.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repo on GitHub → **Settings** → **Pages**
2. Under "Source", select **Deploy from a branch**
3. Choose **main** branch, **/ (root)** folder
4. Click **Save**

Your site will be live at:
```
https://ruitammyhuang.github.io/focal-portfolio/
```
(Takes ~2 minutes to deploy after enabling)

### 4. Update the social sharing URL

Open `index.html` and replace the placeholder URL in the `<meta property="og:url">` tag:
```html
<meta property="og:url" content="https://ruitammyhuang.github.io/focal-portfolio/">
```

---

## 📁 Portfolio Structure

```
portfolio/
├── index.html          ← Home / landing page
├── case.html           ← The Case: what Focal is and why it was complex
├── process.html        ← Phase-by-phase development process
├── resources.html      ← Checklists, frameworks, prompting strategies
├── competencies.html   ← Competency analysis (strengths + gaps)
├── lessons.html        ← Lessons learned (what works, pitfalls, surprises)
├── implications.html   ← Implications for CS Ed + Instructional Design
├── updates.html        ← Living update log
├── css/
│   └── style.css       ← Shared styles
├── js/
│   └── main.js         ← Navigation + interactions
└── README.md           ← This file
```

---

## 🔄 Updating the Portfolio

The portfolio is a **living document**. As the Focal system evolves, run a monthly update session:

1. Open a new Claude Cowork session in the `Notion_Auto_PM` project
2. Say: *"Let's do a monthly portfolio update using the update template"*
3. Claude will guide you through what changed and update the relevant pages
4. Push changes to GitHub:

```bash
cd /path/to/Notion_Auto_PM/portfolio
git add .
git commit -m "Portfolio update: [Month Year] — [one-line summary]"
git push
```

---

## 🎯 Portfolio Purpose

1. **Knowledge** — Frameworks for human–AI collaborative system design
2. **Competencies** — What skills this process reveals we need to teach
3. **Design Artifacts** — Iteratively refined system design documents
4. **Lessons Learned** — What works, what to avoid, with teaching implications

Primary audiences: CS Education students, researchers, and educators; Instructional Designers; faculty considering similar systems.

---

*Dr. Rui (Tammy) Huang · [github.com/ruitammyhuang](https://github.com/ruitammyhuang)*
