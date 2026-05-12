# 👋 Hi, I'm Nour Habib!

**Software Engineer** focused on building scalable backend and AI-powered systems, including production-ready applications, semantic retrieval platforms, and multi-agent workflows.

## 🛠️ Skills
**AI/Backend**
 • Python
 • FastAPI
 • Spring Boot
 • LLM pipelines
 • multi-agent workflows

 **Web**
 • Angular / React
 • TypeScript
 • Node.js / NestJS

 **Data / Infra**
 • PostgreSQL
 • pgvector
 • AWS

 **Other**
 • Swift (iOS)
 • Java (Android / DSA)
 
## 🧠 Featured Project
**Witsmith** (React, Node.js, TypeScript, Python, CLōD)
**A developer tool that gives AI coding agents persistent memory and a safety contract — so they learn from past mistakes and don't repeat them**
- Session recording: witsmith start/run/finish captures every command, its allow/ask/deny decision, stdout/stderr, git diff, and agent trace into a structured evidence bundle per session
- Self-evolving safety contract: every command is checked against AGENT_WIT.yaml via pattern matching, a SQLite verdict cache, and an LLM fallback; denied commands can permanently amend the contract so future agents are blocked instantly without an LLM call
- LLM memory generation: the evidence bundle is analysed by CLōD in parallel (summarize, infer hypotheses, extract typed claims) to produce structured memory cards tagged with source files, retrieval keywords, and stale-detection paths
- 3-tier response cache: LLM responses are cached in-memory (Map), then SQLite, then API; first session import costs ~40s, every repeat call returns in under 100ms
- Hash-based stale detection: SHA256 hashes of each memory card's source files are stored at import time; when files change, affected cards are automatically marked stale and excluded from future context
- Agent context injection: before every new session, relevant non-stale memories are retrieved by keyword search and written to .witsmith/context.md, which a Cursor rule injects into the agent's context so it's warned about past failures before writing a single line


**Situate Vancouver** (React, FastAPI, Django, OpenAI, PostgreSQL, PostGIS)
**A real-time city monitoring system that aggregates live data and enables natural language queries over city events, powering an interactive map with up-to-date incident insights**
- Monitors local traffic, accidents, constructions, natural disasters, outages, wildfires, earthquakes, border wait times
- Uses 5+ different external APIs for data
- Multi-agent AI pipeline processes and reasons over live city data to surface actionable insights from API responses
- Personalized experience with saved routes, alert subscriptions, and user-specific notification preferences
- Multi-layer caching strategy (Redis + Django ORM)
- Deployed on AWS (EC2, RDS, S3, CloudFront)
- Link: https://www.situatevancouver.com

**Notely** 
- (Angular/Ionic, NestJS, FastAPI, OpenAI, PostgreSQL)
**AI-powered knowledge and notes platform**
 - voice-to-text note creation & meeting transcription
 - embedding-based semantic search (PostgreSQL + pgvector)
 - AI chatbot assistant for searching and editing notes
 - image-to-text extraction from uploaded note photos
 - automatic summarization, categorization, and tagging
 - deployed on AWS (EC2, RDS, S3, CloudFront)
 - [Demo](https://mangotree.company/assets/demo.html)


## 🌟 Favorite Repositories
- [Notely](https://mangotree.company/assets/demo.html)
- [sports-scribe](https://github.com/nour-habib/sports-scribe)
- [verifact](https://github.com/nour-habib/verifact)

## 🌐 Connect with Me
- [LinkedIn](https://www.linkedin.com/in/nourhabib23/)

## 🎵 Fun Facts
- 🏀 Basketball fan
- 🎶 Music lover (reggaeton, hiphop, r&b, etc)
- 🍜 Always exploring new food spots (Tacos, Steak, Burgers, Fish N Chips, etc)


---

> *“Building smarter, safer and more creative tech—one line at a time.”*


