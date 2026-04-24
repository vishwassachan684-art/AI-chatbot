# 🏥 AI Doctor Booking Assistant

An intelligent and responsive **AI-powered medical appointment booking chatbot** built using Next.js and a free OpenAI-compatible API.

---

## ✨ Features

* 🤖 **AI Assistant** – Handles patient queries like a real receptionist
* 📅 **Smart Appointment Booking** – Checks available slots and books automatically
* 💸 **Free AI API** – Uses Pollinations AI (no API key required)
* 🎨 **Modern UI** – Clean and responsive interface built with CSS & Next.js
* 📱 **Fully Responsive** – Works on mobile, tablet, and desktop

---

## 🚀 Run Locally (Step-by-Step)

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/vishwassachan684-art/AI-chatbot.git
cd AI-chatbot
```

---

### 2️⃣ Install Dependencies

```bash
npm install
```

---

### 3️⃣ Start Development Server

```bash
npm run dev
```

---

### 4️⃣ Open in Browser

Go to:

```
http://localhost:3000
```

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

You can customize AI behavior in:

```
src/app/api/chat/route.ts
```

---

## 📂 Project Structure (Important Files)

```
src/
 ├── app/
 │    ├── api/chat/route.ts   # AI logic & API handler
 │    ├── page.tsx            # Main UI
 │
 ├── components/              # UI components
 ├── styles/                  # CSS files
```

---

## ⚠️ Notes

* No API key is required to run this project
* Make sure Node.js (v18+) is installed
* If port 3000 is busy, Next.js will automatically switch ports

---

## 🤝 Contributing

Feel free to fork this project and improve it:

* Add database integration
* Improve UI/UX
* Add authentication

---

## 📌 Author

**Vishwas Sachan**
GitHub: https://github.com/vishwassachan684-art

---

💡 *Built for learning, experimenting, and building real-world AI applications.*
