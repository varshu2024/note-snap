# 📚 NoteSnap — AI-Powered Study Summarizer

> **Built for Gen AI Academy APAC 2026 — Meet the Builders Campaign**  
> Powered by **Google Gemini 1.5 Flash**  
> 🌐 **Live Demo:** [notesnap2.netlify.app](https://notesnap2.netlify.app/)

---

## 🎯 Problem Statement

Students across India and the APAC region face these challenges every exam season:

| Problem | Impact |
|---|---|
| Thick textbooks (NCERT, 300+ page PDFs) | Hours of reading, poor retention |
| Dense lecture notes | Hard to revise the night before exams |
| Private tuition unaffordable (₹2,000–₹10,000/month) | Inequality in exam preparation |
| Complex English in textbooks | Barrier for regional-language students |
| No personalized study tools | One-size-fits-all approach fails |

**Target Users:** Class 10–12 students, college students, JEE/NEET/UPSC aspirants across India.

---

## 💡 Solution: NoteSnap

NoteSnap is a **free, browser-based AI study tool** where students can:

1. Upload any PDF (textbook chapter, lecture notes, handout)
2. Choose how they want to understand it (summary, exam prep, simplified, etc.)
3. Get a structured, AI-powered output instantly via **Google Gemini 1.5 Flash**
4. Copy or download the result for offline study

No login. No payment. No installation. Just open and use.

---

## ✨ Features

| Feature | Description |
|---|---|
| 📋 **Full Summary** | Key concepts + definitions + revision points |
| ❓ **Exam Prep** | Likely exam questions + model answers + scoring tips |
| ⚡ **Quick Revision** | 10 power bullet points only |
| 🧒 **Simplify** | Explain like I'm 15 years old, with relatable examples |
| 🗺️ **Mind Map** | Hierarchical text-based topic tree |
| 📂 **Drag & Drop** | Drop your PDF directly onto the upload area |
| ⬇️ **Download** | Save summary as a .txt file |
| 🧠 **Subject Hints** | Tag subject for better Gemini output |

---

## 🛠️ Tech Stack

| Technology | Purpose | Why This? |
|---|---|---|
| **Google Gemini 1.5 Flash** | AI summarization engine | Fast, accurate, generous free tier |
| **Google AI Studio** | API key generation & testing | Official Google Cloud platform |
| **PDF.js (Mozilla)** | Extract text from uploaded PDFs | Open-source, browser-based |
| **HTML5 + CSS + Vanilla JS** | Frontend — no framework needed | Zero dependencies, runs anywhere |

---

## 📁 Project Structure

```
notesnap/
├── index.html          ← Complete working app (open directly in Chrome)
├── README.md           ← This file — project documentation
├── blog-post.md        ← Full blog post for submission
├── linkedin-post.txt   ← Ready-to-post LinkedIn content
└── CHECKLIST.md        ← Step-by-step submission guide
```

---

## 🚀 How to Run

### Option 1: Local (Instant)
1. Download `index.html`
2. Open it in **Google Chrome** or any modern browser
3. Get a free Gemini API key from [aistudio.google.com](https://aistudio.google.com)
4. Upload a PDF → Select summary type → Click **Generate**

### Option 2: Host Online (Free)
- **GitHub Pages**: Push to a GitHub repo → Enable Pages in Settings
- **Netlify Drop**: Drag the file to [app.netlify.com/drop](https://app.netlify.com/drop)
- **Vercel**: Import the file via Vercel dashboard

---

## 🔑 Getting Your Free Gemini API Key

1. Go to [aistudio.google.com](https://aistudio.google.com)
2. Sign in with your Google account
3. Click **"Get API Key"** → **"Create API Key"**
4. Copy the key — it starts with `AIza...`
5. Paste it into NoteSnap's Step 1 input

> ⚠️ **Security**: Your key is only used client-side to call Google's API directly. It is never stored or sent anywhere else.

---

## 🎓 Google AI Technologies Used

- **Google Gemini 1.5 Flash API** — the core AI engine for summarization
- **Google AI Studio** — for testing, prompt engineering, and key management

---

## 📊 Real-World Impact

- A student uploads a 40-page NCERT Physics chapter
- NoteSnap extracts the text and sends it to Gemini
- In under 10 seconds: structured summary, definitions, revision points
- Student saves 2–3 hours of reading time
- Free alternative to ₹5,000/month private tuition

---

## 🔮 Future Roadmap

- [ ] Regional language support (Hindi, Telugu, Tamil, Bengali)
- [ ] Audio summaries using Google Text-to-Speech
- [ ] Subject-specific prompt templates (JEE, NEET, UPSC)
- [ ] WhatsApp bot integration for mobile-first users
- [ ] Gemini Vision support for scanned/image-based PDFs

---

## 👩‍💻 Built By

**Uppada Varshini**  
Student, India 🇮🇳  
Built for Gen AI Academy APAC — Meet the Builders 2026

---

*Made with ❤️ using Google Gemini AI*
