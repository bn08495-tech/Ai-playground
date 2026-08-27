# MindVault — AI Knowledge Notebook

Phase 2 adds an AI-ready local backend to the Phase 1 Markdown notebook.

## Features

- Dashboard and structured Markdown notebook
- Knowledge, skills, discoveries, user profile, instructions, preferences, projects, ideas, corrections, and learning history
- Teach AI workflow with classification and approval
- Local browser persistence and Markdown export/import
- AI provider proxy that keeps API keys out of frontend code
- Ollama support for local models
- OpenRouter support for cloud models
- AI actions for suggesting notebook edits

## Run

```bash
npm install
cp .env.example .env
node server.js
```

Open `http://localhost:3000`.

For Ollama, set `AI_PROVIDER=ollama` and `OLLAMA_MODEL` in `.env`.
For OpenRouter, set `AI_PROVIDER=openrouter`, `OPENROUTER_API_KEY`, and `AI_MODEL`.

Never commit `.env` or API keys.
