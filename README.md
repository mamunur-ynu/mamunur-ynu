# Hi, I'm Mamunur 👋

Second-year **Artificial Intelligence** student at **Yunnan University**, Kunming, China — originally from Sundarganj, Bangladesh.

I like taking coursework ideas further than the assignment asks, and turning them into things people can actually open and use.

---

### 🚍 Smart Campus Bus Tracker

A campus shuttle tracker and route optimizer that began as a C++ data-structures project and grew into a live full-stack product.

**[▶ Try it live](https://ynu-bus-tracker.netlify.app)**

- **Dijkstra route optimization** — shortest path between any two campus stops, re-routing live when a delay is applied
- **3D campus city** (Three.js) — buses drive the real route loops, pause at stops, and obey traffic lights with second-countdowns
- **AI assistant** — an LLM agent that calls the routing engine as a *tool*, so quoted travel times are computed, never hallucinated
- **Real-time cloud** — Supabase Postgres, live multi-device sync, admin-gated editing
- Bilingual EN / 中文, installable PWA, 16 unit tests, deployed by CI/CD on every push

| | |
|---|---|
| Web app — React · TypeScript · Three.js · Supabase | [repo](https://github.com/mamunur-ynu/ynu-bus-tracker-app) |
| Original C++ system — OOP · STL · Dijkstra | [repo](https://github.com/mamunur-ynu/yunnan-university-smart-campus-bus-tracker) |

---

### 🎓 Preluma — AI-powered adaptive learning platform

A Streamlit platform that turns passive pre-class reading into a guided, AI-assisted workflow: an AI brief, worked examples, an adaptive quiz, a mistake clinic, and teacher-facing analytics.

**[▶ Try it live](https://prelumaedtech.streamlit.app/)** · [repo](https://github.com/mamunur-ynu/Preluma-edtech)

- **8 LLM providers behind a sequential failover chain** — free-tier endpoints rate-limit constantly, so the tutor stays available through individual outages
- Dual-mode persistence: Supabase (12 tables) with a local fallback
- 11,310 lines across 15 Python modules, 13 pytest suites
- *My part in this three-person team: core platform, UI, AI provider layer, authentication, system architecture*

---

### 🛠️ Working with

`Python` · `TypeScript` · `C++` · `React` · `Streamlit` · `Three.js` · `Supabase / PostgreSQL` · `LLM APIs` · `Git` · `CI/CD` · `pytest` · `Vitest`

### 📫 Reach me

- Email: **mamunurmim07@gmail.com**
- LinkedIn: [mimynu](https://www.linkedin.com/in/mimynu)
- Live demo: [ynu-bus-tracker.netlify.app](https://ynu-bus-tracker.netlify.app)
