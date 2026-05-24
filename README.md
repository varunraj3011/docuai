# ⚡ DocuAI — AI-Powered Documentation Generator

> Stop writing docs manually. Paste any code → get complete professional documentation in under 5 seconds.

**Built for AI Hackathon for Builders
GL Bajaj Institute of Management and Research* | Problem Statement #8 — Technical Documentation Generator

---

## 🚀 Live Demo

👉 **[Try it live](https://varunraj3011.github.io/docuai)**

---

## 🎯 Problem It Solves

Developers rarely write documentation. This causes:
- Outdated or missing API docs
- Onboarding confusion for new team members
- Hours wasted explaining code in meetings

**DocuAI fixes this instantly** — paste any function, class, or module and get complete, structured documentation automatically.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔍 Auto language detection | Works with JS, Python, Java, Go, Rust, SQL, and more |
| 📝 Complete docstrings | Ready-to-paste JSDoc / Python docstring format |
| ⚙️ Parameter table | Name, type, required/optional, description for every param |
| 🧪 Usage examples | 2 real examples generated from your code |
| ⚠️ Edge cases | Identifies inputs that could break the function |
| 📊 Complexity analysis | Big-O time & space with explanation |
| 🔒 Security notes | Flags potential vulnerabilities in your code |

---

## 🛠️ Tech Stack

- **Frontend** — Pure HTML, CSS, JavaScript (zero frameworks, zero dependencies)
- **AI** — Google Gemini 2.0 Flash Lite API
- **Hosting** — GitHub Pages (free)

---

## 🏃 How to Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/YOURUSERNAME/docuai.git
   cd docuai
   ```

2. Open `index.html` in your browser — no server needed!

3. Get a free Gemini API key from [aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)

4. Paste the key in the app and start generating docs

---

## 🔐 API Key Safety

The API key is **never stored in the code**. It is entered by the user at runtime in the browser and is never sent anywhere except directly to Google's Gemini API over HTTPS.

---

## 💡 How It Works

```
You paste code
      ↓
Browser sends it to Gemini API (Google's servers)
      ↓
AI reads code → understands functions, params, logic
      ↓
Returns structured JSON (name, params, examples, complexity…)
      ↓
App renders beautiful documentation instantly
```

---

## 📸 Screenshots

> Add screenshots here after your demo

---

## 👨‍💻 Built By

- **Your Name** — [GitHub](https://github.com/varunraj3011)

Built in **24 hours** during the hackathon.

---

## 📄 License

MIT License — free to use and modify.
