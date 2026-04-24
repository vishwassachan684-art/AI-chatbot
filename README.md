# 🏥 AI Doctor Booking Assistant

A beautiful, responsive, and intelligent medical appointment booking system powered by a free Conversational AI.

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/USERNAME/REPOSITORY)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/USERNAME/REPOSITORY)

> [!IMPORTANT]
> **Replace `USERNAME/REPOSITORY`** in the links above with your actual GitHub username and repository name to enable the interactive buttons!

---

## ✨ Features

- **🤖 AI-Powered Assistant**: A friendly AI agent (Dr. Smith's Assistant) that handles patient inquiries.
- **📅 Smart Booking**: The AI can automatically check available slots and book appointments using integrated tools.
- **💸 100% Free API**: Uses the Pollinations AI API — **no Gemini or OpenAI API keys required** to run the project.
- **🎨 Premium UI**: Built with a modern, glassmorphic design system using Vanilla CSS and Next.js.
- **📱 Responsive**: Fully optimized for mobile, tablet, and desktop.

## 🚀 Getting Started

### 1. Clone & Install
```bash
git clone https://github.com/USERNAME/REPOSITORY.git
cd REPOSITORY
npm install
```

### 2. Run Locally
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) to see your AI assistant in action.

## 🛠️ Tech Stack

- **Framework**: [Next.js 15+](https://nextjs.org) (App Router)
- **Language**: TypeScript
- **Styling**: Vanilla CSS (CSS Modules & Global Variables)
- **AI Engine**: [Pollinations AI](https://pollinations.ai/) (OpenAI-compatible free endpoint)

## 📖 How it Works

The chatbot uses **Tool Calling (Function Calling)** to interact with a mock database of appointments.
- **`getAvailableSlots`**: AI fetches current availability.
- **`bookAppointment`**: AI processes the booking once the patient provides their name, date, and time.

You can modify the bot's behavior in `src/app/api/chat/route.ts` by editing the `SYSTEM_PROMPT`.

## 🤝 Contributing

This project is open for anyone to explore and modify! Feel free to:
1. Click the **StackBlitz** button above to edit directly in your browser.
2. Fork the repository and add new features (like SMS notifications or a real database integration).

---
*Created with ❤️ for a better patient experience.*
