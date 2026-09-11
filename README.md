<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=58A6FF&center=true&vCenter=true&width=760&height=45&lines=AI+%26+Agent+Systems+Engineer;Always-on+voice+agents%3A+wake+word+to+tool+call;MCP+tooling+%7C+agent+evals+%7C+Claude+Code+skills;TypeScript+%7C+Python+%7C+Kotlin+%7C+C%2B%2B%2FCUDA;Ship+fast.+Verify+harder." alt="AI and Agent Systems Engineer" />

### Yash Budhia &nbsp;·&nbsp; Bengaluru, India

[![Website](https://img.shields.io/badge/yashbudhia.com-111111?style=flat-square&logo=googlechrome&logoColor=white)](https://yashbudhia.com)
[![X](https://img.shields.io/badge/@YashBudhiya-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/YashBudhiya)
<!-- TODO: paste your LinkedIn + contact email badges here:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-HANDLE)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:YOUR@EMAIL)
-->

</div>

---

## About

I build agents that have to keep working when nobody is watching — always-on, on real hardware, with real user data behind them.

- 🐈 Building **[Macy](https://heymacy.ai)** — an always-on personal assistant. A Wear OS app in Kotlin does on-device wake-word detection and vitals; a Node/TypeScript agent server handles streaming voice, long-term memory and a few hundred tool integrations; an iMessage front end carries the conversation.
- 🧪 Most interested in the unglamorous half of agents: **evaluation harnesses, MCP tooling and guardrails** — proving an agent picked the right tool, not just that it produced text.
- 🧊 When the problem is numerical, I verify before I optimise. `moldcool` checks every result against a series solution, a manufactured solution and an eigenvalue before it is allowed to report a speedup.
- 🔭 Open source: 5 open PRs upstream (python-stdnum, Razorpay Python/Node, ibantools) and 2 merged into **DiceDB**.
- 📦 Much of my recent work lives in private and client repos. What is below is the part I can show.

---

## Tech

**Agents & LLM systems**

![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-1F2937?style=flat-square)
![Agent Skills](https://img.shields.io/badge/Claude_Code_Skills-D97757?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_+_FAISS-0EA5E9?style=flat-square)
![Vosk](https://img.shields.io/badge/Vosk_wake_word-334155?style=flat-square)
![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=flat-square)
![Evals](https://img.shields.io/badge/Evals_%26_benchmarks-16A34A?style=flat-square)

**Backend & infrastructure**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Fly.io](https://img.shields.io/badge/Fly.io-8B5CF6?style=flat-square&logo=flydotio&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Apps & interfaces**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Wear OS](https://img.shields.io/badge/Wear_OS-4285F4?style=flat-square&logo=android&logoColor=white)

**Systems & numerics**

![C++](https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![OpenMP](https://img.shields.io/badge/OpenMP-1F4E79?style=flat-square)
![Eigen](https://img.shields.io/badge/Eigen-6C3483?style=flat-square)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)

---

## Flagship projects

### 🔍 [code-search-benchmark](https://github.com/yashbudhia/code-search-benchmark) &nbsp;·&nbsp; `Python`

An evaluation harness for **code-retrieval agents**. It mines ground truth straight out of git commit history — the files a commit actually touched become the answer key — then scores any retrieval agent on weighted F1 and end-to-end latency, with pluggable agents, a semantic-search baseline and optional LLM query rewriting. Dataset generation, evaluation, metrics and reporting are separate modules, so a new agent is one interface away from a full report.

### 🛡️ [solana-gasless-skill](https://github.com/yashbudhia/solana-gasless-skill) &nbsp;·&nbsp; `TypeScript` `Agent Skill`

A **Claude Code / Codex Agent Skill** that makes a coding agent an expert at gasless Solana onboarding — fee sponsorship, sponsored ATA rent, fee-in-token, session keys — *without* getting the sponsor wallet drained. The centrepiece is a threat model and a non-negotiable relayer checklist: simulation, deny-by-default instruction allowlists, balance-delta guards, compute caps, kill switch. Ships with a runnable, tested reference relayer. Built for the Solana AI Kit skill bounty after verifying no existing skill covered account abstraction.

### 🎮 [lifequest](https://github.com/yashbudhia/lifequest) &nbsp;·&nbsp; `Next.js` `MongoDB` `Claude`

A personal-finance simulator that plays like a **macro-management game**. An AI operator edits your financial records through typed, validated tools rather than free-text guesses; bank statements (PDF, CSV or image) are parsed into a categorised debrief; every mutation is audited and the latest one is reversible. It degrades cleanly — a deterministic command parser with no API keys, an in-process store with no database.

### 🧊 [moldcool](https://github.com/yashbudhia/moldcool) &nbsp;·&nbsp; `C++17` `CUDA` `OpenMP`

A 2D transient heat-conduction solver that estimates injection-mould cooling time from first principles, written to show where the handbook Fourier formula quietly fails on ribs and thick sections. Every number is checked against something exact — a series solution, a manufactured solution, the semi-discrete eigenvalue, an energy identity, Eigen's direct solver — and **convergence orders and stability limits are asserted in CI, not eyeballed**.

| | measured |
|---|---|
| Spatial / temporal order | 2.00 (slab, MMS, Crank-Nicolson) |
| CUDA vs serial CPU | **24.8×** (RTX 3060 Laptop, 2048² grid, fp64) |
| GPU ↔ CPU agreement | 1.3e-15 relative after 200 steps |
| Verification tests | 7, each with order assertions, gated in CI |

Including the results that did not flatter it: OpenMP buys only 1.3× because the kernel is memory-bound, and the shared-memory tiled kernel is *slower* than the plain one on Ampere. Both are kept, because measuring that is the point.

### 🧠 [adaptive-learn](https://github.com/yashbudhia/adaptive-learn) &nbsp;·&nbsp; `FastAPI` `FAISS` `Redis`

An adaptive boss-behaviour system for games: a RAG pipeline over FAISS and embeddings retrieves context, the boss acts, and outcomes are fed back so behaviour improves across encounters. Multi-game vocabularies, JWT auth with encrypted credential storage, Postgres and Redis behind FastAPI.

### 📷 [emmetra](https://github.com/yashbudhia/emmetra) &nbsp;·&nbsp; `Python` `Deep learning`

An image-signal-processing pipeline built end to end — demosaic, white balance, denoise, sharpen — plus a deep-learning denoiser and an LDR→HDR converter, with acutance and SNR measurements comparing the classical path against the learned one.

---

## Open source

| PR | Repository | What it does | Status |
|---|---|---|---|
| [#511](https://github.com/arthurdejong/python-stdnum/pull/511) | `arthurdejong/python-stdnum` | Add IFSC (Indian Financial System Code) bank-branch validation | 🟢 Open |
| [#341](https://github.com/razorpay/razorpay-python/pull/341) | `razorpay/razorpay-python` | `close()` and context-manager support on the client | 🟢 Open |
| [#342](https://github.com/razorpay/razorpay-python/pull/342) | `razorpay/razorpay-python` | Fix `UnboundLocalError` when package metadata is missing | 🟢 Open |
| [#489](https://github.com/razorpay/razorpay-node/pull/489) | `razorpay/razorpay-node` | Support `expand[]` in `orders.fetch`, encoded the way the API expects | 🟢 Open |
| [#692](https://github.com/Simplify/ibantools/pull/692) | `Simplify/ibantools` | Fix account-number extraction for IE, PT, ME, MU and SC | 🟢 Open |
| [#23](https://github.com/dicedb/playground-mono/pull/23) | `dicedb/playground-mono` | Blacklist unsafe commands in the playground | ✅ Merged |
| [#19](https://github.com/dicedb/alloy/pull/19) | `dicedb/alloy` | The same blacklist enforced at the engine boundary | ✅ Merged |

---

<details>
<summary><b>🔒 Private &amp; client work</b> &nbsp;— <i>click to expand</i></summary>

<br>

Not public, but the bulk of what I have been building. Happy to walk through any of them.

| Project | What it is | Stack |
|---|---|---|
| **Macy** ([heymacy.ai](https://heymacy.ai)) | Always-on personal assistant: on-device wake word and vitals on a Wear OS watch, streaming voice through a cloud agent, long-term memory, hundreds of tool integrations, iMessage front end | Kotlin · Wear OS · Node/TS · MongoDB Atlas · Cloudflare |
| **InterviewCracker** | Desktop interview copilot — screen and audio capture feeding a live reasoning loop, with a stealth window mode | Electron · Node/TS · Fly.io · Claude |
| **whydunit** | Agentic battery forensics for Android: evidence-cited power-drain investigation from batterystats and bugreports, with a reproducible seeded eval | Python · agent tooling |
| **job-agent** | Autonomous job-hunt agent: sources roles, finds and verifies contact emails through a tool marketplace, drafts and sends outreach under a send budget | TypeScript · Claude · tool APIs |
| **ai-music-factory** | Multi-channel AI music pipeline — generation, mastering, thumbnail art and scheduled YouTube publishing, one YAML file per channel | Node/TS · Fly.io · generative audio |
| **people-finder-bot** | Telegram bot running a Claude-driven research loop over email-finder and LinkedIn tools to locate a person's contacts and draft outreach | Node/TS · Fly.io · Claude |
| **dubbing-pipeline** | Any language → Hinglish dubbing that preserves music, SFX and laughter underneath the dialogue | Python · ASR/TTS |

</details>

<details>
<summary><b>📚 More public repos</b> &nbsp;— <i>click to expand</i></summary>

<br>

| Repo | What it is |
|---|---|
| [3-tier-rule-engine](https://github.com/yashbudhia/3-tier-rule-engine) | Rule engine over an AST — UI, API and data tiers — deciding eligibility from age, department, income and spend |
| [Realtime-Weather-Monitoring](https://github.com/yashbudhia/Realtime-Weather-Monitoring) | Real-time weather stream turned into rollups, aggregates and threshold alerts off the OpenWeatherMap API |
| [Rubics-Cube-Solver](https://github.com/yashbudhia/Rubics-Cube-Solver) | 3×3 and 4×4 solver with multiple algorithms and a visualiser |
| [AI-sentiment-analysis](https://github.com/yashbudhia/AI-sentiment-analysis) | Upload a CSV of reviews, get the dominant customer sentiment out of an LLM |
| [Image-Compressor-by-color-quantization](https://github.com/yashbudhia/Image-Compressor-by-color-quantization) | K-means colour quantisation as a posterise-and-compress pipeline |
| [Quadruped_bot_with_object_tracking](https://github.com/yashbudhia/Quadruped_bot_with_object_tracking) | Four-legged robot with vision-based object tracking |
| [contra-remake-in-python](https://github.com/yashbudhia/contra-remake-in-python) | Contra-style run-and-gun mechanics written from scratch |
| [Amazon-Price-Tracker](https://github.com/yashbudhia/Amazon-Price-Tracker) | Scraper on a cron that tracks product prices and alerts on drops |
| [skillpath-framer-assignment](https://github.com/yashbudhia/skillpath-framer-assignment) | Framer site wired to a live course-catalogue API |
| [DSA](https://github.com/yashbudhia/DSA) | Data-structures and algorithms practice, in C |

</details>

---

## GitHub

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=yashbudhia&theme=transparent" alt="Profile summary" width="96%" />

<img height="190" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=yashbudhia&theme=transparent" alt="Commit stats" />
<img height="190" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=yashbudhia&theme=transparent" alt="Most-committed languages" />
<img height="190" src="https://streak-stats.demolab.com/?user=yashbudhia&theme=transparent&hide_border=true&date_format=j%20M%5B%20Y%5D" alt="Contribution streak" />

<br><br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yashbudhia/yashbudhia/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/yashbudhia/yashbudhia/output/github-snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/yashbudhia/yashbudhia/output/github-snake.svg" width="96%" />
</picture>

</div>

---

<div align="center">

<sub>Alt account: <a href="https://github.com/yashbudhia13">@yashbudhia13</a> &nbsp;·&nbsp; Open to AI and agent engineering work — <a href="https://yashbudhia.com">yashbudhia.com</a></sub>

</div>
