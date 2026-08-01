<h1 align="center">Hi 👋, I'm Tahir Bhat</h1>

<h3 align="center">💻 B.Tech CSE Student | Python Developer | Learning C & C++ | AI Enthusiast</h3>

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=00F7FF&center=true&vCenter=true&width=700&lines=Welcome+to+my+GitHub!;B.Tech+CSE+Student;Python+Developer;Learning+C+and+C%2B%2B;AI+Enthusiast;Always+Learning+New+Things" />
</p>

---

## 🚀 About Me

- 🎓 B.Tech Computer Science Student
- 🌱 Currently learning **C, C++, Python & DSA**
- 🤖 Interested in **Artificial Intelligence & Machine Learning**
- 💻 Love building projects and solving coding problems
- 📍 India

---

## 🛠 Tech Stack

<p align="center">
<img src="https://skillicons.dev/icons?i=python,c,cpp,git,github,vscode,linux,html,css"/>
</p>

---

## 📊 GitHub Stats

<p align="center">
<img src="https://github-readme-stats-sigma-five.vercel.app/api?username=TahirBhat-2008&show_icons=true&theme=tokyonight&hide_border=true"/>
<img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=TahirBhat-2008&layout=compact&theme=tokyonight&hide_border=true"/>
</p>

---

## 🔥 GitHub Streak

<p align="center">
<img src="https://streak-stats.demolab.com?user=TahirBhat-2008&theme=tokyonight&hide_border=true"/>
</p>

---

## 🏆 GitHub Trophies



<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=TahirBhat-2008&theme=tokyonight&row=1&column=7&no-frame=true&margin-w=10" />
</p>

---

## 📈 Contribution Graph

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=TahirBhat-2008&theme=tokyo-night"/>
</p>

---

## 🐍 Contribution Snake

<p align="center">
<img src="https://raw.githubusercontent.com/TahirBhat-2008/TahirBhat-2008/output/github-contribution-grid-snake.svg"/>
</p>

---

## 🌐 Connect with Me

<p align="center">
<a href="https://github.com/TahirBhat-2008">
<img src="https://skillicons.dev/icons?i=github"/>
</a>
</p>

---

<p align="center">
<img src="https://komarev.com/ghpvc/?username=TahirBhat-2008&label=Profile%20Views&color=0e75b6&style=flat"/>
</p>
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: TahirBhat-2008
          outputs: |
            dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
