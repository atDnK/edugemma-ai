# 📚 TOEFLGemma AI — Offline TOEFL iBT Study Mentor

**TOEFLGemma AI** is a lightweight, privacy-first, offline study assistant powered by Google's **Gemma 2 (2B)** open-weight model. It is built specifically to help students and self-learners master TOEFL iBT skills without relying on paid subscriptions or active internet connections.

---

## ✨ Features

- **100% Offline Inference:** Operates locally via Ollama with zero internet dependency.
- **Task-Specific Templates:** Generates structured frameworks for Speaking (Tasks 1–4) and Writing (*Integrated* & *Academic Discussion*).
- **Academic Vocabulary Tutor:** Breaks down complex reading passages into simplified terms and context examples.
- **Zero Operating Cost & Full Privacy:** All practice essays, notes, and queries remain 100% private on your machine.

---

### How to Run Locally

1. Install [Ollama](https://ollama.com).
2. Pull the Gemma 2 model in your terminal:
   `ollama run gemma2:2b`
3. Load the custom system prompt from `Modelfile` into your preferred local Web UI or create a custom Ollama model:
   `ollama create toeflgemma -f Modelfile`

---

## 📄 License & Community

Built as part of the **Hacktoberfest 2026 Weekend Challenge: Build for a Friend**. Open-source under the MIT License.
