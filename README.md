<img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30"> Hey, I'm Udit Patidar

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=23&duration=3000&pause=1000&color=9D7BFF&center=true&vCenter=true&width=650&lines=Game+Developer+%F0%9F%8E%AE;AI+Developer+%F0%9F%A4%96;Building+ZypeCode+%E2%9A%A1;Turning+Ideas+Into+Reality+%F0%9F%9A%80" />

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&height=180&color=0:09001f,50:5522aa,100:00d4ff&text=UDIT%20PATIDAR&fontColor=ffffff&fontSize=55&animation=fadeIn&fontAlignY=55&desc=GAME%20DEV%20%7C%20AI%20DEV&descAlignY=75" width="100%" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=UditXP&label=PROFILE+VIEWS&color=8b5cf6&style=for-the-badge" />
  <img src="https://img.shields.io/github/followers/UditXP?label=FOLLOWERS&style=for-the-badge&color=06b6d4" />
</p>

⚡ Programming Languages

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,cpp,python&theme=dark" />
</p>

🛠️ Tools & Platforms

<p align="center">
  <img src="https://skillicons.dev/icons?i=git,github,vscode,unreal&theme=dark" />
</p>

🚀 Featured Projects

<table>
<tr>
<td width="50%">
<h3>⚡ ZypeCode</h3>
AI-powered coding assistant for the terminal.
<br/><br/>
<b>Status:</b> Building
</td>
<td width="50%">
<h3>🤖 AI SaaS</h3>
Developing modern AI-powered software products.
<br/><br/>
<b>Status:</b> In Progress
</td>
</tr>
</table>

📊 GitHub Statistics


## 📊 GitHub Statistics

<p align="center">
  <img height="180" src="https://github-stats-extended.vercel.app/api?username=UditXP&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=9D7BFF&icon_color=00D4FF" />

  <img height="180" src="https://github-stats-extended.vercel.app/api/top-langs/?username=UditXP&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=9D7BFF" />
</p>

🧊 3D Contribution Graph


name: GitHub-Profile-3D-Contrib

on:
  schedule:
    - cron: "0 18 * * *" 
  workflow_dispatch:

permissions:
  contents: write

jobs:
  build:
    runs-on: ubuntu-latest
    name: generate-github-profile-3d-contrib

    steps:
      - uses: actions/checkout@v5

      - uses: yoshi389111/github-profile-3d-contrib@0.6.0
        env:
          GITHUB_TOKEN: ${{ secrets.TOKEN }}
          USERNAME: ${{ github.repository_owner }}

      - name: Commit & Push
        run: |
          git config user.name Dowon-Kang
          git config user.email kd1412@hs.ac.kr
          git add -A .
          if git commit -m "generated"; then
            git push
          fi

🌌 Developer Mindset

Code. Create. Experiment. Build. Repeat.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:5522aa,100:00d4ff&height=120&section=footer&animation=fadeIn" width="100%" />
</p>

<p align="center">
  <b>Made with ❤️ by Udit Patidar | @UditXP</b>
</p>
