# How to Build an Awesome GitHub Portfolio (Profile README)

Your GitHub profile README is your developer landing page — the first thing people see when they visit your profile. This guide walks you through creating one from scratch.

---

## 1. Create the Magic Repository

GitHub renders a special README when you create a repository that **matches your username**.

1. Go to [github.com/new](https://github.com/new)
2. Set the **Repository name** to your GitHub username (e.g., if your username is `chaikokcheng`, name it `chaikokcheng`)
3. Make it **Public**
4. Check **Add a README file**
5. Click **Create repository**

> You'll see a message: *"You found a secret! chaikokcheng/chaikokcheng is a special repository."*

---

## 2. Structure Your README

A great profile README typically includes these sections:

```markdown
# Hi there, I'm Kok Cheng 👋

## About Me
- 🔭 I'm currently studying at UPM (Universiti Putra Malaysia)
- 🌱 I'm currently learning modern web development
- 👯 I'm looking to collaborate on student projects and hackathons
- 💬 Ask me about my coursework or projects
- 📫 How to reach me: your.email@student.upm.edu.my
- ⚡ Fun fact: I love drinking coffee while coding

## Tech Stack

## Projects

## GitHub Stats

## Connect With Me
```

**Result:**

> # Hi there, I'm Kok Cheng 👋
> 
> ## About Me
> - 🔭 I'm currently studying at UPM (Universiti Putra Malaysia)
> - 🌱 I'm currently learning modern web development
> - 👯 I'm looking to collaborate on student projects and hackathons
> - 💬 Ask me about my coursework or projects
> - 📫 How to reach me: your.email@student.upm.edu.my
> - ⚡ Fun fact: I love drinking coffee while coding
> 
> *(Other sections omitted in this preview)*

---

## 3. Write a Strong Introduction

Keep it short, authentic, and scannable. Lead with **who you are** and **what you do**.

**Good example:**

```markdown
# Hi, I'm Kok Cheng 👋

I'm a computer science student at UPM passionate about building cool web applications.
Currently focusing on modern web frameworks, previously built some campus event management tools.
```

**Result:**

> # Hi, I'm Kok Cheng 👋
> 
> I'm a computer science student at UPM passionate about building cool web applications.
> Currently focusing on modern web frameworks, previously built some campus event management tools.

**Tips:**
- Use a one-liner that summarizes your identity
- Mention your current role or focus area
- Keep it to 2–3 sentences max

---

## 4. Showcase Your Tech Stack

Use badges to make your skills visual and scannable. [Shields.io](https://shields.io/) and [Simple Icons](https://simpleicons.org/) are your friends.

```markdown
## 🛠 Tech Stack

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
```

**Result:**

> ## 🛠 Tech Stack
>
> ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
> ![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
> ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
> ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
> ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
> ![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)

**Badge format:**
```
https://img.shields.io/badge/-LABEL-COLOR?style=flat-square&logo=LOGO_NAME&logoColor=white
```

Find logo names at [simpleicons.org](https://simpleicons.org/).

---

## 5. Highlight Your Best Projects

Don't list everything — curate 3–5 of your strongest projects.

**Option A: Simple table**

```markdown
## 🚀 Featured Projects

| Project | Description | Tech |
|---------|------------|------|
| [**project-name**](https://github.com/you/project) | One-line description | React, Node.js |
| [**another-project**](https://github.com/you/another) | One-line description | Python, FastAPI |
```

**Result:**

> ## 🚀 Featured Projects
> 
> | Project | Description | Tech |
> |---------|------------|------|
> | [**project-name**](https://github.com/you/project) | One-line description | React, Node.js |
> | [**another-project**](https://github.com/you/another) | One-line description | Python, FastAPI |

**Tips:**
- Link to live demos when available
- Choose projects that show range (frontend, backend, CLI, library, etc.)
- Make sure featured repos have good READMEs themselves

---

## 6. Add GitHub Stats


**Result:**

> ![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=chaikokcheng&theme=dark)

**Available themes:** `dark`, `radical`, `merko`, `gruvbox`, `tokyonight`, `onedark`, `cobalt`, `synthwave`, `dracula`, and more.

---

## 7. Add Social / Contact Links

Make it easy for people to reach you.

```markdown
## 🤝 Connect With Me

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/chaikokcheng)
[![Twitter](https://img.shields.io/badge/-Twitter-1DA1F2?style=flat-square&logo=twitter&logoColor=white)](https://twitter.com/chaikokcheng)
[![Portfolio](https://img.shields.io/badge/-Portfolio-000?style=flat-square&logo=google-chrome&logoColor=white)](https://github.com/chaikokcheng)
[![Email](https://img.shields.io/badge/-Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:your.email@student.upm.edu.my)
```

**Result:**

> ## 🤝 Connect With Me
>
> [![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/chaikokcheng)
> [![Twitter](https://img.shields.io/badge/-Twitter-1DA1F2?style=flat-square&logo=twitter&logoColor=white)](https://twitter.com/chaikokcheng)
> [![Portfolio](https://img.shields.io/badge/-Portfolio-000?style=flat-square&logo=google-chrome&logoColor=white)](https://github.com/chaikokcheng)
> [![Email](https://img.shields.io/badge/-Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:your.email@student.upm.edu.my)

---

## 8. Optional Enhancements

### Dynamic Activity Graph

```markdown
![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=chaikokcheng&theme=tokyo-night)
```

**Result:**

> ![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=chaikokcheng&theme=tokyo-night)

### Visitor Counter

```markdown
![Profile Views](https://komarev.com/ghpvc/?username=chaikokcheng&color=blue)
```

**Result:**

> ![Profile Views](https://komarev.com/ghpvc/?username=chaikokcheng&color=blue)

### Animated Typing Effect

Use [readme-typing-svg](https://github.com/DenverCoder1/readme-typing-svg):

```markdown
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=36BCF7&width=435&lines=Full+Stack+Developer;Open+Source+Enthusiast;Always+Learning)](https://git.io/typing-svg)
```

**Result:**

> [![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=36BCF7&width=435&lines=Full+Stack+Developer;Open+Source+Enthusiast;Always+Learning)](https://git.io/typing-svg)

---

## 9. Add a "Currently Working On" Section

Show visitors what you're actively building. This signals you're an active developer.

```markdown
## 🔭 Currently Working On

- 🚧 Building a **real-time collaboration tool** with WebSockets and React
- 📖 Writing a blog series on **system design patterns**
- 🌱 Learning **Rust** and **WebAssembly**
```

**Result:**

> ## 🔭 Currently Working On
> 
> - 🚧 Building a **real-time collaboration tool** with WebSockets and React
> - 📖 Writing a blog series on **system design patterns**
> - 🌱 Learning **Rust** and **WebAssembly**

---

## 10. Add Work Experience / Timeline

Great for developers looking for jobs or freelance work.

**Option A: Simple list**

```markdown
## 💼 Experience & Education

- 🎓 **Bachelor of Computer Science** @ UPM *(2021 – Present)*
- 💻 **Web Engineering Intern** @ TechCompany *(Summer 2023)*
- 🏆 **Hackathon Team Lead** @ UPM Hackathon *(2022)*
```

**Result:**

> ## 💼 Experience & Education
>
> - 🎓 **Bachelor of Computer Science** @ UPM *(2021 – Present)*
> - 💻 **Web Engineering Intern** @ TechCompany *(Summer 2023)*
> - 🏆 **Hackathon Team Lead** @ UPM Hackathon *(2022)*

**Option B: Visual timeline**

```markdown
## 💼 Experience

| Year | Role | Company |
|------|------|---------|
| 2023 – Present | Senior Frontend Engineer | Acme Corp |
| 2021 – 2023 | Full Stack Developer | StartupXYZ |
| 2019 – 2021 | Junior Developer | Agency123 |
```

---

## 11. Add Certifications & Achievements

Showcase credentials that add credibility.

```markdown
## 🏆 Certifications & Achievements

- 🎓 **AWS Certified Solutions Architect** – Associate *(2024)*
- 🎓 **Google Professional Cloud Developer** *(2023)*
- 🏅 **Hacktoberfest** contributor – 4 consecutive years
- ⭐ **500+ stars** on open-source projects
- 📝 **Published author** on Medium / Dev.to with 50k+ reads
```

---

## 12. Add a "Fun Facts" or Personal Touch Section

Makes your profile memorable and human.

```markdown
## ⚡ Fun Facts

- 🎮 I speedrun retro games in my free time
- ☕ I mass produce my code on heavy amounts of coffee  
- 🌍 I've worked remotely from 12 different countries
- 🐱 My rubber duck debugger is actually a real cat
- 📚 Currently reading: *Designing Data-Intensive Applications*
```

---

## 13. Add a Support / Sponsor Section

If you do open-source work, make it easy for people to support you.

```markdown
## 💖 Support My Work

If you find my projects helpful, consider supporting me:

[![Buy Me A Coffee](https://img.shields.io/badge/-Buy%20Me%20A%20Coffee-FFDD00?style=flat-square&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/chaikokcheng)
[![GitHub Sponsors](https://img.shields.io/badge/-Sponsor-EA4AAA?style=flat-square&logo=github-sponsors&logoColor=white)](https://github.com/sponsors/chaikokcheng)
[![Ko-fi](https://img.shields.io/badge/-Ko--fi-FF5E5B?style=flat-square&logo=ko-fi&logoColor=white)](https://ko-fi.com/chaikokcheng)
```

**Result:**

> ## 💖 Support My Work
> 
> If you find my projects helpful, consider supporting me:
> 
> [![Buy Me A Coffee](https://img.shields.io/badge/-Buy%20Me%20A%20Coffee-FFDD00?style=flat-square&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/chaikokcheng)
> [![GitHub Sponsors](https://img.shields.io/badge/-Sponsor-EA4AAA?style=flat-square&logo=github-sponsors&logoColor=white)](https://github.com/sponsors/chaikokcheng)
> [![Ko-fi](https://img.shields.io/badge/-Ko--fi-FF5E5B?style=flat-square&logo=ko-fi&logoColor=white)](https://ko-fi.com/chaikokcheng)

---

## 14. Add a "Languages I Speak" Section

Especially useful if you work internationally or in open-source.

```markdown
## 🌐 Languages

- 🇺🇸 English *(native)*
- 🇨🇳 Mandarin *(fluent)*
- 🇯🇵 Japanese *(conversational)*
- 🇪🇸 Spanish *(learning)*
```

**Result:**

> ## 🌐 Languages
> 
> - 🇺🇸 English *(native)*
> - 🇨🇳 Mandarin *(fluent)*
> - 🇯🇵 Japanese *(conversational)*
> - 🇪🇸 Spanish *(learning)*

---

## 15. Add GitHub Trophies

Use [github-profile-trophy](https://github.com/ryo-ma/github-profile-trophy) for auto-generated achievement trophies.

```markdown
## 🏆 GitHub Trophies

![Trophies](https://github-profile-trophy-tawny.vercel.app/?username=chaikokcheng&theme=darkhub&no-frame=true&row=1&column=7)
```

**Result:**

> ## 🏆 GitHub Trophies
> 
> ![Trophies](https://github-profile-trophy-tawny.vercel.app/?username=chaikokcheng&theme=darkhub&no-frame=true&row=1&column=7)

**Available themes:** `flat`, `onedark`, `gruvbox`, `dracula`, `monokai`, `chalk`, `nord`, `alduin`, `darkhub`, `juicyfresh`, `buddhism`, `oldie`, `radical`, `onestar`, `discord`, `algolia`

---

## 16. Add a Snake Animation (Contribution Graph)

A fun animated snake that eats your contribution graph.

Set up with [snk](https://github.com/Platane/snk) GitHub Action:

**Step 1:** Create `.github/workflows/snake.yml`:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *" # runs daily
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: chaikokcheng
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

**Step 2:** Add to your README:

```markdown
![Snake animation](https://raw.githubusercontent.com/chaikokcheng/chaikokcheng/output/github-snake-dark.svg)
```

**Result:**

> ![Snake animation](https://raw.githubusercontent.com/chaikokcheng/chaikokcheng/output/github-snake-dark.svg)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/chaikokcheng/github_portfolio_workshop/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/chaikokcheng/github_portfolio_workshop/output/github-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/chaikokcheng/github_portfolio_workshop/output/github-snake.svg">
</picture>

---

## 17. Add a "Latest Activity" Section (Auto-Updated)

Use [github-activity-readme](https://github.com/jamesgeorge007/github-activity-readme) to auto-update your recent GitHub activity.

**Step 1:** Add placeholder to README:

```markdown
## ⚡ Recent Activity

<!--START_SECTION:activity-->
<!--END_SECTION:activity-->
```

**Step 2:** Create `.github/workflows/activity.yml`:

```yaml
name: Update README

on:
  schedule:
    - cron: "*/30 * * * *" # every 30 minutes
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: jamesgeorge007/github-activity-readme@master
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

This auto-populates with entries like:
> 1. 🎉 Merged PR #42 in user/repo
> 2. 💪 Opened PR #43 in user/repo
> 3. ❗ Opened issue #12 in user/repo

<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

---

## 18. Add a WakaTime Coding Stats Section

Show your weekly coding breakdown with [waka-readme-stats](https://github.com/anmol098/waka-readme-stats).

**Step 1:** Sign up at [wakatime.com](https://wakatime.com) and install the editor plugin.

**Step 2:** Add placeholder to README:

```markdown
## 📊 Weekly Coding Stats

<!--START_SECTION:waka-->
<!--END_SECTION:waka-->
```

**Step 3:** Create a GitHub Action to update it. It auto-generates output like:

```
TypeScript   12 hrs 30 mins  ████████████░░░░░  48.2%
Python       8 hrs 15 mins   ████████░░░░░░░░░  31.8%
CSS          2 hrs 45 mins   ███░░░░░░░░░░░░░░  10.6%
Markdown     1 hr 20 mins    █░░░░░░░░░░░░░░░░   5.2%
Other        1 hr 5 mins     █░░░░░░░░░░░░░░░░   4.2%
```

---

## 19. Make Your Profile Stand Out for Recruiters

If you're job-hunting, tailor your profile as a mini-resume.

```markdown
# Hi, I'm Kok Cheng — CS Student @ UPM based in Selangor 👋

I build [type of things] with [key technologies].
**Open to opportunities** — let's talk!

📄 [**View My Resume**](https://link-to-your-resume.com)

## 💼 What I Bring

- ✅ 5+ years of production experience with React & Node.js
- ✅ Led a team of 4 engineers shipping features to 1M+ users
- ✅ Strong background in system design and API architecture
- ✅ Active open-source contributor (500+ contributions this year)

## 🎯 Looking For

- Full-time Senior Frontend / Full Stack roles
- Remote or hybrid in Selangor
- Product-focused teams building at scale
```

**Result:**

> # Hi, I'm Kok Cheng — CS Student @ UPM based in Selangor 👋
> 
> I build apps with [key technologies].
> **Open to opportunities** — let's talk!
> 
> 📄 [**View My Resume**](https://link-to-your-resume.com)
> 
> ## 💼 What I Bring
> 
> - ✅ 5+ years of production experience with React & Node.js
> - ✅ Led a team of 4 engineers shipping features to 1M+ users
> - ✅ Strong background in system design and API architecture
> - ✅ Active open-source contributor (500+ contributions this year)
> 
> ## 🎯 Looking For
> 
> - Full-time Senior Frontend / Full Stack roles
> - Remote or hybrid in Selangor
> - Product-focused teams building at scale

---

## 20. Design Principles

| Do | Don't |
|----|-------|
| Keep it scannable — use headers, badges, and whitespace | Write giant paragraphs of text |
| Curate your best 3–5 projects | List every repo you've ever made |
| Update it regularly | Let it go stale for months |
| Show personality — it's chaikokchengR page | Copy someone else's README verbatim |
| Use consistent styling (one badge style, one theme) | Mix 5 different visual styles |
| Test how it renders on mobile | Assume everyone views on desktop |

---

## 21. Full Example Template

```markdown
# Hi, I'm [Your Name] 👋

One-liner about who you are and what you do.

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/chaikokcheng)
[![Portfolio](https://img.shields.io/badge/-Website-000?style=flat-square&logo=google-chrome&logoColor=white)](https://you.dev)

---

## 🛠 Tech Stack

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

---

## 🚀 Featured Projects

| Project | Description | Tech |
|---------|------------|------|
| [**cool-project**](https://github.com/you/cool-project) | Short punchy description | React, Node |
| [**another-one**](https://github.com/you/another-one) | Short punchy description | Python, FastAPI |
| [**cli-tool**](https://github.com/you/cli-tool) | Short punchy description | Rust |

---

## 🤝 Let's Connect

I'm always open to interesting conversations and collaboration.
📫 Reach me at **your.email@student.upm.edu.my**
```

---

## Quick Reference: Useful Tools

| Tool | What It Does | Link |
|------|-------------|------|
| Shields.io | Custom badges | [shields.io](https://shields.io/) |
| Simple Icons | Logo names for badges | [simpleicons.org](https://simpleicons.org/) |
| GitHub Readme Stats | Auto-generated stat cards | [github.com/anuraghazra/github-readme-stats](https://github.com/anuraghazra/github-readme-stats) |
| Readme Typing SVG | Animated typing effect | [github.com/DenverCoder1/readme-typing-svg](https://github.com/DenverCoder1/readme-typing-svg) |
| GitHub Profile README Generator | Interactive builder | [rahuldkjain.github.io/gh-profile-readme-generator](https://rahuldkjain.github.io/gh-profile-readme-generator/) |
| Activity Graph | Contribution graph widget | [github.com/Ashutosh00710/github-readme-activity-graph](https://github.com/Ashutosh00710/github-readme-activity-graph) |
| Streak Stats | Contribution streak counter | [github.com/DenverCoder1/github-readme-streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats) |
| Profile View Counter | Visitor badge | [github.com/antonkomarev/github-profile-views-counter](https://github.com/antonkomarev/github-profile-views-counter) |
| GitHub Profile Trophy | Achievement trophies | [github.com/ryo-ma/github-profile-trophy](https://github.com/ryo-ma/github-profile-trophy) |
| Snake Animation | Contribution snake game | [github.com/Platane/snk](https://github.com/Platane/snk) |
| WakaTime Stats | Coding time breakdown | [github.com/anmol098/waka-readme-stats](https://github.com/anmol098/waka-readme-stats) |
| Activity Readme | Auto-update recent activity | [github.com/jamesgeorge007/github-activity-readme](https://github.com/jamesgeorge007/github-activity-readme) |
| Blog Post Workflow | Auto-pull blog posts | [github.com/gautamkrishnar/blog-post-workflow](https://github.com/gautamkrishnar/blog-post-workflow) |
| Spotify Profile | Now playing widget | [github.com/kittinan/spotify-github-profile](https://github.com/kittinan/spotify-github-profile) |

---

**Now go make your GitHub profile stand out!** 🚀
