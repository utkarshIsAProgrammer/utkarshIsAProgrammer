<div align="center">

<img src="assets/header.svg" width="100%" alt="utkarsh yadav — indiedev" />

<a href="https://github.com/utkarshIsAProgrammer">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=17&duration=2600&pause=700&color=00FF9C&center=true&vCenter=true&width=780&height=40&lines=%3E+booting+indiedev...;%3E+backend-first+%2F%2F+full-stack+%2F%2F+TypeScript+%26+Go;%3E+building+Orbit%3A+a+social+app+with+an+AI+world+inside;%3E+code+in+dark.+ship+in+silence." alt="typing" />
</a>

<br/>

<a href="https://www.linkedin.com/in/utkarsh-yadav-62b974374/"><img src="https://img.shields.io/badge/linkedin-connect-0a0e14?style=flat-square&logo=linkedin&logoColor=00ff9c&labelColor=0a0e14&color=00ff9c" /></a>
<a href="https://x.com/indieDev_ut"><img src="https://img.shields.io/badge/x-@indieDev__ut-0a0e14?style=flat-square&logo=x&logoColor=00ff9c&labelColor=0a0e14&color=00ff9c" /></a>
<a href="https://www.instagram.com/panchajanya_utkarsh/"><img src="https://img.shields.io/badge/instagram-panchajanya__utkarsh-0a0e14?style=flat-square&logo=instagram&logoColor=00ff9c&labelColor=0a0e14&color=00ff9c" /></a>
<a href="https://www.reddit.com/user/panch_ajanya"><img src="https://img.shields.io/badge/reddit-u/panch__ajanya-0a0e14?style=flat-square&logo=reddit&logoColor=00ff9c&labelColor=0a0e14&color=00ff9c" /></a>
<br/>
<img src="https://img.shields.io/github/followers/utkarshIsAProgrammer?style=flat-square&logo=github&logoColor=00d9ff&labelColor=0a0e14&color=00d9ff&label=followers" />
<img src="https://img.shields.io/github/stars/utkarshIsAProgrammer?style=flat-square&logo=github&logoColor=ffb000&labelColor=0a0e14&color=ffb000&label=stars" />
<img src="https://komarev.com/ghpvc/?username=utkarshIsAProgrammer&label=profile+views&color=00ff9c&style=flat-square" />

<img src="assets/pulse.svg" width="100%" alt="heartbeat" />

</div>

<!-- ───────────── ABOUT ───────────── -->
<img src="assets/title-about.svg" width="100%" alt="~/about $ cat readme.md" />

<div align="center">
<img src="assets/neofetch.svg" width="100%" alt="neofetch" />
</div>

```json
// now.json
{
  "building":     "Orbit — social app with a sandboxed AI world",
  "contributing": "SFCollab (volunteer, live product development)",
  "learning":     "Go  →  golang_2.0",
  "seeking":      "fresher full-stack / backend roles (campus placements)",
  "motto":        "code in dark. ship in silence."
}
```

<details>
<summary><code>$ sudo cat /etc/secrets</code> &nbsp;🔐 <i>(click to decrypt)</i></summary>

<br/>

```text
[sudo] password for indiedev: ********

 > i built my own vs code dark theme: indiedev-vibe-1
 > orbit's AI agents run on local LLMs, so the simulation costs $0 to run
 > minesmith's whole stack runs on free tiers. zero-budget shipping.
 > i go by "panchajanya" too
 > i build in public on X → @indieDev_ut
```

</details>

<br/>

<!-- ───────────── STACK ───────────── -->
<img src="assets/title-stack.svg" width="100%" alt="~/stack $ npm ls --global" />

<div align="center">
<img src="assets/stack.svg" width="100%" alt="tech stack" />
</div>

<br/>

<!-- ───────────── PROJECTS ───────────── -->
<img src="assets/title-projects.svg" width="100%" alt="~/projects $ ls -la" />

<div align="center">
<img src="assets/projects.svg" width="100%" alt="projects" />

