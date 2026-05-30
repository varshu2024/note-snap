# How I Built NoteSnap: An AI Tool That Helps Indian Students Study Smarter

*A project for the Gen AI Academy APAC — Meet the Builders 2026 Campaign*

---

## The Problem I Saw Around Me

I'm a student in India. Every exam season, I watch my classmates — and myself — struggle with the same thing: hundreds of pages of textbooks, dense lecture notes, and never enough time to read everything before the exam.

Here's the reality for millions of Indian students:

- **NCERT textbooks** can run to 300+ pages per subject
- **Private tuition** costs ₹2,000–₹10,000 a month — not affordable for everyone
- **Complex English** in textbooks creates a barrier for students from regional-medium schools
- **Competitive exams** (JEE, NEET, UPSC) demand mastery across multiple massive subjects simultaneously

I kept thinking: *what if AI could be that patient, affordable tutor that helps any student, anywhere, for free?*

That question led me to build **NoteSnap**.

---

## What Is NoteSnap?

NoteSnap is a free, browser-based web app where students can:

1. **Upload any PDF** — a textbook chapter, lecture notes, or a handout
2. **Choose how they want to learn** — full summary, exam questions, quick bullet points, simplified explanation, or a mind map
3. **Get instant AI output** — structured, clear, and exam-ready in under 10 seconds

No login. No payment. No installation. Just open it in Chrome, paste your free Google Gemini API key, and start learning.

---

## The Technology Behind It

### Google Gemini 1.5 Flash — The Heart of NoteSnap

I chose **Google Gemini 1.5 Flash** as the AI engine for one simple reason: it's fast, accurate, and has a generous free tier that makes the tool genuinely accessible to every student.

The Gemini API processes the extracted text from the PDF and returns structured summaries based on the prompt style the student chooses.

### PDF.js — Reading the Student's Files

I used **Mozilla's PDF.js** library to extract text from uploaded PDFs entirely in the browser — no server needed, no data uploaded anywhere except directly to Google's API.

### Pure HTML, CSS & JavaScript — Zero Friction

The entire app is a single `index.html` file. No Node.js, no npm, no build step. Any student can:
- Download the file
- Open it in Chrome
- Start using it immediately

This was a deliberate choice. Complex setups are a barrier for students. One file = instant access.

### Google AI Studio — My Prompt Engineering Lab

I used **Google AI Studio** to experiment with different prompts and find the optimal way to instruct Gemini for each summary mode. Prompt engineering turned out to be half the work — and half the learning.

---

## The Five Summary Modes I Built

The core insight was that students don't always want the same thing. Sometimes you need to understand a topic deeply. Sometimes you just need to quickly revise before a test. Sometimes you're completely lost and need someone to explain it simply.

So I built five modes:

| Mode | What It Does | When to Use |
|---|---|---|
| **Full Summary** | Key concepts + definitions + revision points | First time studying a chapter |
| **Exam Prep** | Likely questions + model answers + scoring tips | 2 days before exam |
| **Quick Revision** | 10 power bullet points | Night before exam |
| **Simplify** | Explain like I'm 15 with Indian examples | When the English is too complex |
| **Mind Map** | Text-based topic tree | Visual learners, overview |

Each mode uses a carefully crafted prompt tailored to Indian students and the Indian exam system.

---

## What I Learned About Prompt Engineering

Before building this, I thought AI was mostly about the model. After building NoteSnap, I understand that **the prompt is at least as important as the model**.

Two prompts for the same content can give dramatically different results. My "Exam Prep" prompt took 12 iterations before it consistently produced the structured output I wanted. The "Simplify" prompt needed to explicitly say "use examples from Indian daily life" to make the outputs feel relevant to students.

**Lesson learned**: A well-crafted prompt is the product. The model is the tool.

---

## The Impact I'm Hoping For

Let me paint a picture of how NoteSnap helps a real student:

> *Priya is a Class 12 student in Hyderabad. Her Physics exam is in 3 days. Chapter 12 (Atoms) is 35 pages long and she hasn't touched it. She uploads the PDF to NoteSnap, selects "Exam Prep", clicks Generate. In 8 seconds, she has 5 short-answer questions, 3 long-answer questions, the 3 most likely topics, and scoring tips. She spends 90 minutes on focused revision instead of 5 hours of uncertain reading.*

That's the real value — not just AI for AI's sake, but AI that solves a genuine problem for real students.

---

## How to Try NoteSnap Right Now

1. Get a free Gemini API key at [aistudio.google.com](https://aistudio.google.com) (no credit card needed)
2. Open `index.html` in Chrome
3. Paste your key, upload any PDF, choose a summary style
4. Click **Generate**

The entire experience takes under 2 minutes to set up.

---

## What's Next for NoteSnap

The roadmap I'm excited about:

- **Regional language summaries** — Hindi, Telugu, Tamil, Bengali, so students can get summaries in their mother tongue
- **Audio output** — Listen to summaries using Google Text-to-Speech while commuting
- **Gemini Vision support** — Process scanned PDFs (image-based) that can't be read by text extraction
- **WhatsApp bot** — For the 700M+ Indians who use WhatsApp as their primary internet interface

---

## Final Thought

A certificate says you learned something. A live, working project says you built something.

NoteSnap is my proof that I can take a real problem, choose the right technology (Google Gemini), engineer the right solution (thoughtful prompting + accessible design), and ship something useful.

If it helps even one student study more effectively, it was worth every hour.

---

**Uppada Varshini**  
Student, India 🇮🇳  
Gen AI Academy APAC — Meet the Builders 2026

*#GenAIAcademy #MeetTheBuilders #GoogleGemini #GeminiAPI #StudentDeveloper #IndiaAI*
