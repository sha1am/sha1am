<div align="center">

<img
  src="https://capsule-render.vercel.app/api?type=waving&color=0:0b0f19,45:1e3a8a,100:00ADD8&height=200&section=header&text=Shadab%20Alam&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Backend%20Engineer%20%7C%20Go%20%C2%B7%20Python%20%C2%B7%20Distributed%20Systems&descAlignY=58&descSize=16"
  width="100%"
  alt="Shadab Alam - Backend Engineer"
/>

<img
  src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&pause=1400&color=22D3EE&center=true&vCenter=true&width=780&lines=High-throughput+services+in+Go+and+Python;Kafka+pipelines+%C2%B7+Postgres+%C2%B7+Redis+%C2%B7+Elasticsearch;Concurrency%2C+latency+budgets%2C+and+failure+recovery"
  alt="Backend engineer building high-throughput services in Go and Python"
/>

<p>
  <a href="https://sha1am.github.io/portfo1io/#about">
    <img src="https://img.shields.io/badge/Portfolio-0b0f19?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="https://www.linkedin.com/in/sha1am/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:shadab.connect17@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://leetcode.com/u/sha1am/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/>
  </a>
  <a href="https://codeforces.com/profile/shalam">
    <img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=sha1am&style=for-the-badge&color=00ADD8" alt="Profile views"/>
</p>

</div>

---

## What I Build

Backend engineer at **Trademo** — API layers, ingestion pipelines, and the data plumbing behind them. Day to day that means Django and Go services talking over Kafka, backed by PostgreSQL, Redis and Elasticsearch, shipped in Docker on Kubernetes.

I care about the reasoning behind backend decisions: when a cache is a lie, why idempotency saves you at 3 a.m., what an index actually costs on write, and how a service should behave when its dependency is already down.

| Focus | What that means in practice | Tools |
|---|---|---|
| **Service APIs** | REST and microservice design, auth, validation, versioning, clean error contracts | Go `net/http`, Django REST Framework |
| **Event pipelines** | Producers and consumers, batch + streaming ingestion, idempotent processing, delivery semantics | Kafka |
| **Storage & search** | Data modelling, index and query tuning, cache invalidation strategy | PostgreSQL, MySQL, Redis, Elasticsearch |
| **Delivery** | Containerised services, CI-driven deploys, shell tooling | Docker, Kubernetes, AWS, Linux |
| **Systems work** | Concurrency primitives, profiling, latency budgets, load testing | Go, C++, Rust fundamentals |

<div align="center">
<img src="https://skillicons.dev/icons?i=go,python,django,cpp,ts,js,react,nodejs&theme=dark" alt="Languages and frameworks"/>
<br/>
<img src="https://skillicons.dev/icons?i=postgres,mysql,redis,kafka,elasticsearch,docker,kubernetes,aws,linux,git,bash&theme=dark" alt="Infrastructure and tooling"/>
</div>

---

## Currently Building

### [LogSift](https://github.com/sha1am/LogSift) &nbsp;·&nbsp; `Go` `OpenTelemetry` `Anthropic API` `React`

A log intelligence copilot — the thing I reach for when a service is misbehaving and the logs are too big to read.

```text
services --OTLP--> Go receiver --> scoring engine --> LLM reasoning --> dashboard
                   (OTel-native)   (rolling z-score)  (tool use)        (React + Recharts)
```

- **OTLP receiver** in Go, OTel-native, so anything already emitting OpenTelemetry can point at it with no shim
- **Scoring engine** computing rolling z-scores over log streams to surface what actually changed, rather than what is merely frequent
- **Reasoning layer** on the Anthropic API with tool use, turning a flagged anomaly into an explanation
- **Dashboard** in React and Recharts for the part humans need to look at

---

## Featured Projects

