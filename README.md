# 🌾 KisanMitra

**An AI-powered farming assistant chatbot for smallholder farmers — built with the Gemini API.**

> Built for ML AlgoRush

---

## The Problem

Smallholder and marginal farmers across rural India — especially in West Bengal — struggle to get
timely agricultural guidance. Agricultural extension officers are scarce, and most farming
information available online is scattered, overly technical, and written in English. This leaves
farmers without quick, practical answers when they need them most — during sowing season, when a
pest outbreak hits, or when trying to figure out which government scheme they qualify for.

## Who It's For

**Smallholder and marginal farmers in West Bengal** — paddy and jute growers, among others — who
are far more comfortable asking a question in Bengali or Hindi than searching the web in English.

## Why Gemini?

- **Multilingual by default** — holds a natural conversation in Bengali, Hindi, or English without
  separate translation pipelines.
- **Reasons over vague, plain-language descriptions** — a farmer describing "leaves turning yellow"
  gets a genuinely useful response, not a keyword-matched FAQ entry.
- **Synthesizes broad agricultural + policy knowledge conversationally** — instead of static
  documents or search results, the farmer gets a direct, personalized answer.

Building an equivalent system with custom NLP from scratch isn't feasible in a hackathon timeframe —
an LLM is the only practical way to deliver this experience well.

---

## Features

- 💬 Conversational chat interface with memory of the current session
- 🌐 Language selector — English / বাংলা (Bengali) / हिंदी (Hindi)
- ⚡ One-tap quick topics: Crop Advice, Pest & Disease Help, Government Schemes, Weather & Irrigation
- 🧠 System prompt tuned for simple, low-literacy-friendly, actionable answers
- 🛡️ Built-in guardrail — the bot avoids inventing specific scheme names/amounts and points users to
  their local Krishi Bhavan / block office for verification and serious issues

---

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript (vanilla, no framework/build step)
- **AI Engine:** Google Gemini API (`gemini-2.0-flash`)
- **Hosting:** Static site — deployable via GitHub Pages, Netlify, or Vercel

---

## How to Run

1. Clone or download this repository.
2. Open `KisanMitra Project.html` in any modern browser — no install, no server required.
3. Paste your Gemini API key into the **Gemini API key** field in the chat sidebar.
   - Get a free key from [Google AI Studio](https://aistudio.google.com/).
   - The key stays in your browser only — it is never sent anywhere except Google's API.
4. Pick a language, tap a quick topic or type your own question, and start chatting.

---

## Project Status

Built as a solo submission for **ML AlgoRush**.

### Possible Next Steps
- Voice input/output for low-literacy users
- Image upload for visual pest/disease identification (Gemini vision)
- Location-aware weather via a live weather API
- Persistent chat history per user

---

## License

This project was built for a hackathon submission. No license specified.
