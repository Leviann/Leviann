# Farid Ismailov

**Applied AI Engineer / LLM Engineer · QA Automation Lead / Lead SDET**  
Korolyov, Russia · Remote · UTC+3 · English C1

I build LLM applications: agents with tools, memory and retrieval, assistants for engineering and management work, and desktop tools for audio and context. I have around **2 years of applied AI/LLM practice**, backed by **12+ years in QA and test automation**.

My focus is turning an AI workflow into a system that can be used, tested and maintained: context and state, integrations, response quality, recovery after failures, and visibility into usage and cost.

[Portfolio](https://prizmed.ru) · [Telegram](https://t.me/Leviann) · [Email](mailto:faridliners@gmail.com)

## Applied AI work

### LLM agents, memory and evaluation

I develop and operate a personal R&D platform with **four AI bots sharing a Python runtime**. It brings together tool calling, MCP, conversation history, long-term memory, retrieval and multimodal inputs.

- SQLite-backed conversation and memory storage, full-text search and retrieval experiments with Chroma and Neo4j/Graphiti.
- Long-context handling with versioned summaries and source attribution.
- Durable execution records, preserved tool results and partial responses, and recovery that avoids blindly repeating an operation with an unknown outcome.
- Scenario-based evals and LLM-as-a-judge for response quality and memory retrieval, alongside tracking provider usage and cost.

### AI assistant for management work

I built an assistant to restore task context, track agreements, decisions and open questions, and prepare work summaries and meeting materials. I designed context storage, search, versioned state updates, links between conclusions and supporting evidence, and protection against concurrent changes. I use it in my QA leadership work.

### AI developer tools and agent workflows

I started building my own agent harness while working at Sber and continue to develop it across Linux, Windows and macOS. It includes reusable instructions, skills and MCP integrations, task decomposition, bounded workers, review, verification through real consumers, and continuity across long-running work.

I work with **Codex, Cursor, Claude Code and VS Code / GitHub Copilot**. At Sber, I also experimented with locally run models and IDE integration.

In my current QA role, I created and handed over an AI-assisted mobile test development workflow: test case → plan → implementation → review → execution on a real device. I trained two engineers using actual team tasks. I also developed a separate corporate QA assistant pilot for requirements, merge requests, CI and meetings; that pilot is currently paused.

### Audio and desktop applications

- **Screen Palette** — Rust/Tauri desktop AI assistant with audio and screen capture, local ASR using Nemotron/Sherpa ONNX, streaming LLM responses, context handling and MCP integration.
- **Jazz Subtitles** — TypeScript Manifest V3 extension with a local FastAPI backend for recording work sessions and subsequent ASR, screen-text extraction and LLM summaries.
- **Not So Super Whisper** — voice input for macOS and Windows using Swift/AppKit and C#/WPF, ASR APIs, insertion into the active field and local history.

## QA and engineering background

| Period | Company | Role |
|---|---|---|
| Jun 2026–present | MEDIA-100 | QA Automation Lead |
| Sep 2020–Apr 2026 | Sber | QA Lead / Lead SDET |
| Nov 2016–Aug 2020 | Wiley | Senior QA Engineer |
| Jul 2014–Nov 2016 | Exactpro Systems | QA Engineer |

At Sber, I built QA processes and automation for a B2B/B2C product, developed a Python test framework and later moved it to Kotlin, and integrated execution and reporting into CI. Over the development of the automation programme, regression coverage grew from approximately 20% to 80%, and the overall regression cycle became about three times faster.

My QA background spans API and UI automation, mobile testing, service integrations, SQL, release readiness, hiring and mentoring. It shapes how I build and evaluate AI systems today.

## Working stack

**AI / backend:** Python, asyncio, FastAPI, Pydantic, MCP, tool calling, structured outputs, RAG, retrieval, context engineering, evals, Gemini API, OpenAI-compatible APIs, OpenRouter.  
**Data / delivery:** SQLite/FTS5, PostgreSQL, Chroma, Neo4j/Graphiti, Docker, Linux, Git, GitLab CI, Jenkins.  
**QA / automation:** Python, Kotlin, Java, Playwright, Selenium, Appium, REST API, SQL, Allure.

## По-русски

Разрабатываю прикладные AI-системы: LLM-агентов, память и поиск, инструменты для разработки, аудио и рабочего контекста. Около двух лет AI/LLM-практики опираются на 12+ лет QA и автоматизации. Ищу задачи Applied AI / LLM Engineering; также открыт к QA Automation Lead / Lead SDET с инженерной работой и развитием автоматизации. Предпочитаю полностью удалённую работу из РФ.