<a href="https://github.com/utkarshIsAProgrammer/Orbit"><img src="https://img.shields.io/badge/orbit-source-0a0e14?style=flat-square&logo=github&logoColor=ffb000&labelColor=0a0e14&color=ffb000" /></a>
<a href="https://github.com/utkarshIsAProgrammer/minesmith"><img src="https://img.shields.io/badge/minesmith-source-0a0e14?style=flat-square&logo=github&logoColor=00ff9c&labelColor=0a0e14&color=00ff9c" /></a>
<a href="https://minesmith-tau.vercel.app"><img src="https://img.shields.io/badge/minesmith-live_demo-0a0e14?style=flat-square&logo=vercel&logoColor=00ff9c&labelColor=0a0e14&color=00ff9c" /></a>
<a href="https://github.com/utkarshIsAProgrammer/indieDev---vibe-1"><img src="https://img.shields.io/badge/indiedev--vibe--1-theme-0a0e14?style=flat-square&logo=visualstudiocode&logoColor=ff2e97&labelColor=0a0e14&color=ff2e97" /></a>
<a href="https://github.com/utkarshIsAProgrammer/golang_2.0"><img src="https://img.shields.io/badge/golang__2.0-notes-0a0e14?style=flat-square&logo=go&logoColor=a371f7&labelColor=0a0e14&color=a371f7" /></a>

<br/>

<img src="https://img.shields.io/github/last-commit/utkarshIsAProgrammer/Orbit?style=flat-square&label=orbit+last+commit&labelColor=0a0e14&color=ffb000" />
<img src="https://img.shields.io/github/last-commit/utkarshIsAProgrammer/minesmith?style=flat-square&label=minesmith+last+commit&labelColor=0a0e14&color=00ff9c" />
<img src="https://img.shields.io/github/last-commit/utkarshIsAProgrammer/golang_2.0?style=flat-square&label=golang_2.0+last+commit&labelColor=0a0e14&color=a371f7" />
</div>

### 🧬 orbit's AI world — architecture

```text
 ┌──────────────┐   tick   ┌────────────────────┐   prompt   ┌───────────────┐
 │  BullMQ      │ ───────► │  orbit-agent-runner│ ─────────► │  Ollama (LLM) │
 │  + Redis     │          │  (Node tick loop)  │ ◄───────── │  local model  │
 └──────────────┘          └─────────┬──────────┘   action   └───────────────┘
                                     │ per-agent JWT
                                     ▼
                          ┌────────────────────┐        ┌──────────────────────────┐
                          │   Orbit REST API   │ ─────► │ MongoDB                  │
                          │  (Node + Express)  │        │ posts · relationships ·  │
                          └─────────┬──────────┘        │ agentMemories            │
                                    │                   └──────────────────────────┘
                                    ▼
                        👥 humans can step into the AI World
```

<br/>

<!-- ───────────── STATS ───────────── -->
<img src="assets/title-stats.svg" width="100%" alt="~/stats $ git log --stat --live" />

<div align="center">

<img height="175" src="https://github-readme-stats.vercel.app/api?username=utkarshIsAProgrammer&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&bg_color=0a0e14&title_color=00ff9c&text_color=c9d1d9&icon_color=00d9ff&ring_color=00ff9c" />
<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=utkarshIsAProgrammer&layout=compact&hide_border=true&langs_count=8&bg_color=0a0e14&title_color=00ff9c&text_color=c9d1d9" />

<img src="https://streak-stats.demolab.com/?user=utkarshIsAProgrammer&hide_border=true&background=0a0e14&ring=00ff9c&fire=ffb000&currStreakNum=00ff9c&currStreakLabel=00ff9c&sideNums=00d9ff&sideLabels=8b949e&dates=6e7681" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=utkarshIsAProgrammer&bg_color=0a0e14&color=00ff9c&line=00ff9c&point=ffffff&area=true&area_color=00ff9c&hide_border=true&title_color=00ff9c&custom_title=commit.activity%28%29" width="100%" />

<img src="https://github-profile-trophy.vercel.app/?username=utkarshIsAProgrammer&theme=matrix&no-frame=true&no-bg=true&margin-w=10&row=1&column=7" />

<img src="https://raw.githubusercontent.com/utkarshIsAProgrammer/utkarshIsAProgrammer/output/github-contribution-grid-snake-dark.svg" width="100%" alt="snake eating my contributions" />

</div>

<br/>

<!-- ───────────── CONNECT ───────────── -->
<img src="assets/title-connect.svg" width="100%" alt="~/connect $ ping utkarsh" />

```bash
$ ping utkarsh
64 bytes from utkarsh: status=open_to_fresher_roles  collab=always  time=<1 day
```

<div align="center">
<a href="https://www.linkedin.com/in/utkarsh-yadav-62b974374/"><img src="https://img.shields.io/badge/💼_hire_me-linkedin-0a0e14?style=for-the-badge&labelColor=0a0e14&color=00ff9c" /></a>
<a href="https://x.com/indieDev_ut"><img src="https://img.shields.io/badge/📡_build_in_public-x-0a0e14?style=for-the-badge&labelColor=0a0e14&color=00d9ff" /></a>

<img src="assets/footer.svg" width="100%" alt="exit 0" />
</div>
