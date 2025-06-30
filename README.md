

---
# 🧠 AI Resume Builder – Copilot Flow (n8n + Supabase + Vite + React)

An end-to-end AI-powered resume generator. Users fill out a form and instantly receive a beautifully designed, ATS-friendly PDF resume — generated using OpenAI and stored securely in Supabase.

---

## 🚀 Project Overview

This project is a full-stack automation system:

1. **Frontend** (React + Tailwind): Users enter resume details.
2. **n8n Workflow**: Receives form data via webhook, generates professional resume using OpenAI, styles it as HTML, converts to PDF, and uploads to Supabase.
3. **Supabase**: Public storage of generated resumes.
4. **Frontend fetch**: Resume download link is displayed to the user.

---

## 🗂 Folder Structure

```

copilot-resume-flow/
├── public/              # Favicon, SEO files
├── src/                 # React app source code
│   ├── components/      # UI components
│   ├── hooks/           # Custom hooks
│   ├── integrations/    # API & webhook logic
│   ├── lib/             # Utility functions
│   ├── pages/           # Form & download views
│   ├── App.tsx          # Root component
│   └── main.tsx         # App entry point
├── supabase/            # Supabase migrations/config
├── index.html           # Vite HTML template
├── tailwind.config.ts   # Tailwind setup
├── vite.config.ts       # Vite config
├── README.md            # This file

````

---

## 🔧 Technologies Used

| Layer       | Tech                          |
|-------------|-------------------------------|
| Frontend    | React, TypeScript, TailwindCSS |
| Backend     | [n8n](https://n8n.io/) (No-code workflow automation) |
| AI          | OpenAI via LangChain           |
| PDF Engine  | [Browserless](https://browserless.io/) |
| Storage     | Supabase Buckets               |

---
---

## 🧪 Run Locally

```bash
# Install dependencies
bun install

# Start development server
bun dev
````

Or with npm:

```bash
npm install
npm run dev
```

---

## 📸 Screenshots / Demo

![Screenshot 2025-06-30 112301](https://github.com/user-attachments/assets/c3d5ed15-f54e-4dbe-8048-fbac1e925d49)

![Screenshot 2025-06-30 112312](https://github.com/user-attachments/assets/6852706a-7ed7-4160-9601-80c0c16d32dc)

---

## ✍️ Contribution Guide

1. Fork this repo
2. Clone your fork
3. Create a new branch
4. Submit a Pull Request 🚀

---

## 📄 License

MIT License

---

## 💡 Author

> Built with ❤️ by [Anurag Srivastav](https://github.com/DeveloperAnuragsrivastav)

```



