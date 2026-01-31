<div align="center">

**AI-powered productivity assistant for your desktop**

[![Electron](https://img.shields.io/badge/Electron-30-47848F?logo=electron)](https://www.electronjs.org/)
[![React](https://img.shields.io/badge/React-18-61DAFB?logo=react)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript)](https://www.typescriptlang.org/)
[![Bun](https://img.shields.io/badge/Bun-Backend-F9F1E1?logo=bun)](https://bun.sh/)
[![Elysia](https://img.shields.io/badge/Elysia-API-8B5CF6)](https://elysiajs.com/)

</div>

---

Elefanta is a desktop app that combines AI chat, semantic file search, calendar management, and proactive screen analysis. It learns from your files, captures context from your screen, and helps you stay organized—all from a sleek, always-available launcher.

## ✨ Features

| Feature               | Description                                                                                                                          |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| **🤖 AI Chat**        | Agentic assistant with tools for calendar, file search, and actions. Supports multiple models (Gemini, Cohere, Mistral, OpenRouter). |
| **🔍 File Search**    | Semantic search across local and cloud documents—PDFs, Office files, images, and more.                                               |
| **📸 Think For Me**   | Captures your screen and proactively analyzes tasks, meetings, and info—creates calendar events, searches files, takes actions.      |
| **📅 Calendar**       | Create, edit, delete events with recurrence (daily, weekly, monthly). Day and month views.                                           |
| **👁️ GodsEye**        | Periodic screen captures for context. View logs and filter by collaborator.                                                          |
| **📚 Knowledge Base** | Persistent facts and preferences the AI remembers across sessions.                                                                   |
| **🤝 Collaborations** | Invite collaborators, share context, and see their GodsEye logs.                                                                     |
| **⚡ Smart Launcher** | AI-powered suggestions based on your query.                                                                                          |

---

## Download

Get the latest Windows build from the [Releases](../../releases) page.

- **Stable** — Recommended for most users
- **Pre-release** — Early builds; use for testing or bleeding-edge features

The app supports **auto-updates** via electron-updater; you’ll be prompted when a new version is available (or use **Settings → Updates** to check manually).

---

## Forum & Community

- **Questions, feedback, and feature ideas:** [GitHub Discussions](../../discussions)
- **Bugs and issues:** [Issues](../../issues)

Use Discussions for general talk, tips, and requests; use Issues for reproducible bugs and concrete feature requests.

_Maintainers: enable **GitHub Discussions** under **Settings → General → Discussions** to use this repo as the community forum._

---

## Feature Overview

### Authentication

- Sign in / sign up with **email & password**
- **Google Sign-in**
- Session handling with **refresh tokens**

### AI & Search

- **File Search** — Semantic search across local and cloud documents
  - Search in uploaded files (PDF, Office, images, videos, audio, code)
  - View/preview in app (e.g. Google Docs viewer for Office files)
  - Filter by file type
- **AI Chat** — Agent assistant
  - Manages calendar, searches files, runs actions
  - Multi-model (Gemini, Cohere, Mistral, OpenRouter)
  - Chat history and persistence
  - Suggested prompts (e.g. “Explain like I’m 5”, “@screen What’s on my screen?”)
  - Knowledge base integration
- **Think For Me** — Proactive screen-based assistant
  - Captures a screenshot of the current screen
  - Analyzes tasks, meetings, and other information
  - Can create calendar events, search files, and take related actions
  - Default: _“Analyze my current screen. If you see any tasks, meetings, or information that should be saved, please take the appropriate agentic actions.”_

### Knowledge Base

- Stores facts and preferences used by the AI
- Create, view, and delete items

### Calendar

- Create, edit, and delete events
- Day / month views
- Recurrence (daily, weekly, monthly)
- All-day events
- Event notes

### Collaboration

- Request collaboration by email
- Accept or reject collaboration requests
- List collaborators and pending requests
- Share context and access with others

### GodsEye

- **Logs** — Browse screen capture logs
- **Periodic captures** — Screenshots every ~30 seconds when logged in
- **Collaborator view** — Filter logs by collaborator
- Enables shared visibility across collaborators

### Settings

- **Profile** — View account info and logout
- **Updates** — Manual check for app updates
- **UI** — Glow effect toggle
- **Auto-upload** — Enable/disable and set upload path for automatic file uploads
- **Browser access** — Optional connection to Chrome DevTools (debug port) for browser context

### Platform

- **Electron** desktop app (Windows)
- Auto-updates via electron-updater
- Persistent launcher with animations (GSAP)
- AI-powered launcher suggestions based on input

---

## Summary

Elefanta combines **file search**, **AI chat**, **screen analysis**, **calendar**, **collaboration**, and **automatic context capture (GodsEye)** in one Windows desktop app.
