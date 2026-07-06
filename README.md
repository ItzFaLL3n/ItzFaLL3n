<div align="center">

```
~/github/ItzFaLL3n $ whoami
```

# FaLL3n
**Backend Developer · Cloud Security · Container Alchemist**

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&duration=3000&pause=1200&color=E74C3C&background=0D0505&center=true&vCenter=true&width=650&lines=Securing+containers+one+CVE+at+a+time;Shipping+AI-native+automation+with+Claude+%2B+n8n;Infra+by+day%2C+threat+modeling+by+night)](https://git.io/typing-svg)

<br/>

[![GitHub](https://img.shields.io/badge/github-ItzFaLL3n-e74c3c?style=flat-square&logo=github&logoColor=white&labelColor=0d0505)](https://github.com/ItzFaLL3n)
[![Discord](https://img.shields.io/badge/discord-join-e74c3c?style=flat-square&logo=discord&logoColor=white&labelColor=0d0505)](https://discord.gg/E834WAy32g)
[![Status](https://img.shields.io/badge/status-building-e74c3c?style=flat-square&labelColor=0d0505)](#)
![Views](https://komarev.com/ghpvc/?username=FaLL3nWhizzy&style=flat-square&color=e74c3c&labelColor=0d0505&label=views)

</div>
<br/>

---

### `01` — init

```yaml
name:       FaLL3n
location:   "somewhere in the cloud"
focus:      Cloud Security · Backend Architecture · Containers · AI-Driven Automation
building:   Secure, scalable systems — one container at a time.
ai_ops:     Claude as the reasoning layer, n8n as the nervous system.
fun_fact:   "I don't patch vulnerabilities. I have long talks with them."
```

---

### `02` — arsenal

<div align="center">

**Languages**
<br/>
<img src="https://skillicons.dev/icons?i=ts,py,rust,js,bash,lua,html,css&theme=dark" />

<br/><br/>

**Cloud & Infrastructure**
<br/>
<img src="https://skillicons.dev/icons?i=aws,gcp,azure,terraform,linux,nginx,git,github&theme=dark" />

<br/><br/>

**Containers & Orchestration**
<br/>
<img src="https://skillicons.dev/icons?i=docker,kubernetes&theme=dark" />

<br/><br/>

**AI & Automation**
<br/>
<img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=fff" />
<img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=fff" />

</div>

> Claude reasons over the workflow. n8n orchestrates it. Together they replace a good chunk of what used to be manual triage — webhook events get classified, enriched, and routed before a human ever sees them.

---

### `03` — pipeline

The shape of most things I ship right now: an event comes in, an agent decides what it means, and only the ambiguous cases reach a person.

```mermaid
flowchart LR
    A["Webhook / Cron Trigger"] --> B["n8n Workflow Engine"]
    B --> C{{"Claude Agent"}}
    C -- "safe / routine" --> D["Automated Action"]
    C -- "anomalous / high-risk" --> E["Human Review Queue"]
    D --> F[("Deploy — Docker / K8s")]
    D --> G[("Alert — Slack / Discord")]
    E --> H["Security Analyst"]

    classDef claude fill:#0d0505,stroke:#e74c3c,color:#fff,stroke-width:2px
    class C claude
```

Same pattern, different faces: CI/CD gatekeeping, log-anomaly triage, or a WhatsApp/Slack bot that only escalates when the model isn't confident.

---
```
### `04` — metrics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=ItzFaLL3n&show_icons=true&hide_border=true&title_color=e74c3c&icon_color=e74c3c&text_color=ffffff&bg_color=0d0505" width="49%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ItzFaLL3n&layout=compact&hide_border=true&title_color=e74c3c&text_color=ffffff&bg_color=0d0505" width="30%" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=ItzFaLL3n&hide_border=true&background=0D0505&ring=E74C3C&fire=E74C3C&currStreakLabel=E74C3C&sideLabels=FFFFFF&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=888888" width="60%" />

</div>

<sub>If your GitHub handle isn't exactly `ItzFaLL3n`, swap it into the three URLs above.</sub>

<details>
<summary><strong>Advanced — contribution snake animation</strong></summary>
<br/>

GitHub Actions can generate an animated "snake" that eats through your contribution graph. Add this workflow at `.github/workflows/snake.yml`:

```yaml
name: generate snake
on:
  schedule:
    - cron: "0 0 * * *"
  push:
    branches:
      - main
  workflow_dispatch: {}

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/snake.svg
            dist/snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

Then embed it once the `output` branch exists:




</details>

---
```
### `05` — connect

<div align="center">

[![GitHub](https://img.shields.io/badge/github-ItzFaLL3n-e74c3c?style=for-the-badge&logo=github&logoColor=white&labelColor=0d0505)](https://github.com/ItzFaLL3n)
[![Discord](https://img.shields.io/badge/discord-join_server-e74c3c?style=for-the-badge&logo=discord&logoColor=white&labelColor=0d0505)](https://discord.gg/E834WAy32g)

<sub>Open to conversations about container security, backend architecture, and AI-driven ops.</sub>

</div>

<div align="center">
<sub>© FaLL3n — patched systems, unpatched curiosity.</sub>
</div></tr>
</table>

</div>

---

### `03` — tools & infrastructure

<div align="center">

<table>
<tr>
<td align="center" width="80"><img src="https://skillicons.dev/icons?i=docker&theme=dark" width="36" height="36" alt="Docker"/><br/><sub>Docker</sub></td>
<td align="center" width="80"><img src="https://skillicons.dev/icons?i=kubernetes&theme=dark" width="36" height="36" alt="Kubernetes"/><br/><sub>Kubernetes</sub></td>
<td align="center" width="80"><img src="https://skillicons.dev/icons?i=aws&theme=dark" width="36" height="36" alt="AWS"/><br/><sub>AWS</sub></td>
<td align="center" width="80"><img src="https://skillicons.dev/icons?i=nginx&theme=dark" width="36" height="36" alt="Nginx"/><br/><sub>Nginx</sub></td>
<td align="center" width="80"><img src="https://skillicons.dev/icons?i=nodejs&theme=dark" width="36" height="36" alt="Node.js"/><br/><sub>Node.js</sub></td>
<td align="center" width="80"><img src="https://skillicons.dev/icons?i=mongodb&theme=dark" width="36" height="36" alt="MongoDB"/><br/><sub>MongoDB</sub></td>
<td align="center" width="80"><img src="https://skillicons.dev/icons?i=mysql&theme=dark" width="36" height="36" alt="MySQL"/><br/><sub>MySQL</sub></td>
<td align="center" width="80"><img src="https://skillicons.dev/icons?i=git&theme=dark" width="36" height="36" alt="Git"/><br/><sub>Git</sub></td>
<td align="center" width="80"><img src="https://skillicons.dev/icons?i=neovim&theme=dark" width="36" height="36" alt="Neovim"/><br/><sub>Neovim</sub></td>
</tr>
</table>

</div>

---

### `04` — stack

| Cloud & Security | Backend & DevOps |
|---|---|
| AWS — IAM, GuardDuty, CloudTrail | Node.js · Prisma · REST APIs |
| Container Security & Hardening | Docker Compose & K8s Manifests |
| Secrets Management | Helm Charts · Terraform IaC |
| Threat Modeling | CI/CD Pipelines |
| Network Policy & Zero Trust | AWS ECR / ECS |

---

### `05` — AI-assisted development

<div align="center">

<table>
<tr>
<td align="center" width="110">
<img src="https://img.shields.io/badge/Claude_Code-c0392b?style=for-the-badge&logo=anthropic&logoColor=white" height="24" alt="Claude Code"/><br/>
<sub>Agentic coding</sub>
</td>
<td align="center" width="110">
<img src="https://img.shields.io/badge/Copilot-161b22?style=for-the-badge&logo=githubcopilot&logoColor=white" height="24" alt="Copilot"/><br/>
<sub>Code completion</sub>
</td>
<td align="center" width="110">
<img src="https://img.shields.io/badge/Cursor-1a1a2e?style=for-the-badge&logo=cursor&logoColor=white" height="24" alt="Cursor"/><br/>
<sub>AI-first editor</sub>
</td>
<td align="center" width="110">
<img src="https://img.shields.io/badge/v0-000000?style=for-the-badge&logo=vercel&logoColor=white" height="24" alt="v0"/><br/>
<sub>UI generation</sub>
</td>
</tr>
<tr>
<td align="center" width="110">
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" height="24" alt="Gemini"/><br/>
<sub>Research</sub>
</td>
<td align="center" width="110">
<img src="https://img.shields.io/badge/Windsurf-0077cc?style=for-the-badge&logo=codeium&logoColor=white" height="24" alt="Windsurf"/><br/>
<sub>AI IDE</sub>
</td>
<td align="center" width="110">
<img src="https://img.shields.io/badge/ChatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white" height="24" alt="ChatGPT"/><br/>
<sub>Ideation</sub>
</td>
<td align="center" width="110">
<img src="https://img.shields.io/badge/Perplexity-1e293b?style=for-the-badge&logo=perplexity&logoColor=white" height="24" alt="Perplexity"/><br/>
<sub>AI search</sub>
</td>
</tr>
</table>

</div>

---

### `06` — github stats

<div align="center">

<img src="https://github-readme-stats-fall3nwhizzy.vercel.app/api?username=ItzFaLL3n&count_private=true&show_icons=true&hide_border=true&theme=github_dark&title_color=e74c3c&icon_color=e74c3c&text_color=7a5050&bg_color=080808&ring_color=c0392b&include_all_commits=true&card_width=440" height="165" alt="GitHub Stats"/>

<img src="https://github-readme-stats-fall3nwhizzy.vercel.app/api/top-langs/?username=ItzFaLL3n&layout=compact&hide_border=true&theme=github_dark&title_color=e74c3c&text_color=7a5050&bg_color=080808&langs_count=6&card_width=440" height="165" alt="Top Languages"/>

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=ItzFaLL3n&hide_border=true&background=080808&stroke=1e0a0a&ring=c0392b&fire=e74c3c&currStreakLabel=e74c3c&sideLabels=4a3030&dates=2e1818&currStreakNum=f0e0e0&sideNums=c8a8a8" height="130" alt="Streak Stats"/>


</div>

![snake](https://raw.githubusercontent.com/ItzFaLL3n/ItzFaLL3n/output/snake-dark.svg)

---

<div align="center">

<sub>built with claude code & caffeine · secured before shipped</sub>

<br/>

[![github](https://img.shields.io/badge/github-follow-e74c3c?style=flat-square&logo=github&logoColor=white&labelColor=0d0505)](https://github.com/FaLL3nWhizzy)
[![discord](https://img.shields.io/badge/discord-join-e74c3c?style=flat-square&logo=discord&logoColor=white&labelColor=0d0505)](https://discord.gg/E834WAy32g)

</div>
