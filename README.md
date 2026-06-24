# 🧠 MINDRIFT — Your Mental Wellness Companion

MINDRIFT is a culturally-aware mental wellness platform built for Indian competitive exam aspirants — JEE, NEET, UPSC, and college students alike. It blends AI-powered emotional support, anonymous peer sharing, stress-relief tools, and personalized daily planning to help students navigate exam pressure, family expectations, and the everyday weight of student life.

---

## 📌 About This Project

Most mental wellness apps aren't built with the Indian student experience in mind — the specific pressure of competitive exams, family expectations, and a culture where talking about mental health is still difficult. MINDRIFT is an attempt to close that gap: a single-page web app combining an empathetic AI companion, a stigma-free community space, and practical tools — all in one place.

- 🎓 B.Tech CSE (AI/ML Specialization), Future University
- 🛠️ Focus: Designing a genuinely useful, culturally-aware wellness product end-to-end
- 📈 Goal: Build something real students would actually want to use

---

## ✨ Features

### 🧠 SoulSync — AI Companion
A conversational AI support chat powered by Claude, with selectable personas (Big Bro, Big Sis, Best Friend, Wise Mentor, Calm Guide) that speak in a warm, natural Hindi-English mix. Includes built-in sentiment detection — if a conversation signals distress, it surfaces verified Indian crisis helpline numbers (iCall, Vandrevala Foundation) automatically.

### 👥 EchoSpace — Anonymous Sharing
A safe, anonymous space to post what's on your mind, tag posts by topic, relate to others' posts, and reply — built to reduce the isolation that often comes with exam stress.

### 🧘 CalmCore — Stress Relief Toolkit
Guided breathing exercises (4-7-8, box breathing, etc.), quick physical movement breaks, and short meditations — all trackable with session streaks.

### 🌍 TherapyBridge — Professional Support
Browse and filter therapists by specialization, then book a session through a simple date/time slot picker.

### 📅 LifeMap — Personalized Daily Planner
Generates a day plan adapted to your current mental state (e.g. exam-stressed vs. anxious), balancing study blocks, breaks, meals, and sleep — with Gen Z–style nudges to keep you on track.

### 💼 OpportunityHub
A filterable feed of opportunities (internships, scholarships, etc.) relevant to the student's course.

### 📊 Mood Tracker
Daily mood logging with notes, streaks, and a visual history chart to help students notice their own patterns over time.

### 🎨 Other touches
Guided onboarding (7-step profile setup), dark/light theme toggle, and a free-tier + premium chat limit model.

---

## 🧰 Tech Stack

- **Frontend:** Vanilla HTML, CSS, and JavaScript — single self-contained file
- **AI:** Claude (Anthropic API) for the SoulSync conversational companion
- **Storage:** Browser `localStorage` for theme, mood logs, and session data (no backend/database yet)

---

## 🚀 Getting Started

Since this is a single static HTML file, you can run it directly:

```bash
git clone https://github.com/deepanshu-bisht-dev/MinDrift-.git
cd MinDrift-
```

Then simply open `mindrift_v5.html` in your browser.

> ⚠️ **Note on SoulSync (AI chat):** The chat feature calls the Anthropic API directly from the browser without an API key. This works when the file is run inside an environment that proxies the request (like a Claude Artifact), but **will not work as a standalone static file** unless you add your own backend or proxy to securely attach an API key. Never hardcode an Anthropic API key directly into client-side JavaScript in a public repo.

---

## 🗺️ Roadmap

- [ ] Move SoulSync's AI calls behind a secure backend/proxy
- [ ] Add a real database (currently all data lives in browser `localStorage`)
- [ ] Build user authentication properly (current sign-in/sign-up is front-end only)
- [ ] Expand TherapyBridge with real therapist data and booking persistence
- [ ] Add data export so users can keep their mood history

---

## 🤝 Connect

Always open to feedback, suggestions, or collaboration ideas.

- GitHub: [@deepanshu-bisht-dev](https://github.com/deepanshu-bisht-dev)

---

⭐ If you find this project useful or interesting, consider giving it a star!
