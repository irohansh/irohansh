<div align="center">

<img src="https://avatars.githubusercontent.com/u/167911362?v=4" width="120" style="border-radius: 50%;" alt="Rohan Sharma"/>

# Rohan Sharma

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=650&lines=Ex-Backend+Intern+%40+Cestrum;Ex-DevOps+Intern+%40+Comviva;AWS+%26+Oracle+Certified;Final+Year+CSE+%40+VIT+Chennai)](https://git.io/typing-svg)

[![Website](https://img.shields.io/badge/Portfolio-irohansh.tech-58A6FF?style=flat-square&logo=googlechrome&logoColor=white)](https://irohansh.tech)
[![GitHub](https://img.shields.io/badge/GitHub-irohansh-181717?style=flat-square&logo=github)](https://github.com/irohansh)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-rohansharma89-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/rohansharma89)
[![Location](https://img.shields.io/badge/Location-Chennai,_India-FF6B6B?style=flat-square&logo=googlemaps&logoColor=white)](https://github.com/irohansh)

</div>

---

## About

Final year Computer Science student at **VIT** and a backend engineer focused on building reliable, scalable systems — and lately, on agentic pipelines that keep humans in the loop.

Most recently a **Backend Intern at Cestrum**, where I designed REST APIs and backend services in Node.js and Express for a community platform serving 5K+ users — securing endpoints with JWT auth, Google OAuth 2.0, and role-based access control, and replacing polling with WebSockets for real-time notifications and live feed updates. Before that, a **DevOps Intern at Comviva**, working on Terraform-managed AWS infrastructure and CI/CD automation with GitHub Actions and Docker.

Certified **AWS Solutions Architect – Associate** and **Oracle Certified Professional: Java SE 17 Developer**. Comfortable across the backend stack — from schema design and query optimization to containerized deploys — with a strong emphasis on correctness, observability, and developer ergonomics.

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

### IncidentOS

An incident response platform that never acts without a human saying yes. Seven agents triage the alert, correlate state across Slack, GitHub, Prometheus and Grafana, and draft a remediation plan — which then waits at an approval gate until someone signs off.

![TypeScript](https://img.shields.io/badge/TypeScript-21262D?style=flat-square) ![Node.js](https://img.shields.io/badge/Node.js-21262D?style=flat-square) ![AI Agents](https://img.shields.io/badge/AI_Agents-21262D?style=flat-square) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-21262D?style=flat-square) ![Docker](https://img.shields.io/badge/Docker-21262D?style=flat-square)

🔵 TypeScript &nbsp; ![Stars](https://img.shields.io/github/stars/irohansh/IncidentOS?style=flat-square&label=%E2%98%86&color=0D1117&labelColor=0D1117)

[![View Code](https://img.shields.io/badge/View_Code-0D1117?style=flat-square&logo=github&logoColor=white)](https://github.com/irohansh/IncidentOS)

</td>
<td width="50%" valign="top">

### MergeMind

A pull-request reviewer that works the way a good team does. A planner agent reads the diff and delegates to security, logic and style specialists running in parallel, then a synthesiser folds everything into one clean, deduplicated review comment on the PR.

![TypeScript](https://img.shields.io/badge/TypeScript-21262D?style=flat-square) ![Node.js](https://img.shields.io/badge/Node.js-21262D?style=flat-square) ![AI Agents](https://img.shields.io/badge/AI_Agents-21262D?style=flat-square) ![GitHub API](https://img.shields.io/badge/GitHub_API-21262D?style=flat-square)

🔵 TypeScript &nbsp; ![Stars](https://img.shields.io/github/stars/irohansh/MergeMind?style=flat-square&label=%E2%98%86&color=0D1117&labelColor=0D1117)

[![View Code](https://img.shields.io/badge/View_Code-0D1117?style=flat-square&logo=github&logoColor=white)](https://github.com/irohansh/MergeMind)

</td>
</tr>
</table>

<details>
<summary><b>Engineering detail — IncidentOS</b></summary>

<br/>

| | |
|:--|:--|
| **Cost** | Cost-aware model routing across Claude Sonnet and Haiku cut per-incident inference spend, with token usage and latency captured in PostgreSQL for SQL-driven cost analysis. |
| **Integrations** | Incident state synchronized across Slack, GitHub, Prometheus and Grafana through a unified MCP-style client. |
| **Security** | HMAC-SHA256 webhook verification, strict command denylists, and remediation of critical SSRF and URL-injection vulnerabilities. |
| **Delivery** | Services containerized with Docker Compose behind an end-to-end CI/CD pipeline. |

</details>

<details>
<summary><b>Engineering detail — MergeMind</b></summary>

<br/>

| | |
|:--|:--|
| **Cost** | Model routing and file batching cut inference cost by **25–30% per review**; every agent call logged to PostgreSQL with token, latency and cost metrics. |
| **Pipeline** | Five specialised agents decompose PR diffs and review batches in parallel before a Synthesiser consolidates the output. |
| **Tooling** | Three MCP servers — GitHub, PostgreSQL and filesystem — wired into a Claude Code workflow with custom slash commands to fetch and review pull requests. |

</details>

---

## Tech Stack

### Languages

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### Backend & Frameworks

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

### Data & Infrastructure

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### Tools & Practices

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=irohansh&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github&custom_title=GitHub+Stats" height="165" alt="GitHub Stats"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=irohansh&theme=github_dark&hide_border=true&layout=compact&langs_count=8" height="165" alt="Top Languages"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=irohansh&theme=github-dark-blue&hide_border=true" alt="GitHub Streak"/>

</div>

---

## Certifications

<div align="center">

<table>
<tr>
<td align="center" width="50%">

<img src="https://images.credly.com/size/340x340/images/0e284c3f-5164-4b21-8660-0d84737941bc/image.png" height="150" alt="AWS Certified Solutions Architect – Associate"/>

<a href="https://www.credly.com/badges/391e1ab9-aee4-470d-84c0-7a483505280d"><img src="https://img.shields.io/badge/%E2%9C%93_Click_to_verify-238636?style=flat-square&labelColor=0D1117" alt="Click to verify"/></a>

</td>
<td align="center" width="50%">

<img src="https://brm-workforce.oracle.com/pdf/certview/images/OCPJSE17.png" height="150" alt="Oracle Certified Professional: Java SE 17 Developer"/>

<a href="https://catalog-education.oracle.com/ords/certview/sharebadge?id=B3AD49F22B25A11FBC9E00237AA3F0778E7CCD95D0326FEB2BE130D602BCDD5D"><img src="https://img.shields.io/badge/%E2%9C%93_Click_to_verify-238636?style=flat-square&labelColor=0D1117" alt="Click to verify"/></a>

</td>
</tr>
</table>

</div>

---

## LeetCode

<div align="center">

<a href="https://leetcode.com/irohansh" target="_blank">
  <img src="https://leetcard.jacoblin.cool/irohansh?theme=dark&font=Fira%20Code&border=0&radius=8&ext=heatmap" alt="LeetCode Stats"/>
</a>

<br/>

[![Contest Rating](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Falfa-leetcode-api.onrender.com%2Firohansh%2Fcontest&query=contestRating&suffix=%20Rating&label=Contest&color=FFA116&labelColor=1a1a1a&style=flat-square&logo=leetcode&logoColor=FFA116)](https://leetcode.com/irohansh)

</div>

---

<div align="center">

*"Build systems that outlast the sprint."*

</div>
