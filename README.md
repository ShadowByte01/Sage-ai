# 🚀 Sage AI

### Professional AI Chatbot Platform

**Sage AI** is a production-ready AI chatbot application built with **Next.js 14, TypeScript, PostgreSQL (Supabase), and Groq AI**.

It features secure authentication, persistent chat history, multiple chat sessions, and a modern ChatGPT-inspired interface — optimized for performance and seamless Vercel deployment.

---

## ✨ Key Features

* 🔐 Secure User Authentication (Signup / Login)
* 🤖 AI-Powered Conversations via Groq SDK
* 💾 Persistent Chat History (PostgreSQL)
* 💬 Multiple Chat Sessions
* ⚡ Real-Time Messaging Experience
* 🎨 Modern ChatGPT-Inspired UI
* 🎬 Smooth Animations (Framer Motion)
* 📱 Fully Responsive Design
* ☁️ One-Click Vercel Deployment

---

## 🏗 Tech Stack

| Layer          | Technology                    |
| -------------- | ----------------------------- |
| **Frontend**   | Next.js 14, React, TypeScript |
| **Backend**    | Next.js API Routes            |
| **Database**   | PostgreSQL (Supabase)         |
| **AI Engine**  | Groq SDK                      |
| **Animations** | Framer Motion                 |
| **Styling**    | CSS Modules                   |
| **Deployment** | Vercel                        |

---

## ⚙️ Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/sage-ai.git
cd sage-ai
```

---

### 2️⃣ Install Dependencies

```bash
npm install
```

---

### 3️⃣ Configure Database (Supabase)

1. Create a new Supabase project.
2. Open the **SQL Editor**.
3. Run the schema file:

```
/db/schema.sql
```

This will generate all required tables for:

* Users
* Chat Sessions
* Messages

---

### 4️⃣ Environment Variables

Create a `.env.local` file in the root directory:

```env
GROQ_API_KEY=your_groq_api_key
SUPABASE_DBURL=your_postgresql_connection_string
CHATBOT_NAME=Sage AI
CHATBOT_LOGO_URL=https://your-logo-url.com/logo.png
SESSION_SECRET=your_super_secret_key
```

### 🔑 Required Variables

- `GROQ_API_KEY` - Your Groq API key
- `SUPABASE_DBURL` - PostgreSQL connection string
- `CHATBOT_NAME` - Name of your chatbot
- `CHATBOT_LOGO_URL` - URL to chatbot logo
- `SESSION_SECRET` - Secret for JWT tokens


---

### 5️⃣ Run Development Server

```bash
npm run dev
```

Visit:

```
http://localhost:3000
```

---

## 🚀 Production Deployment (Vercel)

Deploy instantly using:

```bash
vercel
```

Or connect your GitHub repository to Vercel.

### ⚠️ Important

Add all environment variables in the **Vercel Dashboard → Project Settings → Environment Variables**

---

## 📂 Project Structure

```
/components
/pages
/api
/lib
/db
/styles
```

* `components/` → UI components
* `pages/` → Routes & pages
* `api/` → Backend API logic
* `lib/` → Utilities & helpers
* `db/` → Database schema
* `styles/` → CSS modules

---

## 🔐 Security & Best Practices

* JWT-based session authentication
* Secure environment variables
* Server-side API handling
* Database isolation via Supabase

---

## 📈 Scalability Ready

* Modular architecture
* API-driven design
* Optimized for serverless deployment
* Easy integration with additional AI models

---

## 📜 License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute this software with proper attribution.

---

## 👨‍💻 Author

Built with ❤️ by shadow.devs
