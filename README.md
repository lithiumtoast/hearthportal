# HearthPortal 🔥🚪

**One address. Your AI. Your hardware. Your rules.**

🚧 UNDER CONSTRUCTION! 🚧 See roadmap section for more details.

## 🔥 What is HearthPortal?

Your AI models run on your hardware using [`Ollama`](https://github.com/ollama/ollama) or alternatives. Locked down under your safety, guidance, and rules. The portal is a static website that runs locally or hosted for free using [GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages). Use it personally completely offline, or share it with people you trust like your own community, friends, or family.

- **One address** `https://yourname.github.io/hearthportal`
- **Your hardware** You paid for the hardware, it should do what *you* want.
- **Your data** Locked down in an environment you control. Your home, your rules.
- **Your models** Run what you want, when you want.
- **Your privacy** No cloud, no tracking, no corporate surveillance.

## 🚪 Why "HearthPortal"?

A **hearth** is the heart of the home where family gathers, stories are shared, and fire is kept safely contained. A **portal** is a doorway between worlds.

HearthPortal is both: a warm, inviting doorway to your private AI. One address that opens into a world where you, your family, or your community can safely explore, learn, and use AI that runs on your hardware, under your control.

### ✨ The Vision for Everyone

> *"Access to computers and anything that might teach you something about the way the world works should be unlimited and total. Always yield to the Hands-On Imperative!"*
> — Steven Levy, *Hackers: Heroes of the Computer Revolution* pg 28, talking about Hacker Ethic.

> *"Chouinard decided he needed to make his own gear. At the very least, doing so would give him control of the equipment he was counting on to save his life. Perhaps he could make some money at it, too.”*
> — David Gelles' *Dirtbag Billionaire* pg 29, talking about Yvon Chouinard rock climbing and going on to found Patagonia.

Wield the fire of AI the way you want with unlimited access, total control, and the satisfaction of knowing you built it yourself. Hands on, from the metal up.

#### 👤 For Individuals

Your personal AI, always with you. One address from any device. Your thoughts, your models, total privacy.

#### 👨‍👩‍👧 For Families

Kids can't stop asking questions? Fuel their curiosity with AI you deem safe under your rules. Review interactions for things you deem inappropriate. No data leaving your home. One address for the whole family.

#### 👥 For Circles of Friends

Shared AI for your group: game nights, trip planning, common interests. One address for friends. No corporate listening, no age or identity verification, just friends.

#### 🏢 For Small Businesses

Internal knowledge base, employee onboarding, policy Q&A. Vertically scale your employees with custom workflows. Company data stays on your hardware. No third-party training on your intellectual property.

#### 🧑‍🏫 For Classrooms

AI tutor for your students, private and focused. Set rules to encourage problem solving without just giving the answer. Lock out the internet; instead use trusted reference information such as specific textbooks and professor notes. Create custom exams where no two students will have the same questions and answers for grading. No student data mined. One address for the whole class. Portal works on school hardware such as Chromebooks, no install.

## 🌍 The Community

HearthPortal is free and open source, forever. Built on the belief that AI should be something we participate in, not something done to us. We follow the principles of [the open source way](https://www.theopensourceway.org): transparency, collaboration, and releasing early and often.

> *"The primary and continual focus for a project is to take good care of your users, for some of them will become your contributors, and you want them to do it out of love more than resentment."*
> — *The Open Source Way*

### Join Us

- **Ask and help others** — Ask questions and help others in [Discussions](https://github.com/lithiumtoast/hearthportal/discussions).
- **Contribute code** — [Pull Requests](https://github.com/lithiumtoast/hearthportal/pulls) are welcome for new features, bug fixes, documentation so long as they are in good faith and aligned with the vision.
- **Spread the word** — The more people run their own AI, the healthier the ecosystem.

## 🗺️ Roadmap

HearthPortal is in active development. Here's where we're headed.

### ✅ Phase 0: Foundation (Current)

- [x] Core concept and vision defined
- [x] Name and brand established: HearthPortal 🔥🚪
- [x] Tagline: "One address. Your AI. Your hardware. Your rules."
- [x] README with vision, audience examples, and Hacker Ethic foundation
- [] Architecture design: Hearth Portal (UI) + Hearth Keep (proxy)
- [] GitHub repository setup

### 🚧 Phase 1: Core Functionality (In Progress)

- [ ] Hearth Portal — Blazor WebAssembly frontend
  - [ ] Basic chat interface
  - [ ] Model selection dropdown
  - [ ] Conversation history (local storage)
  - [ ] Settings page for server URL
  - [ ] GitHub Pages deployment documentation

- [ ] Hearth Keep — Authentication proxy
  - [ ] JWT authentication flow
  - [ ] API key validation (one-time, never stored)
  - [ ] Token refresh mechanism
  - [ ] Rate limiting
  - [ ] Token revocation
  - [ ] Docker image for easy deployment
  - [ ] Systemd service example

- [ ] Ollama integration
  - [ ] Support for /api/generate
  - [ ] Support for /api/chat
  - [ ] Support for /api/tags (model listing)
  - [ ] Streaming response support

### 🏠 Phase 2: Home & Family Features

- [ ] Multi-user support with profiles
- [ ] Parental controls and content filtering
- [ ] Usage quotas per user (time or requests)
- [ ] Conversation review dashboard for parents/teachers
- [ ] Guest access mode (no login required, limited functionality)
- [ ] Kid-friendly UI theme

### 🌱 Phase 3: Ecosystem Expansion

- [ ] **Hearth Stories** — Conversation memory and search
- [ ] **Hearth Forge** — Model fine-tuning interface
- [ ] **Hearth Lens** — RAG (Retrieval Augmented Generation) with your documents
  - [ ] Upload PDFs, text files, websites
  - [ ] Semantic search over personal knowledge base

- [ ] **Hearth Prism** — Multi-model orchestration
  - [ ] Route queries to best model
  - [ ] Ensemble responses from multiple models

- [ ] **Hearth Ember** — Mobile companion app
  - [ ] Voice input
  - [ ] Push notifications
  - [ ] Offline cache of recent conversations

### 🔌 Phase 4: Integrations & Extensibility

- [ ] Plugin system for custom tools
- [ ] Webhooks for automation
- [ ] API for third-party integrations
- [ ] Home Assistant integration
- [ ] Calendar and email integration
- [ ] Smart home control via local models

### 🌍 Phase 5: Community & Sustainability

- [ ] Contributor documentation and onboarding
- [ ] Community showcase of custom deployments
- [ ] Regular release cadence
- [ ] Translation into multiple languages
- [ ] Accessibility improvements
- [ ] Environmental impact dashboard
  - [ ] Show CO2 saved by running locally vs. cloud
  - [ ] Energy consumption tracking

---

## 🤝 How to Help

We're in Phase 0 and looking for contributors who believe in the mission. If you want to help:

- **Star the repo** to show support.
- **Open an issue** for bugs or feature requests.
- **Share your use case** in Discussions.
- **Contribute code** — PRs welcome for anything on the roadmap.
- **Spread the word** — The more people run their own AI, the healthier the ecosystem.

---

As Lee Felsenstein might say, *"I have seen the future and it needs work."*

**Help us build it.**