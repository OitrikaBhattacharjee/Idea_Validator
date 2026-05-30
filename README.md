# 🧠 The Idea Validator

> Pitch your startup idea to a room full of brutal, honest, AI-powered personas — and find out if your idea actually holds up.

![The Idea Validator](https://img.shields.io/badge/Built%20for-CodeStorm%202026-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Live-brightgreen)

---

## 💡 What is this?

Most people pitch their ideas only to friends who say *"wow that's amazing!"*

**The Idea Validator** puts your idea in front of 4 people who won't sugarcoat it:

| Persona | Who they are | What they do |
|--------|-------------|--------------|
| 💼 Alex Chen | Skeptical Investor | Pokes holes in your business model and market size |
| 🔍 Maya Osei | Harsh Critic | Finds every execution risk and logical gap |
| 🙋 Jordan Park | Excited Early Adopter | Shows you exactly who would love and use this |
| ⚔️ Sam Rivera | The Competitor | Tells you what you'd need to beat what already exists |

After all 4 react, you get a **Room Verdict** — an overall score across viability, originality, and market fit, plus your biggest strength and biggest risk.

---

## 🚀 Live Demo

👉 **[Try it here]**  https://courageous-madeleine-a4bbd5.netlify.app/ 

---

## 🎯 Why I built this

Every founder, student, or builder has had this problem: you think your idea is great, but you don't know how to stress-test it before you invest weeks building it.

Existing tools either give you generic feedback or require you to actually find and talk to real investors and critics — which most beginners can't access.

I wanted to build something that simulates a real pitch room: fast, honest, and accessible to anyone with an idea.

---

## ⚙️ How it works

1. You type your idea into the text box
2. The app calls the Claude AI API **4 times simultaneously** — once per persona
3. Each persona responds with their honest reaction in character
4. A 5th API call synthesizes everything into a final verdict with scores
5. Results load in parallel so it's fast

**Tech stack:**
- Pure HTML, CSS, JavaScript (no frameworks, no build tools)
- Anthropic Claude API (`claude-sonnet-4-20250514`)
- Deployed on Netlify

---

## 🖥️ Run it locally

No installation needed. Seriously.

1. Download `index.html`
2. Open it in any browser
3. That's it

> **Note:** The Claude API is called client-side. For production use, move the API call to a backend to protect your key.
> **To enable AI responses:** Get a free API key from console.anthropic.com and add it to the fetch headers in index.html as `"x-api-key": "your-key-here"` and `"anthropic-version": "2023-06-01"`

---

## 📁 Project Structure

```
idea-validator/
│
├── index.html          # The entire app — one file
└── README.md           # You're reading this
```

---

## 🏆 Built for CodeStorm 2026

This project was built during **CodeStorm 2026 — Month 1: Build the Future of the Web.**

- Track: AI-powered web utility
- Category: Next-Generation Web Experiences
- Built by: Oitrika Bhattacharjee on May 30, 2026

---

## 📄 License

MIT License — © 2026 Oitrika Bhattacharjee

You're free to use, share, and modify this. Just keep the credit.

---

## 🙋 About the builder

Built by **Oitrika Bhattacharjee** — https://github.com/OitrikaBhattacharjee

*If this helped you stress-test an idea, give it a ⭐ — it means a lot.*
