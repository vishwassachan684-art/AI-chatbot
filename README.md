# 🏥 AI Doctor Booking Assistant

An intelligent and responsive **AI-powered medical appointment booking chatbot** built using Next.js and a free OpenAI-compatible API.

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/vishwassachan684-art/AI-chatbot)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/vishwassachan684-art/AI-chatbot)

---

## ✨ Features

* 🤖 **AI Assistant** – Handles patient queries like a real receptionist
* 📅 **Smart Appointment Booking** – Checks available slots and books automatically
* 💸 **Free AI API** – Uses Pollinations AI (no API key required)
* 🎨 **Modern UI** – Clean and responsive interface built with CSS & Next.js
* 📱 **Fully Responsive** – Works on mobile, tablet, and desktop

---

## 🚀 Run Locally (Recommended)

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/vishwassachan684-art/AI-chatbot.git
cd AI-chatbot
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Start Development Server

```bash
npm run dev
```

### 4️⃣ Open in Browser

http://localhost:3000

---

## ⚡ Quick Start (No Setup)

You can also run this project instantly in your browser:

* Click **Open in StackBlitz** (runs instantly)
* Or use **GitHub Codespaces**

---

## 🛠️ Tech Stack

* **Framework:** Next.js (App Router)
* **Language:** TypeScript
* **Styling:** CSS Modules + Global CSS
* **AI Engine:** Pollinations AI (OpenAI-compatible API)

---

## 📖 How It Works

This chatbot uses **function/tool calling** to simulate a real booking system:

* `getAvailableSlots` → Fetches available appointment times
* `bookAppointment` → Books a slot based on user input

Modify behavior here:

```
src/app/api/chat/route.ts
```

---

## 📂 Project Structure

```
src/
 ├── app/
 │    ├── api/chat/route.ts
 │    ├── page.tsx
 │
 ├── components/
 ├── styles/
```

---

## ⚠️ Notes

* No API key required
* Requires Node.js v18+
* Auto-switches port if 3000 is busy

---

## 🤝 Contributing

Feel free to fork and improve:

* Add database
* Improve UI
* Add authentication

---

## 📌 Author

**Vishwas Sachan**
https://github.com/vishwassachan684-art

---

💡 *Built for learning and real-world AI experimentation.*
