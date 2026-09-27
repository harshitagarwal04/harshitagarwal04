# Harshit Agarwal

**Founding Software Engineer · AI Engineer · Voice AI & LLM Systems**

📍 India &nbsp;|&nbsp; [Portfolio](https://portfolio-harshit-agarwal.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/harshit-713-agarwal/) · [Contact](https://portfolio-harshit-agarwal.vercel.app/#contact)

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Pipecat](https://img.shields.io/badge/-Pipecat-000000?style=flat-square)
![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square)
![Claude](https://img.shields.io/badge/-Claude-D97757?style=flat-square&logo=claude&logoColor=white)
![n8n](https://img.shields.io/badge/-n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Google Cloud](https://img.shields.io/badge/-Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

> I enjoy the whole life of a product: picturing how something should work, building it until it actually does, and then watching real people use it.
>
> Most of my work sits where AI meets production: voice agents that hold real conversations on live phone calls, and pipelines that turn stacks of documents into verified data. Building the model call is the easy part. The real work is making it fast, reliable, and something people can depend on every day.

---

## 🛰️ What I'm Working On

- 🔊 **Voice AI & document verification @ Vaanii**: founding engineer, owning the backend end to end. Built the voice pipeline (LLM + STT + TTS) and an OCR verification pipeline with **99.9% extraction accuracy** that verifies a 20-page document set in **33–40 seconds**.
- 🎯 **[HuntLoop](https://project-huntloop.vercel.app/)**: an AI-powered job application tracker. 🚧 In development.
- 📞 **Previously @ ConversAI Labs**: led the Pipecat Voice AI backend, handling **480+ calls/hour** in production (designed for 900+), with PGVector retrieval over 100+ call transcripts and n8n post-call automation.

---

## 🛠️ Tech Stack

**Languages**
`Python` `TypeScript` `JavaScript` `SQL`

**Backend & Frontend**
`FastAPI` `SQLAlchemy` `REST APIs` `Next.js` `React` `React Native`

**AI, LLM & Voice**
`OpenAI` `Claude` `Hugging Face` `RAG` `Vector Search` `Function Calling` `Pipecat` `STT / TTS` `OCR`

**Data**
`PostgreSQL` `Vector DBs`

**Automation, Cloud & Tools**
`n8n` `Google Cloud` `Cloud Run` `Azure` `Docker` `Git` `Postman`

---

## 🧭 How I Build

- **Simple first.** I start with the simplest version that works and add complexity only when real usage asks for it.
- **Ship fast, upgrade later.** A reliable, bug-free first version in users' hands beats a polished one they never get to try. After that, I keep improving it, and users get to watch it get better along the way.
- **Automate what repeats.** Automations take time to build, and an under-tested one can do more damage than the manual work it replaced. So I automate the repetitive work and do the rest by hand.

> *Every product starts as ten seconds of work. The job is to keep making it one.*

---

## 🎯 [HuntLoop](https://project-huntloop.vercel.app/): AI-Powered Job Application Tracker

`🚧 In active development · private repo · sign-in disabled for now`

HuntLoop started with a conversation. While discussing a sales CRM with my colleagues at Vaanii, a tool for tracking deals through a pipeline, I was reminded of my own job search a while back: every application tracked in a spreadsheet full of dropdowns, and the constant tiredness of keeping it up to date. That's when I realised a job search is a pipeline too, so I built one for it and put AI at the centre.

It's also **built to run at $0**. The Gmail API and Vercel hosting are free, and so are the free tiers of several LLM providers. Those free tiers come with tight rate limits, but spread across providers with failover and cooldowns, they hold up well enough to run the whole product.

HuntLoop tracks every application's status, resume version, emails, and follow-ups through a 9-stage Kanban pipeline.
- **LLM routing layer** across multiple providers, with automatic failover and rate-limit cooldowns
- **Gmail sync over OAuth**: an LLM classifies inbound email into suggested status updates and drafts follow-ups
- **Cover-letter generator** that picks the best-matching resume and flags claims the resume doesn't support

**Stack:** Next.js, TypeScript, PostgreSQL, Gmail API, LLMs

---

### 🐍 Contribution Snake
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/harshitagarwal04/harshitagarwal04/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/harshitagarwal04/harshitagarwal04/output/github-contribution-grid-snake.svg">
    <img alt="Snake animation" src="https://raw.githubusercontent.com/harshitagarwal04/harshitagarwal04/output/github-contribution-grid-snake.svg">
  </picture>
</div>
