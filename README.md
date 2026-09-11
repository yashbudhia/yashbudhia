<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=58A6FF&center=true&vCenter=true&width=760&height=45&lines=AI+and+Agent+Systems+Engineer;Always-on+voice+agents%2C+wake+word+to+tool+call;MCP+tooling%2C+agent+evals%2C+Claude+Code+skills;TypeScript+%7C+Python+%7C+Kotlin+%7C+C%2B%2B%2FCUDA;Ship+fast.+Verify+harder." alt="AI and Agent Systems Engineer" />

### Yash Budhia, Bengaluru

[![Website](https://img.shields.io/badge/yashbudhia.com-111111?style=flat-square&logo=googlechrome&logoColor=white)](https://yashbudhia.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yash-budhia-78643b272)
[![X](https://img.shields.io/badge/@YashBudhiya-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/YashBudhiya)

</div>

---

## About

I build agents that have to keep running when nobody is watching. Always on, on real devices, with real user data behind them.

- Building [Macy](https://heymacy.ai), an always on personal assistant. A Wear OS app in Kotlin does wake word detection and vitals on device. A Node/TypeScript server runs the agent itself: streaming voice, long term memory, a few hundred tool integrations. iMessage is the front end.
- The part of agent work I care about most is the boring part. Evals, MCP tooling, guardrails. Proving the agent picked the right tool, not just that it produced text.
- On numerical work I verify first and optimise after. moldcool checks every result against a series solution, a manufactured solution and an eigenvalue before it is allowed to report a speedup.
- Open source: 5 open PRs upstream (python-stdnum, Razorpay Python and Node, ibantools) and 2 merged into DiceDB.
- A lot of my recent work sits in private and client repos. What is below is the part I can show.

---

## Tech

**Agents and LLM systems**

![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-1F2937?style=flat-square)
![Agent Skills](https://img.shields.io/badge/Claude_Code_Skills-D97757?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_+_FAISS-0EA5E9?style=flat-square)
![Vosk](https://img.shields.io/badge/Vosk_wake_word-334155?style=flat-square)
![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=flat-square)
![Evals](https://img.shields.io/badge/Evals_and_benchmarks-16A34A?style=flat-square)

**Backend and infrastructure**

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

**Apps and interfaces**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Wear OS](https://img.shields.io/badge/Wear_OS-4285F4?style=flat-square&logo=android&logoColor=white)

**Systems and numerics**

![C++](https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![OpenMP](https://img.shields.io/badge/OpenMP-1F4E79?style=flat-square)
![Eigen](https://img.shields.io/badge/Eigen-6C3483?style=flat-square)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)

---

## Projects

### [code-search-benchmark](https://github.com/yashbudhia/code-search-benchmark) &nbsp; `Python`

A benchmark for code search agents. It builds the test set out of git history, so the files a commit actually touched become the answer key, and then scores any retrieval agent on weighted F1 and end to end latency. Agents are pluggable, there is a semantic search baseline to compare against, and LLM query rewriting is optional. Dataset generation, evaluation, metrics and reporting are separate modules, so plugging in a new agent means implementing one interface.

### [solana-gasless-skill](https://github.com/yashbudhia/solana-gasless-skill) &nbsp; `TypeScript` `Agent Skill`

A Claude Code / Codex Agent Skill that teaches a coding agent to build gasless Solana onboarding without getting the sponsor wallet drained. It covers fee sponsorship, paying ATA rent for users, fee in token, and session keys. The main file is a threat model plus a checklist for the relayer: simulation, deny by default instruction allowlists, balance delta guards, compute caps, rate limiting, kill switch. Ships with a reference relayer that runs and has tests. Written for the Solana AI Kit skill bounty, after checking that nothing in the kit covered account abstraction.

### [lifequest](https://github.com/yashbudhia/lifequest) &nbsp; `Next.js` `MongoDB` `Claude`

A personal finance app that plays like a management game. The AI operator edits your records through typed, validated tools instead of guessing at free text. Bank statements (PDF, CSV or image) get parsed into a spending breakdown. Every change is logged and the last one can be undone. It degrades cleanly: a deterministic command parser when there are no API keys, an in process store when there is no database.

### [moldcool](https://github.com/yashbudhia/moldcool) &nbsp; `C++17` `CUDA` `OpenMP`

A 2D transient heat conduction solver that works out injection mould cooling time from first principles. The handbook Fourier formula is fine for a flat plate and wrong for ribs and thick sections, and this shows exactly where. Every number is checked against something exact: a series solution, a manufactured solution, the semi discrete eigenvalue, an energy identity, Eigen's direct solver. Convergence orders and stability limits are asserted in CI instead of eyeballed.

| | measured |
|---|---|
| Spatial and temporal order | 2.00 (slab, MMS, Crank-Nicolson) |
| CUDA vs serial CPU | **24.8x** (RTX 3060 Laptop, 2048² grid, fp64) |
| GPU vs CPU agreement | 1.3e-15 relative after 200 steps |
| Verification tests | 7, each asserting orders, gated in CI |

The results that were not flattering are in there too. OpenMP only gets 1.3x because the kernel is memory bound, and the shared memory tiled CUDA kernel is slower than the plain one on Ampere. Both kernels are kept.

### [adaptive-learn](https://github.com/yashbudhia/adaptive-learn) &nbsp; `FastAPI` `FAISS` `Redis`

An adaptive boss behaviour system for games. A RAG loop over FAISS and embeddings pulls context, the boss acts, and the outcome feeds back so it plays differently next time. Handles multiple games with their own vocabularies. FastAPI with Postgres and Redis, JWT auth, encrypted credential storage.

### [emmetra](https://github.com/yashbudhia/emmetra) &nbsp; `Python` `Deep learning`

An image signal processing pipeline written end to end: demosaic, white balance, denoise, sharpen. Plus a deep learning denoiser and an LDR to HDR converter, with acutance and SNR numbers comparing the classical path against the learned one.

---

## Open source

| PR | Repository | What it does | Status |
|---|---|---|---|
| [#511](https://github.com/arthurdejong/python-stdnum/pull/511) | `arthurdejong/python-stdnum` | Add IFSC (Indian Financial System Code) bank branch validation | Open |
| [#341](https://github.com/razorpay/razorpay-python/pull/341) | `razorpay/razorpay-python` | `close()` and context manager support on the client | Open |
| [#342](https://github.com/razorpay/razorpay-python/pull/342) | `razorpay/razorpay-python` | Fix `UnboundLocalError` when package metadata is missing | Open |
| [#489](https://github.com/razorpay/razorpay-node/pull/489) | `razorpay/razorpay-node` | Support `expand[]` in `orders.fetch`, encoded the way the API expects | Open |
| [#692](https://github.com/Simplify/ibantools/pull/692) | `Simplify/ibantools` | Fix account number extraction for IE, PT, ME, MU and SC | Open |
| [#23](https://github.com/dicedb/playground-mono/pull/23) | `dicedb/playground-mono` | Blacklist unsafe commands in the playground | Merged |
| [#19](https://github.com/dicedb/alloy/pull/19) | `dicedb/alloy` | Same blacklist enforced at the engine boundary | Merged |

---

<details>
<summary><b>Private and client work</b> &nbsp; <i>(click to expand)</i></summary>

<br>

These are not public, but they are most of what I have been building. Happy to walk through any of them.

| Project | What it is | Stack |
|---|---|---|
| **Macy** ([heymacy.ai](https://heymacy.ai)) | Always on personal assistant. Wake word and vitals run on a Wear OS watch, voice streams through a cloud agent with long term memory and a few hundred tool integrations, iMessage is the front end | Kotlin, Wear OS, Node/TS, MongoDB Atlas, Cloudflare |
| **InterviewCracker** | Desktop interview copilot. Screen and audio capture feed a live reasoning loop, with a stealth window mode | Electron, Node/TS, Fly.io, Claude |
| **whydunit** | Battery forensics agent for Android. Investigates power drain from batterystats and bugreports and cites its evidence, with a reproducible seeded eval | Python, agent tooling |
| **job-agent** | Autonomous job hunt agent. Sources roles, finds and verifies contact emails through a tool marketplace, drafts and sends outreach under a send budget | TypeScript, Claude, tool APIs |
| **ai-music-factory** | Multi channel AI music pipeline. Generation, mastering, thumbnail art and scheduled YouTube publishing, one YAML file per channel | Node/TS, Fly.io, generative audio |
| **people-finder-bot** | Telegram bot that runs a Claude research loop over email finder and LinkedIn tools to find someone's contacts and draft outreach | Node/TS, Fly.io, Claude |
| **dubbing-pipeline** | Any language to Hinglish dubbing that keeps the music, SFX and laughter under the dialogue | Python, ASR/TTS |

</details>

<details>
<summary><b>More public repos</b> &nbsp; <i>(click to expand)</i></summary>

<br>

| Repo | What it is |
|---|---|
| [3-tier-rule-engine](https://github.com/yashbudhia/3-tier-rule-engine) | Rule engine over an AST, split into UI, API and data tiers, deciding eligibility from age, department, income and spend |
| [Realtime-Weather-Monitoring](https://github.com/yashbudhia/Realtime-Weather-Monitoring) | Live weather stream from the OpenWeatherMap API turned into rollups, daily aggregates and threshold alerts |
| [Rubics-Cube-Solver](https://github.com/yashbudhia/Rubics-Cube-Solver) | 3x3 and 4x4 solver with multiple algorithms and a visualiser |
| [AI-sentiment-analysis](https://github.com/yashbudhia/AI-sentiment-analysis) | Upload a CSV of reviews and an LLM reports the dominant sentiment across them |
| [Image-Compressor-by-color-quantization](https://github.com/yashbudhia/Image-Compressor-by-color-quantization) | K-means colour quantisation, a posterise effect that also cuts file size |
| [Quadruped_bot_with_object_tracking](https://github.com/yashbudhia/Quadruped_bot_with_object_tracking) | Four legged walking robot with vision based object tracking |
| [contra-remake-in-python](https://github.com/yashbudhia/contra-remake-in-python) | Contra style run and gun mechanics written from scratch |
| [Amazon-Price-Tracker](https://github.com/yashbudhia/Amazon-Price-Tracker) | Scraper on a cron that tracks product prices and alerts on drops |
| [skillpath-framer-assignment](https://github.com/yashbudhia/skillpath-framer-assignment) | Framer site wired to a live course catalogue API |
| [DSA](https://github.com/yashbudhia/DSA) | Data structures and algorithms practice, in C |

</details>

---

## GitHub

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=yashbudhia&theme=transparent" alt="Profile summary" width="96%" />

<img height="190" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=yashbudhia&theme=transparent" alt="Commit stats" />
<img height="190" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=yashbudhia&theme=transparent" alt="Most committed languages" />
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

<sub>Alt account <a href="https://github.com/yashbudhia13">@yashbudhia13</a>. Open to AI and agent engineering work, reach me at <a href="https://yashbudhia.com">yashbudhia.com</a>.</sub>

</div>
