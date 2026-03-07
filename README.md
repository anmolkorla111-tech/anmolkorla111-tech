
<h1 align="center">Hi 👋, I'm Anmol Korla</h1>
<h3 align="center">Backend • Cloud • DevOps Developer</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&center=true&vCenter=true&width=800&lines=Backend+Developer;Cloud+%26+DevOps+Enthusiast;Building+with+Docker%2C+Jenkins+%26+AWS;DSA+%7C+Projects+%7C+Continuous+Learning" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=anmolkorla111-tech&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" />
</p>

---

## 🚀 About Me

- 🎓 BCA Student
- 💻 Focused on **Backend Development, Cloud and DevOps**
- ⚙️ Building **real-world projects** with modern development tools
- 📚 Practicing **DSA, project building and deployment workflows**
- 📫 Reach me at: **anmolkorla111@gmail.com**

---

## 🔥 Featured Projects

### 🚀 AutoDeploy Platform
CI/CD workflow project using **GitHub, Jenkins and Docker** for automated build and deployment.

### ☁️ DevOps Capstone Project
Hands-on DevOps implementation covering **local setup, Jenkins pipeline and containerized deployment**.

### 🧠 Multi-Tenant SaaS Backend
Scalable backend architecture project focused on **multi-tenant SaaS systems** and API design.

### 🌐 Portfolio Website
A personal portfolio project to showcase **skills, projects and developer profile**.

---

## 🧰 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp,python,js,ts,nodejs,react,nextjs,mongodb,mysql,git,github,docker,aws,linux,vscode" alt="tech stack" />
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=anmolkorla111-tech&show_icons=true&theme=tokyonight&hide_border=true" height="170" alt="stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=anmolkorla111-tech&layout=compact&theme=tokyonight&hide_border=true" height="170" alt="languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=anmolkorla111-tech&theme=tokyonight&hide_border=true" alt="streak stats" />
</p>

---

## 🎯 Current Focus

- Backend Development
- DevOps Projects
- Cloud Learning
- DSA Practice
- Building a strong GitHub profile

---

## 🏆 GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=anmolkorla111-tech&theme=tokyonight&no-frame=true&no-bg=true&margin-w=10&row=1" alt="trophies" />
</p>

---

## 🤝 Connect With Me

<p align="center">
  <a href="mailto:anmolkorla111@gmail.com">
    <img src="https://img.shields.io/badge/Email-anmolkorla111%40gmail.com-red?style=for-the-badge&logo=gmail&logoColor=white" alt="email" />
  </a>
  <a href="https://github.com/anmolkorla111-tech">
    <img src="https://img.shields.io/badge/GitHub-anmolkorla111--tech-black?style=for-the-badge&logo=github&logoColor=white" alt="github" />
  </a>
</p>

---

## 🐍 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/anmolkorla111-tech/anmolkorla111-tech/output/github-contribution-grid-snake.svg" alt="snake animation" />
</p>

---

<p align="center">
  ⭐ Thanks for visiting my profile
</p>

## ⚠️ Important Note for Snake Animation

Snake animation tab kaam karega jab tum repo me GitHub Action add karoge. Baaki sab abhi kaam karega.

GitHub Action file path:

```yaml
.github/workflows/snake.yml
```

Code:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: anmolkorla111-tech
          outputs: |
            dist/github-contribution-grid-snake.svg
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
