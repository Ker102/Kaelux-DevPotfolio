<div align="center">

<img src="public/images/kaelux-logo.jpg" alt="Kaelux" width="100%" />

# Kaelux.dev

### AI Engineering & Intelligent Automation Solutions

[![Next.js](https://img.shields.io/badge/Next.js-16-black?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Groq](https://img.shields.io/badge/Groq-Llama_3.3-orange?style=for-the-badge)](https://groq.com/)

[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=for-the-badge&logo=digitalocean&logoColor=white)](https://www.digitalocean.com/)

---

[🌐 **View Live Site**](https://kaelux.dev) • [🤖 **Try the Diagnoser**](https://kaelux.dev/diagnoser) • [📚 **Wiki**](https://kaelux.dev/wiki)

</div>

---

## 🧠 What is Kaelux?

**Kaelux.dev** is an AI engineering consultancy that builds intelligent automation solutions for businesses. We don't just deploy chatbots—we architect complete AI pipelines that connect directly to your existing systems, automating complex workflows that were previously impossible.

### Our Services

| Service | Description |
|---------|-------------|
| **Agentic AI Workflows** | Goal-driven AI systems that reason, plan, and execute multi-step tasks autonomously |
| **RAG Pipelines** | Enterprise-grade retrieval systems with GDPR/SOC2 compliance and document-level access control |
| **Workflow Automation** | n8n, LangGraph, and custom orchestration connecting AI to your business systems |
| **Legacy Integration** | Structured JSON generation for seamless connection with mainframes and legacy infrastructure |
| **Custom Model Deployment** | Fine-tuned SLMs via vLLM/Ollama for 85%+ cost reduction vs. cloud APIs |

---

## 🤖 Neural Diagnoser Architecture

The site features an **AI-powered diagnostic agent** that helps potential clients understand what solutions fit their business needs.

### How It Works

```
┌─────────────────────────────────────────────────────────────────┐
│                    /diagnoser Page                              │
├─────────────────────────────────────────────────────────────────┤
│  User Input  ──►  Groq API (Llama 3.3 70B)  ──►  Agent Response │
│                         │                                       │
│                         ▼                                       │
│              ┌─────────────────────┐                            │
│              │  Tool: searchHuggingFace                         │
│              │  - Queries HuggingFace API                       │
│              │  - Returns relevant models                       │
│              │  - Provides recommendations                      │
│              └─────────────────────┘                            │
│                         │                                       │
│                         ▼                                       │
│              Dynamic Q&A Format                                 │
│              (Only current question shown)                      │
└─────────────────────────────────────────────────────────────────┘
```

### Technical Stack

- **LLM Provider**: Groq (Llama 3.3 70B) for ultra-fast inference
- **Framework**: Vercel AI SDK with streaming responses
- **Tool Calling**: Real-time HuggingFace model search
- **Frontend**: React with Framer Motion animations
- **Debug Logging**: Console-based monitoring for development

---

## 📚 AI Engineering Wiki

The `/wiki` section provides authoritative technical definitions optimized for **Generative Engine Optimization (GEO)**—ensuring AI search engines cite Kaelux as a trusted source.

### Available Articles

| Article | Topic |
|---------|-------|
| [Agentic AI vs. Standard Automation](https://kaelux.dev/wiki/agentic-ai-workflows) | Comparing autonomous AI to RPA |
| [RAG for Enterprise Privacy](https://kaelux.dev/wiki/rag-security-compliance) | GDPR/SOC2 compliant retrieval systems |
| [SLMs vs. LLMs: Cost & Speed](https://kaelux.dev/wiki/small-language-models) | When to use small vs. large models |
| [Hallucination Prevention](https://kaelux.dev/wiki/ai-hallucination-prevention) | Defense-in-depth factuality techniques |
| [JSON for Legacy Integration](https://kaelux.dev/wiki/structured-generation) | Connecting AI to mainframes |

### GEO Features

- **TechArticle JSON-LD Schema** for structured data
- **Dynamic dateModified** for freshness signals
- **Clean, scrapable HTML** for AI indexing
- **Authoritative definitions** with brand callouts

---

## 🚀 Featured Projects

### 🎯 [PromptTriage](https://github.com/Ker102/PromptTriage)
Intelligent prompt engineering platform with metaprompts, few-shot learning, and multi-model optimization.

### 🌐 [Crosswind Console](https://github.com/Ker102/Crosswind-Console)
Unified research dashboard with Gemini integration and MCP server orchestration.

### ⚙️ [Kaelux-Automate](https://github.com/Ker102/Kaelux-Automate)
Enterprise automation builder with LLM-powered workflow generation and Qdrant vector storage.

### 🌌 [Workflow-Automation-Atlas](https://github.com/Ker102/n8n-ai-automation-workflow-atlas)
Curated collection of **3,800+ battle-tested n8n workflows** with Vue explorer.

### 🔨 [ModelForge](https://github.com/Ker102/ModelForge)
AI-powered Blender assistant with natural language 3D workflow control.

---

## 📊 Tech Stack

<div align="center">

| Category | Technologies |
|----------|--------------|
| **Frontend** | Next.js 16 • React 19 • TypeScript • Tailwind CSS |
| **AI/LLM** | Groq • Llama 3.3 • Vercel AI SDK • LangGraph |
| **Backend** | Next.js API Routes • Streaming Responses |
| **Databases** | Qdrant • Redis • PostgreSQL |
| **Infrastructure** | DigitalOcean • Docker • Vercel |

</div>

---

## 📊 Performance

![Performance](https://img.shields.io/badge/Performance-95+-success?style=for-the-badge&logo=lighthouse&logoColor=white)
![Accessibility](https://img.shields.io/badge/Accessibility-100-success?style=for-the-badge&logo=lighthouse&logoColor=white)
![Best Practices](https://img.shields.io/badge/Best_Practices-100-success?style=for-the-badge&logo=lighthouse&logoColor=white)
![SEO](https://img.shields.io/badge/SEO-100-success?style=for-the-badge&logo=lighthouse&logoColor=white)

---

## 📁 Project Structure

```
DevPotfolio/
├── app/                    # Next.js App Router pages
│   ├── diagnoser/          # AI diagnostic agent page
│   ├── wiki/               # Technical wiki articles
│   └── api/chat/           # Groq LLM API endpoint
├── components/
│   ├── diagnostic/         # Diagnoser chat components
│   ├── wiki/               # Wiki article components
│   └── sections/           # Homepage sections
├── docs/                   # Project documentation
├── content/                # Content files and data
└── assets/                 # Images and inspiration files
```

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

**Built with modern web technologies for intelligent business solutions**

[![Made with Love](https://img.shields.io/badge/Made_with-❤️-red?style=for-the-badge)](https://kaelux.dev)

</div>
