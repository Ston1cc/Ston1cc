# 💫 About Me:
🔭 Currently building [asp_programare](https://github.com/Ston1cc/asp_programare), a project I use to push my JavaScript further while shipping something real.<br>
👯 Looking to collaborate on any project that catches my interest, especially in web dev.<br>
🌱 Currently deepening my skills in JavaScript, C++, and Java.<br>
💬 Ask me about front-end builds, small business websites, or anything Java/DSA related.<br>
🌐 Portfolio: [damiansava.me](https://damiansava.me)

## 🌐 Socials:
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:damiansava6@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-damiansava.me-000000?style=for-the-badge&logo=googlechrome&logoCo
lor=white)](https://damiansava.me)

# 💻 Tech Stack:
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F
7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=whit
e)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/java-%2ge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![HTML5](https://img.shields.io/badge/html5-adge&logo=html5&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)                   ![GitHub](https://img.shields.io/badge/githu-badge&logo=github&logoColor=white)
                                                                                                                      # 🏆 Trophies:
![](https://github-profile-trophy.vercel.app/?username=Ston1cc&theme=darkhub&no-frame=true&row=1&column=6)            
# 🐍 Contribution Snake:                                                                                              ![](https://raw.githubusercontent.com/Ston1cibution-grid-snake-dark.svg)
                                                                                                                      <!---
Ston1cc/Ston1cc is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.     You can click the Preview link to take a loo
--->                                                                                                                  
Important, snake nu merge din cutie: linkul raw.githubusercontent.com/.../output/...svg cere un branch output generat de un GitHub Action. Trebuie pui workflow-ul la .github/workflows/snake.yml:

name: generate snake animation

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: Ston1cc
          outputs: |
            dist/github-contribution-grid-sn
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_T
