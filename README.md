# 👋 Hi, I'm Sina  
*Mobile & Network Engineer • Flutter Specialist • Leading Nodia*

I build high-impact mobile apps using **Flutter**, crafting clean, scalable code in **Python**, **JavaScript**, and **C++**.  
My passion for network systems and UI elegance powers smart, efficient solutions.

🎧 Writing code to the rhythm of music — I bring innovative ideas to life at **Nodia**.

[![Wakatime](https://wakatime.com/badge/user/isina_nej.svg)](https://wakatime.com/@isina_nej)

---

## 🔧 Tech Stack & Tools

| Category         | Technologies                                |
|------------------|---------------------------------------------|
| **Programming**  | Dart, Flutter, Python, JavaScript, C++, C   |
| **Frontend**     | React, Next.js, TailwindCSS, HTML5, CSS3    |
| **Backend**      | Django, Node.js, PHP, MATLAB                 |
| **Networking**   | Mikrotik, Windows Server, Virtualization     |
| **Others**       | Git, GitHub, WordPress, ICDL                 |

---

## 🚀 Projects & Highlights

- **Awesome‑App** – Cross‑platform Flutter app for real‑time collaboration  
- **NetOptimizer** – Python/C++ tool for intelligent network performance tuning  
- [See more on my GitHub →](https://github.com/isina-nej)

---

## 📊 GitHub Activity & Badges

<div align="center">

<!-- Current Streak -->
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=isina-nej&theme=dark&hide_border=true)

<!-- Overall Stats -->
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=isina-nej&show_icons=true&count_private=true&theme=radical&hide_border=true)

<!-- Top Languages -->
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=isina-nej&layout=compact&langs_count=8&theme=radical)

<!-- Trophy Board -->
![Trophy Board](https://github-profile-trophy.vercel.app/?username=isina-nej&theme=onedark&margin-w=10&margin-h=10)

</div>

---

## 💡 Automate Updates with GitHub Actions

Add this workflow to automatically regenerate stats on your README daily:

```yaml
# .github/workflows/readme-update.yml
name: Update GitHub Stats
on:
  schedule:
    - cron: '0 0 * * *'
jobs:
  update-readme-stats:
    runs-on: ubuntu-latest
    steps:
      - uses: crazy-max/ghaction-github-stats@v2
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
      - name: Commit updated stats
        uses: stefanzweifel/git-auto-commit-action@v4
        with:
          commit_message: "chore: update GitHub stats"
