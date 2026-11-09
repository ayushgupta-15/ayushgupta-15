<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:00ADD8,100:7C3AED&height=200&section=header&text=Ayush%20Gupta&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%E2%80%A2%20ECE%20%40%20DTU&descAlignY=60&descSize=17&descColor=A9D4F5" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ayushgupta-sde)
[![LeetCode](https://img.shields.io/badge/LeetCode-%23FFA116.svg?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/ashg1511)
[![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)](https://ayushportfolio15.vercel.app)
[![Email](https://img.shields.io/badge/Email-%23D14836.svg?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ayushgupta.professional@gmail.com)

</div>

---

## About

Software engineer and Electronics & Communication undergrad at **Delhi Technological University** (B.Tech, batch of 2027, CGPA 8.31). I build full-stack and AI-backed products, and I'm comfortable going down to systems level: kernels, compilers, concurrency and hardware-adjacent code.

Open to software engineering internships and full-time roles. Portfolio: [ayushportfolio15.vercel.app](https://ayushportfolio15.vercel.app).

---

## Experience

- **Full Stack Developer Intern, Hibiscustech GR Pvt. Ltd.** (Jul 2025 to present). Next.js web front end and React Native screens for [PsyPlay](https://psyplay.io) (on [Google Play](https://play.google.com/store/apps/details?id=io.psyplay.app) and the [App Store](https://apps.apple.com/us/app/psyplay/id6793650706)), contributions to its Go chess-analysis service, and the company website.
- **Full Stack Development Intern, EcoXchange Pvt. Ltd.** (Jun to Aug 2026). Google OAuth single sign-on across [EcoXchange](https://www.ecoxchange.in/) and [Campus Kartt](https://www.campuskartt.in/), and build, test and deploy automation with GitHub Actions.

---

## Featured work

### Full-stack and AI products

| Project | What it is | Stack |
|---|---|---|
| [**Noesis**](https://github.com/ayushgupta-15/Noesis) · [live](https://noesis-pearl.vercel.app) | Research pipeline that plans queries, searches, extracts findings and only writes a report once the evidence is strong enough. Citations are checked in code, and progress streams to the UI. | Next.js, TypeScript, Vercel AI SDK, Exa, Neon Postgres, Zustand |
| [**JobForge AI**](https://github.com/ayushgupta-15/jobforge-ai) · [live](https://jobforge-ai.vercel.app) | Job application tracker with LLM resume scoring and semantic job matching (keyword fallback when the vector store is down), plus Redis caching and rate limiting. | Next.js, FastAPI, Go, Qdrant, Redis, Docker |
| [**TeamSync**](https://github.com/ayushgupta-15/TeamSync) · [live](https://teamsync-platform.vercel.app) | Multi-tenant B2B project management with role-based access control, JWT and Google OAuth, in an npm-workspaces monorepo. | React, Express, TypeScript, MongoDB |
| [**LuminAI Data Analyst**](https://github.com/ayushgupta-15/LuminAI-Data-Analyst) | Natural-language-to-SQL analytics assistant with streamed responses and charts. | FastAPI, LangChain, pgvector, React |
| [**CampusConnect**](https://github.com/ayushgupta-15/college-social-app) | Mobile social network for college students with real-time messaging. | React Native, Go/Gin, PostgreSQL, Redis, WebSockets |

### Systems and low-level

| Project | What it is | Stack |
|---|---|---|
| [**RV32I 5-stage CPU**](https://github.com/ayushgupta-15/rv32i-5stage-pipelined-processor) | Pipelined RISC-V core with forwarding, hazard detection and branch flushing, checked by an automated regression. | Verilog |
| [**AXI4-Lite interconnect**](https://github.com/ayushgupta-15/axi4-lite-interconnect-sv) | Multi-master interconnect with arbitration, protocol assertions and functional coverage. | SystemVerilog |
| [**UART / SPI / I²C library**](https://github.com/ayushgupta-15/serial-protocol-library) | Synthesizable controllers with self-checking testbenches and CI regression. | Verilog |
| [**EDA regression framework**](https://github.com/ayushgupta-15/eda-regression-framework) · [report](https://ayushgupta-15.github.io/eda-regression-framework/) | Parallel regression runner with pluggable simulator adapters, HTML reports and GitHub Actions CI. | Python, Icarus Verilog |
| [**Static timing analysis engine**](https://github.com/ayushgupta-15/static-timing-analysis-engine) | Timing graph, arrival/required-time propagation, slack and critical-path extraction. | C++20, GoogleTest |
| [**Circuit simulator**](https://github.com/ayushgupta-15/circuit-simulation-framework) | SPICE-style simulator using modified nodal analysis, sparse solvers and Newton-Raphson, validated against ngspice. | C++20, Eigen |
| [**RTOS kernel**](https://github.com/ayushgupta-15/RTOS-Kernel) | Preemptive kernel with O(1) priority scheduling, semaphores/mutexes, software timers and Cortex-M4 + POSIX ports. | C, QEMU |
| [**Bare-metal STM32 platform**](https://github.com/ayushgupta-15/bare-metal-firmware-platform) | Custom Cortex-M4 startup code, register layer, interrupt-driven drivers and allocator, validated in QEMU. | C |
| [**Mini compiler**](https://github.com/ayushgupta-15/mini-compiler) | Lexer, parser, AST, IR, optimization passes and a multi-file linker. | C++17 |
| [**Cache simulator**](https://github.com/ayushgupta-15/advanced-cache-simulator) | Configurable L1/L2 cache model with replacement and write policies. | C++ |
| [**Embedded racing game**](https://github.com/ayushgupta-15/embedded-racing-game) | Interrupt-driven game on a PIC16F877A with a 128x64 GLCD, EEPROM high scores and a CRC check. | PIC Assembly |

### Data and ML (selected)

| Project | What it is | Stack |
|---|---|---|
| [**Large-scale e-commerce recommender**](https://github.com/ayushgupta-15/large-scale-ecommerce-recommender) | Streamed 216M events in constant memory, built co-visitation candidates (80.8% Recall@100) and a LightGBM LambdaRank reranker. Metrics are on a 250K-session dev sample. | Python, Polars, LightGBM |
| [**Retail demand forecasting + inventory optimization**](https://github.com/ayushgupta-15/retail-demand-forecasting-inventory-optimization) | Daily demand forecasts turned into replenishment policies. | Python, XGBoost, DuckDB, Streamlit |

<details>
<summary><b>More projects</b></summary>
<br>

- [ThreadPool-Scheduler](https://github.com/ayushgupta-15/ThreadPool-Scheduler): C++ thread pool with a benchmarking harness
- [c-log-analyzer](https://github.com/ayushgupta-15/c-log-analyzer): streaming log analysis CLI in C
- [linux-virtual-sensor-driver](https://github.com/ayushgupta-15/linux-virtual-sensor-driver): Linux char device with ioctl, procfs and sysfs
- [customer-intelligence-platform](https://github.com/ayushgupta-15/customer-intelligence-platform): CLV and churn prediction with a campaign decision engine
- [glp1-part-d-launch-strategy](https://github.com/ayushgupta-15/glp1-part-d-launch-strategy): market sizing case study on CMS data
- [fintech-lending-risk-analytics](https://github.com/ayushgupta-15/fintech-lending-risk-analytics): lending portfolio and credit-risk analysis
- [store-demand-forecasting-](https://github.com/ayushgupta-15/store-demand-forecasting-): CNN-BiLSTM vs XGBoost vs ARIMA on 500 time series
- [customer-growth-analytics](https://github.com/ayushgupta-15/customer-growth-analytics): RFM, cohorts and a Streamlit dashboard
- [wobb-radar](https://github.com/ayushgupta-15/wobb-radar): influencer discovery dashboard (React, TypeScript)
- [QuoteFlow](https://github.com/ayushgupta-15/quoteflow) · [live](https://quoteflow-opal.vercel.app)

</details>

---

## Tech

![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog%20%2F%20SystemVerilog-F7DF1E?style=flat&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-black?style=flat&logo=nextdotjs)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)

---

<div align="center">


<img src="https://leetcard.jacoblin.cool/ashg1511?theme=dark&font=JetBrains%20Mono&ext=heatmap&border=0&radius=8" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,50:00ADD8,100:0D1117&height=120&section=footer" />

</div>
