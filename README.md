# Laurent Bonnemasou

**Software, Mobile & AI Engineering Undergraduate (ADS)** · São José dos Campos, SP, Brazil  
**Languages:** English **C2 Proficient** (University of Michigan ECPE) · Portuguese (Native) · Spanish (Intermediate)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-laurent--bonnemasou-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/laurent-bonnemasou)
[![Resume EN](https://img.shields.io/badge/Resume_(EN)-PDF-2EA44F?style=flat-square&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/mlbonne/resume/main/Laurent_Bonnemasou_Resume_Tech_EN.pdf)
[![Currículo PT](https://img.shields.io/badge/Curr%C3%ADculo_(PT--BR)-PDF-007EC6?style=flat-square&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/mlbonne/resume/main/Laurent_Bonnemasou_Curriculo_Tech_PT.pdf)
[![Email](https://img.shields.io/badge/Email-mlbonnemasou%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mlbonnemasou@gmail.com)

---

### Core Stack
- **Languages:** Python · TypeScript · JavaScript (ES2023+) · SQL · Java (Android Native) · C++ (x64 / Win32)
- **AI & Agents:** LLM Tool-Use & Function Calling · RAG Pipelines · Multi-Agent Orchestration · Prompt & Context Engineering · OpenRouter / OpenAI-Compatible APIs · Tavily Search · AWS Lambda · Alexa Skills Kit (ASK SDK)
- **Mobile, Desktop & Web:** Electron · Capacitor 8 (Android APK) · Node.js · HTML5 / CSS3 · Three.js · Cloudflare Workers & KV · REST APIs
- **Quality & Tooling:** Git · GitHub Actions CI/CD · Vitest · Zod · SQLite · Linux / Bash

---

### Selected Engineering Projects

- **Beldora CB — Cross-Platform Desktop & Android Application + OTA Updater** *(JavaScript, Electron, Capacitor 8, Java, Cloudflare Workers/KV)*  
  Offline-first desktop and Android companion app featuring a custom native Java Android `WebView` print bridge (`BeldoraPrintPlugin.java`) and an automated Cloudflare Workers/KV SHA-256 delta OTA updater with transactional crash rollback.
- **[Alexa Voice AI Assistant — Real-Time LLM + Web Search RAG Skill](https://github.com/mlbonne/alexa-ai-assistant)** *(Python 3.12, AWS Lambda, ASK SDK, OpenRouter, Tavily)*  
  Production serverless voice skill routing live queries to LLMs grounded by parallel Tavily + Wikipedia search retrieval under Alexa's strict `<8s` execution budget.
- **PokeAthlon — Deterministic 60Hz TypeScript Simulation Engine** *(TypeScript, Three.js, Zod, Vitest)*  
  Monorepo architecture decoupling a deterministic 60Hz fixed-timestep physics and state-machine engine from a Three.js renderer, validated by 600+ automated head-to-head AI simulation matches in Vitest.
- **[WA2DC — Native x64 C++ LZMA Binary Delta Patcher](https://github.com/mlbonne/wa2dc-pc-port)** *(C++, Win32 API, LZMA SDK, CRC32, GitHub Actions)*  
  Zero-dependency Windows installer performing streaming CRC32 verification and LZMA decompression to reduce patch distribution payloads by **96%** (`241 MB` → `9.6 MB`).
