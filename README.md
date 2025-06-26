# scam-shield-partizan
This is a community project to protect unprotected from a phone scam schemes.

ScamShield Partizan is an open-source, community-driven project to build a **free, offline, AI-powered scam protection system**—designed specifically for vulnerable users in the Baltic region (but useful worldwide).

No clouds. No data leaks. No subscriptions.
Just real-time scam protection using on-device AI and voice processing.

---

## ❓ What Is This?

Every day, scammers use robocalls and AI-generated voices to trick elderly and isolated people out of their savings.

We're building a smart voice assistant that:
- **Screens unknown callers**
- **Verifies legitimacy before allowing access**
- **Blocks shady behavior**
- **Works completely offline**

---

## 🧠 Core Tech Pillars

- **STT**: Speech-to-Text — Convert caller’s voice to text
- **LLM**: Small Language Model — Analyze speech patterns
- **TTS**: Text-to-Speech — Talk back like a digital bodyguard
- **RAG-style Memory**: Extend AI intelligence with known scam pattern library
- **Local Storage**: Store call logs, verdicts, threat fingerprints — all offline

---

## 📦 Implementation Scenarios

### 1. 💾 Full Local (Android Native)

- **STT/TTS**: Use Android’s built-in voice APIs
- **LLM**: Run a quantized on-device model (e.g. Phi, SmolLM, or Qwen)
- **DB**: SQLite + lightweight local pattern matcher
- ✅ Smallest footprint, works even offline in a shed

### 2. 🔊 Full Local (Custom Stack)

- **STT**: Whisper Tiny/Base or Vosk
- **TTS**: Piper or Coqui TTS
- **LLM**: Local language model (e.g. MobiLlama, OpenELM)
- ✅ More control and accuracy, but heavier runtime

### 3. ☁️ Hybrid (Native + Cloud)

- **STT/TTS**: Android native
- **LLM**: Remote cloud inference endpoint (configurable)
- ✅ Best responsiveness + fallback for older devices

Each option supports:
- 🧠 Pattern memory (RAG-style augmentation)
- 💾 Persistent offline DB (call logs, scam tags, user feedback)

---

## 💌 Get Involved

- 🔧 Developers (mobile, AI, backend)
- 🗣️ Linguists (Latvian, Russian, English)
- 🎨 Designers (UX for elderly users)
- 🕵️ Security nerds (threat detection logic)
- 🧠 Curious humans who want to protect people

Start here 👉 [CONTRIBUTING.md coming soon]

---

## 📍 Status

🧪 Alpha. MVP design in progress.  
📂 GitHub structure coming together.  
💬 Initial architecture discussions in Discord/Telegram.

---

## ❤️ Why It Matters

Scam calls don’t just steal money. They steal peace of mind.

We believe:
- Digital protection should be a right, not a luxury
- Privacy must be default, not a checkbox
- Community-built software can outperform corporate bloatware

Read the [MANIFESTO.md](MANIFESTO.md) to understand the vision.

---