| Project | Stack | What It Does |
|---|---|---|
| **[TicketTrove](https://github.com/sha1am/TicketTrove)** | Go | Movie ticket booking system — seat state machine and concurrency-safe reservation logic, the interesting part being what happens when two people click the same seat. |
| **[ByteVault](https://github.com/sha1am/ByteVault)** | Django REST · React | Full-stack file management service covering upload handling, storage layout, and the whole file lifecycle. |
| **[gitRepoScanner](https://github.com/sha1am/gitRepoScanner)** | Python | Scans and reports on Git repositories — API design over an external provider, with pagination and rate-limit handling done properly. |
| **[SocialMediaAPIs_REUNION](https://github.com/sha1am/SocialMediaAPIs_REUNION)** | Python | Social-graph API set — follows, posts, and auth, built to a spec under a deadline. |

<details>
<summary><b>More projects</b></summary>

<br/>

| Project | Stack | What It Does |
|---|---|---|
| **[RecipeVaultBE](https://github.com/sha1am/RecipeVaultBE)** | Python | Recipe API backend — CRUD service with clean resource modelling and layered validation |
| **[VisualizationDashboard](https://github.com/sha1am/VisualizationDashboard)** | MERN | Analytics dashboard — aggregation queries fronted by a filterable UI |
| **[MajorProject2023](https://github.com/sha1am/MajorProject2023)** | Python · ML | Final-year project — full pipeline from data prep through model evaluation |
| **[portfo1io](https://github.com/sha1am/portfo1io)** | React | Personal portfolio site with dynamic content and light/dark themes |
| **[calarm](https://github.com/sha1am/calarm)** | Python | CLI alarm application — small, self-contained, argument parsing and scheduling |
| **[form_declutter](https://github.com/sha1am/form_declutter)** | Python | Answer bank for job applications — store canned responses once, reuse them anywhere |
| **[Twot](https://github.com/sha1am/Twot)** | Python | Twitter sentiment analysis bot |

</details>

<details>
<summary><b>Learning &amp; practice repositories</b></summary>

<br/>

| Repository | What It Covers |
|---|---|
| **[competitiveProgamming](https://github.com/sha1am/competitiveProgamming)** | C++ contest solutions — data structures, algorithms, problem archives |
| **[finalGrind](https://github.com/sha1am/finalGrind)** | Interview-prep grind: DSA, low-level design, system design notes |
| **[competiveCompanionForSafari](https://github.com/sha1am/competiveCompanionForSafari)** | Safari port of Competitive Companion — TypeScript browser extension |
| **[Python_CWM](https://github.com/sha1am/Python_CWM)** | Python fundamentals, revisited end to end |
| **[TypeScript_CWM](https://github.com/sha1am/TypeScript_CWM)** | TypeScript types, generics, and tooling |
| **[javascriptCWM](https://github.com/sha1am/javascriptCWM)** | JavaScript language deep-dive |
| **[React_CWM](https://github.com/sha1am/React_CWM)** | React components, hooks, and state patterns |
| **[NodeJS_CWM](https://github.com/sha1am/NodeJS_CWM)** | Node.js services and the surrounding ecosystem |

</details>

---

## Where I'm Heading

```go
package main

import "fmt"

type Engineer struct {
	Name    string
	Role    string
	Company string
	Next    []string
}

func main() {
	me := Engineer{
		Name:    "Shadab Alam",
		Role:    "Backend Engineer",
		Company: "Trademo",
		Next: []string{
			"deeper Go concurrency: schedulers, memory model, contention",
			"profiling and load testing as a habit, not a fire drill",
			"design reviews, service ownership, on-call reliability",
		},
	}

	fmt.Printf("%s — %s @ %s\n", me.Name, me.Role, me.Company)
	for _, goal := range me.Next {
		fmt.Println("  ->", goal)
	}
}
```

Working toward **SDE-2 scope**: owning services end to end rather than tickets, and getting sharper at the layer below the framework.

---

## Contribution Graph

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sha1am/sha1am/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sha1am/sha1am/output/snake.svg" />
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/sha1am/sha1am/output/snake.svg" />
</picture>

</div>

<!--
  Heads-up: the stats cards below are rendered by github-readme-stats.vercel.app
  and streak-stats.demolab.com. Those are free community services and they go
  down or hit GitHub API rate limits fairly often — when that happens the cards
  show a broken image or a sad face. They are kept inside a collapsed <details>
  block on purpose so a bad day for those services never breaks this page.
  The snake above is generated by your own GitHub Action and always works.

  Want the cards always-on? Fork github-readme-stats, deploy it to your own
  Vercel account with a personal access token, and swap the hostname below.
-->

<details>
<summary><b>GitHub stats</b></summary>

<br/>

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=sha1am&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub stats"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sha1am&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages"/>

<br/>

<img src="https://streak-stats.demolab.com/?user=sha1am&theme=tokyonight&hide_border=true" alt="GitHub streak"/>

</div>

</details>

---

<div align="center">

<img
  src="https://capsule-render.vercel.app/api?type=waving&color=0:00ADD8,55:1e3a8a,100:0b0f19&height=120&section=footer"
  width="100%"
  alt="Footer"
/>

</div>
