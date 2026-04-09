<div align="center">

<!-- HERO BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Sage%20AI&fontSize=80&fontColor=ffffff&fontAlignY=38&desc=Built%20Beyond%20Limits%20%F0%9F%9A%80&descAlignY=60&descSize=22&animation=fadeIn" width="100%" />

<br/>

<!-- BADGES -->
<p>
  <img src="https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Groq-AI%20Engine-F55036?style=for-the-badge&logo=groq&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-PostgreSQL-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-Deploy-000000?style=for-the-badge&logo=vercel&logoColor=white" />
</p>

<p>
  <img src="https://img.shields.io/github/stars/ShadowByte01/Sage-ai?style=for-the-badge&color=FFD700&logo=github" />
  <img src="https://img.shields.io/github/forks/ShadowByte01/Sage-ai?style=for-the-badge&color=7B68EE&logo=github" />
  <img src="https://img.shields.io/github/license/ShadowByte01/Sage-ai?style=for-the-badge&color=00CED1" />
  <img src="https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge" />
</p>

<br/>

> **The open-source AI platform that thinks fast, remembers everything, and speaks your language.**
> Build your own intelligent assistant in minutes — no PhD required.

<br/>

<a href="#-quick-start">
  <img src="https://img.shields.io/badge/⚡%20Get%20Started-2563EB?style=for-the-badge" />
</a>
&nbsp;&nbsp;
<a href="#-features">
  <img src="https://img.shields.io/badge/✨%20Features-7C3AED?style=for-the-badge" />
</a>
&nbsp;&nbsp;
<a href="https://github.com/ShadowByte01/Sage-ai/fork">
  <img src="https://img.shields.io/badge/🍴%20Fork%20It-059669?style=for-the-badge" />
</a>

</div>

---

<br/>

## 🌌 What is Sage AI?

**Sage AI** is a **fully open-source, production-ready AI chatbot platform** powered by the blazing-fast **Groq inference engine**. Think of it as your own private ChatGPT — but you own the code, you own the data, and you control everything.

Whether you're a developer looking to embed a smart AI into your product, a student learning how modern LLM apps are built, or a hacker who just wants a cool self-hosted assistant — **Sage AI is your starting point**.

```
You clone it → You configure it → You launch it → ✨ Magic
```

<br/>

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🧠 Smart AI Conversations
Real-time, context-aware conversations powered by Groq's ultra-fast LLM inference. Get responses that are sharp, accurate, and nearly instant.

</td>
<td width="50%">

### 💾 Persistent Memory
Every conversation is stored in PostgreSQL (Supabase). Your chat history survives page reloads, browser closes, and even reboots.

</td>
</tr>
<tr>
<td width="50%">

### 🔐 Secure Auth System
Full JWT-based authentication with bcrypt-hashed passwords. Signup, login, and session management — all handled securely server-side.

</td>
<td width="50%">

### 💬 Multiple Chat Sessions
Manage and switch between multiple conversations simultaneously — just like ChatGPT, but yours.

</td>
</tr>
<tr>
<td width="50%">

### 🎙️ Voice Chat Support
Talk to Sage, don't just type to it. Voice input support makes the experience feel truly futuristic.

</td>
<td width="50%">

### 🎨 Image Generation
Not just words — Sage AI can bring ideas to life visually. Image generation built right in.

</td>
</tr>
<tr>
<td width="50%">

### 🎬 Silky Smooth Animations
Powered by **Framer Motion** and **Three.js**, every interaction feels buttery-smooth and visually stunning.

</td>
<td width="50%">

### 📱 Fully Responsive
From a 4K monitor to your phone screen — Sage AI looks gorgeous everywhere.

</td>
</tr>
</table>

<br/>

---

## 🏗️ Tech Stack

<div align="center">

| Layer | Technology | Why We Chose It |
|---|---|---|
| 🖥️ **Frontend** | Next.js 14 + React + TypeScript | SSR, fast routing, type safety |
| ⚙️ **Backend** | Next.js API Routes | Zero-config serverless API |
| 🗄️ **Database** | PostgreSQL via Supabase | Scalable, hosted, reliable |
| 🤖 **AI Engine** | Groq SDK | Fastest LLM inference on the planet |
| 🎬 **Animations** | Framer Motion + Three.js | Fluid UI & 3D visual magic |
| 🔑 **Auth** | JWT + bcryptjs | Battle-tested security |
| 💅 **Styling** | CSS Modules | Scoped, no-conflict styles |
| ☁️ **Deployment** | Vercel | One-click, zero-config cloud |

</div>

<br/>

---

## ⚡ Quick Start

### Prerequisites

