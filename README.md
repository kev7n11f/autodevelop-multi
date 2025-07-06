# 🧠 autodevelop.ai — Build Bots. Launch Ideas. Monetize Magic.

Welcome to **autodevelop.ai**, a lightweight platform designed to help creators turn their concepts into revenue-generating digital assistants with zero coding required.

## 🚀 What Is This?

`autodevelop.ai` empowers users to:

- 🎭 Launch AI assistants with customizable personas
- 🎨 Apply brand-ready styling and copy across use cases
- 💬 Test user interactions and dynamically route messaging
- 💸 Explore monetization paths like subscription tiers and creator spotlights

Think of it as an MVP for democratized bot creation—whether you're a creator, founder, or curious innovator.

---

## 🔧 Project Structure (Next.js 15)

- `pages/index.js` — Public homepage with CTA, feature showcase, and dynamic scroll navigation
- `components/ChatModal.js` — Modal assistant with persona detection and conversation state
- `utils/detectMode.js` — Keyword-based routing logic for personalized assistant context
- `prompts/` — Mode-specific prompt scaffolding (`store.js`, `golf.js`, `revenue.js`, `portal.js`)
- `pages/api/chat/route.js` — Backend endpoint for streaming AI responses per user input

All routing follows traditional `pages/` architecture (no `app/` directory).

---

## ✨ Features

- 🧠 Multi-persona assistant routing
- 🎨 Custom branding blocks (`Manifesto`, `Spotlight`)
- 🔗 Stripe-ready monetization logic
- 📈 Smart mode detection on assistant launch
- 💬 Server-side response streaming via `/api/chat/route.js`

---

## 📦 Getting Started

```bash
# Install dependencies
npm install

# Start dev server
npm run dev# autodevelop-multi