Make sure you have these ready:
- **Node.js** ≥ 18
- A free **[Supabase](https://supabase.com)** account
- A free **[Groq](https://console.groq.com)** API key

---

### 1️⃣ — Clone the Repository

```bash
git clone https://github.com/ShadowByte01/Sage-ai.git
cd Sage-ai
```

---

### 2️⃣ — Install Dependencies

```bash
npm install
```

---

### 3️⃣ — Set Up Your Database

1. Create a new project on [Supabase](https://supabase.com)
2. Navigate to **SQL Editor**
3. Copy and run the contents of `/db/schema.sql`

This creates all required tables:
- `users` — authentication records
- `chat_sessions` — conversation threads
- `messages` — individual message history

---

### 4️⃣ — Configure Environment Variables

Create a `.env.local` file in the root of the project:

```env
# 🤖 AI Engine
GROQ_API_KEY=your_groq_api_key_here

# 🗄️ Database
SUPABASE_DBURL=your_postgresql_connection_string_here

# 🎨 Customization
CHATBOT_NAME=Sage AI
CHATBOT_LOGO_URL=https://your-logo-url.com/logo.png

# 🔐 Security
SESSION_SECRET=your_super_secret_key_here_make_it_long
```

> 💡 See `.env.local.example` in the repo for a template you can copy directly.

---

### 5️⃣ — Launch!

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) and say hello to Sage. 👋

<br/>

---

## 🚀 Deploy to Production

### One-click Vercel Deploy

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/ShadowByte01/Sage-ai)

### Manual Vercel CLI Deploy

```bash
npm i -g vercel
vercel
```

> ⚠️ **Important:** Don't forget to add all environment variables inside **Vercel Dashboard → Project Settings → Environment Variables** before deploying!

<br/>

---

## 📂 Project Structure

```
Sage-ai/
│
├── 📁 components/          # Reusable UI components (buttons, chat bubbles, etc.)
├── 📁 src/component/       # Core app-specific components
├── 📁 pages/               # Next.js routes & pages
│   └── 📁 api/             # Serverless API route handlers
├── 📁 lib/                 # Utilities, helpers & shared logic
├── 📁 db/                  # Database schema (schema.sql)
├── 📁 public/              # Static assets (images, icons, fonts)
├── 📁 styles/              # CSS Module stylesheets
│
├── 📄 .env.local.example   # Environment variable template
├── 📄 next.config.js       # Next.js configuration
├── 📄 tsconfig.json        # TypeScript configuration
└── 📄 package.json         # Project dependencies
```

<br/>

---

## 🔐 Security & Best Practices

Sage AI is built with security-first principles:

- 🔒 **JWT-based sessions** — stateless, secure, and scalable authentication
- 🧂 **bcrypt password hashing** — your users' passwords are never stored in plain text
- 🌐 **Server-side API handling** — your AI keys and DB credentials never touch the client
- 🏗️ **Environment variable isolation** — secrets stay secret via `.env.local`
- 🔑 **Database-level user isolation** — each user only sees their own conversations

<br/>

---

## 📈 Built to Scale

Sage AI is designed to grow with you:

- **Modular architecture** — swap out the AI engine, the DB, or the frontend independently
- **API-first design** — plug in any frontend or consume the API from mobile apps
- **Serverless-ready** — no long-running servers; deploys beautifully on Vercel's edge
- **Easily extensible** — add new models, new providers, or new features without breaking anything

<br/>

---

## 🤝 Contributing

Contributions are what make open source beautiful. Any contribution you make is **greatly appreciated**.

1. **Fork** the repository
2. Create your feature branch: `git checkout -b feature/AmazingFeature`
3. Commit your changes: `git commit -m 'Add some AmazingFeature'`
4. Push to the branch: `git push origin feature/AmazingFeature`
5. Open a **Pull Request**

> ⭐ If Sage AI helped you or impressed you, please consider starring the repo — it means the world to open-source maintainers!

<br/>

---

## 📜 License

Distributed under the **MIT License**. See `LICENSE` for more information.

You are free to use, modify, fork, sell, and distribute this software — just keep the attribution. 🙏

<br/>

---

## 👨‍💻 Author

<div align="center">

<img src="https://avatars.githubusercontent.com/u/ShadowByte01" width="80" style="border-radius:50%" />

**shadow.devs**

*Built with ❤️, caffeine ☕, and a burning desire to push limits.*

[![GitHub](https://img.shields.io/badge/GitHub-ShadowByte01-181717?style=for-the-badge&logo=github)](https://github.com/ShadowByte01)

</div>

<br/>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" width="100%"/>

**If this project sparked something in you — a star ⭐ goes a long way.**

*Sage AI — Smarter. Faster. Beyond Limits.*

</div>
