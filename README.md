# 🌌 Hecos — Helping Companion System | The Soul of Private, Modular Intelligence

**The Native Modular AI Operating Layer — Privacy · Speed · Simplicity**

*Hecos lives on your computer. Your memories, your data, your privacy remain on your computer.*

<p align="center">
<img src="https://github.com/Hecos-Project/Hecos-Assets/raw/main/Hecos%20CodeName%20Ghost%20Fire.jpg" width="600">
</p>

<p align="center">
  <strong>💡 Hecos is your everyday companion.</strong><br>
  Talk to it, command it, or let it run on its own — it manages your computer, sends messages, automates workflows, and switches personality to act as a butler, a friend, or whatever you need.<br>
  <em>No AI required: Hecos works just as well through automation flows and direct commands.</em>
</p>

<p align="center">
  🛠️ <strong>Under the Hood (For Developers & Power Users):</strong><br>
  Starting from <code>v0.53.0</code> (Codename: <strong>Phase II Ghost Fire</strong>), Hecos has evolved into a fully fledged, distributed modular platform. The ecosystem features a decoupled <strong>Client-Server architecture</strong> consisting of a headless CLI Core (the backend server) and an advanced WebUI (the client). The system synchronizes an interactive Chat view, a real-time <strong>Control Room</strong> powered by live telemetry widgets, and <strong>Hecos Flows</strong>—a visual automation engine that executes workflows with or without LLM overhead. <br><br>
  Infrastructure utilities include a unified configuration panel (<strong>Central Hub</strong>), an integrated <strong>Presenter</strong> engine for real-time live commentary and voice briefings, a secure remote file manager, an integrated proxy routing system, granular <strong>Direct Commands</strong>, dynamic Voice/VAD pipelines, and a centralized backup engine. Extensions are handled natively through the <strong>Hecos Package Manager (HPM)</strong>, fetching installable <code>.hpkg</code> components (including PC/Browser Automation, Messenger bridges, Mail clients, Playbooks, and RAG Semantic Memory vaults) directly from the newly integrated <strong>Hecos Store</strong>.
</p>

---

### 🏛️ What is Hecos?

Hecos is a **modular AI Operating Layer** — not a chatbot, not a simple agent. It is a full-stack platform that bridges natural language, desktop automation, and scheduled workflows into a single, unified system using a robust Client-Server design.

At its heart lies the **Hecos Package Manager (HPM)**, a centralized architecture that makes the platform infinitely extensible. You can interact with it by voice or text, trigger actions manually through **Direct Commands**, build complex pipelines with the visual **Flows Engine**, or simply let it run in the background. 

#### 💡 Our Philosophy
Hecos was not created for abstract labels like "Digital Sovereignty" or "Sovereign AI"—concepts that hold no weight in a technological landscape destined to evolve radically into completely different forms. Digital technology is merely a current tool, not the final destination. Furthermore, traditional analog technology should not be discarded; both analog and digital mediums possess unique, valuable advantages. Hecos is built upon a single, core mission: **to improve human life**, regardless of whether the driving technology is digital, analog, or a more advanced evolution yet to come.

---

### 🚀 Key Capabilities

* **🗣️ Natural Conversation & Voice** — Talk to Hecos like a person. It understands context, remembers your preferences, and responds with low-latency real-time text-to-speech (featuring both Kokoro TTS and Piper TTS for natural, high-fidelity local voice generation).
* **📢 Presenter & Playbooks (Training, Coach, Roleplay)** — A real-time narrative and live commentary engine natively integrated into the Core. Paired with installable **Playbook modules**, Hecos transforms into a versatile interactive personal coach, guided training system, roleplay engine, language learning mentor, and step-by-step procedural companion.
* **🌐 Global Presets (Soul Profiles) & Inline Chat Overrides** — Freely combine AI personalities, TTS voices, inference parameters, and LLM backends into cohesive master profiles. Hot-swap models, personas, and voices on the fly directly inside the chat interface.
* **🧠 RAG Semantic Memory Vaults** — Native vector-based semantic memory (ONNX FastEmbed & LanceDB) allowing the system to securely store, recall, and contextualize interactions permanently with per-user vault isolation.
* **🤖 PC & Browser Automation** — Execute deep operating system bridging and browser control execution loops to handle tasks, extract web data, and script actions natively.
* **🔌 Messenger & Mail Integrations** — Multi-network messenger bridges and mail orchestration tools to coordinate incoming/outgoing communications natively.
* **⚡ Direct Commands (HDCS)** — Trigger 150+ native system actions instantly with a keyword command, bypassing the AI reasoning loop completely. Fast, predictable, and 100% offline-first.
* **🔀 Flows Automation Engine** — A visual drag-and-drop node-based canvas for building complex multi-step automations: schedules, triggers, conditions, and AI-powered steps — all in one unified workspace.
* **📦 8-Layer Modular Ecosystem (HPM)** — An advanced package management standard with Pydantic+TOML manifests, Ed25519 cryptographic integrity verification (`/verify`), and sub-process sandbox isolation.
* **🔑 Universal Backend & Key Manager** — Seamlessly switch between local backends (Ollama, Llama.cpp, KoboldCpp via LiteLLM) and cloud providers, backed by a robust multi-key credential vault.
* **🌐 Universal Tool Hub (MCP Bridge)** — Native support for the Model Context Protocol to connect with thousands of external tools, databases, and APIs.
* **📋 Lists, Alarms & Reminders** — Native time orchestration fully integrated with voice pipelines and active desktop notifications.
* **🔒 3-Tier Privacy Architecture** — Operates entirely on your hardware with Normal, Auto-Wipe (RAM-only store, cleared on exit), and Incognito (zero-trace) privacy modes.

---

### 🎭 The Soul of the Machine: Infinite Personalities & Native Personas

A fundamental capability of Hecos is its native **Personality Switching**. Hecos isn't just a cold, rigid assistant — it adapts its behavior, tone, and character based on the persona you load. Each persona is programmed to act differently and fulfill a unique role in your daily life.

With the new **Inline Chat Overrides**, you can override the AI Model, Persona, and Voice directly within the chat interface on the fly, allowing you to create infinite custom personalities instantly for each conversation session.

<p align="center">
  <img src="https://github.com/Hecos-Project/.github/blob/main/profile/Urania_9800_Logo_2.png" width="600">
  <br>
  <em>Urania 9800, the official Hecos Mascot and your everyday friendly companion.</em>
</p>

Out of the box, Hecos includes several pre-configured personalities:
* **Hecos System Soul** — The neutral, rigid, and detached core system. Perfect for raw automation and precise tasks.
* **Urania 9800** — The lively mascot. A true, everyday friend designed for casual, empathetic, and cheerful interaction.
* **Sebastian Pro** — The perfect, highly professional British-style butler. Polite, efficient, and eager to serve.
* **Atlas** — The imposing, authoritative digital guardian.
* **Nova X-01** — A precise, analytical robotic entity for those who prefer purely logical interactions.

You can hot-swap these personas at any time, changing not just the voice and tone, but the very "soul" of the system.

---

### 🖥️ The Hecos WebUI Overview

Hecos operates primarily through its advanced WebUI — a sophisticated interface elegantly divided into five main pillars: the **System Icontray**, the **Chat**, the **Central Hub**, the **Control Room**, and **Hecos Drive**. Here is a sneak peek of the platform in action:

<p align="center">
  <img src="https://github.com/Hecos-Project/.github/blob/main/profile/003_HecosChat_001.png" width="800">
  <br>
  <em><strong>The Chat:</strong> Your primary interaction point, complete with sidebar controls and fast persona switching.</em>
</p>

<br>

<p align="center">
  <img src="https://github.com/Hecos-Project/.github/blob/main/profile/004_HecosChat_Direct_Commands.png" width="800">
  <br>
  <em><strong>Direct Commands:</strong> Bypass the AI completely. Use slash commands like `/hpm search` to trigger actions with zero latency.</em>
</p>

<br>

<p align="center">
  <img src="https://github.com/Hecos-Project/.github/blob/main/profile/005_HecosChat_Direct_ControlRoom_integrata.png" width="800">
  <br>
  <em><strong>Integrated Control Room:</strong> Monitor system hardware, active AI flows, and agent statuses via live telemetry widgets.</em>
</p>

<br>

<p align="center">
  <img src="https://github.com/Hecos-Project/.github/blob/main/profile/008_HecosCentralHub_002.png" width="800">
  <br>
  <em><strong>Central Hub:</strong> The nerve center. Configure every aspect of your local AI, from text-to-speech to custom module routing.</em>
</p>

<br>

<p align="center">
  <img src="https://github.com/Hecos-Project/.github/blob/main/profile/012_Hecos_Flows_003.png" width="800">
  <br>
  <em><strong>Flows Engine:</strong> Build complex, interactive automations and multi-step tasks using the visual drag-and-drop canvas.</em>
</p>

<br>

<p align="center">
  <img src="https://github.com/Hecos-Project/.github/blob/main/profile/Tray_Dashboard_002.png" width="800">
  <br>
  <em><strong>System Tray Dashboard:</strong> The foundational native control panel. Monitor live logs, create centralized backups, and connect your phone via QR code.</em>
</p>

<br>

**Want to see more?** For a complete visual tour of all the interface components, including the Native File Manager, visit the official website:

👉 **[Take the full WebUI Tour (hecos-project.github.io/tour.html)](https://hecos-project.github.io/tour.html)**

---

### 🛍️ The Hecos Store

Hecos is designed to grow with you. Thanks to the **Hecos Package Manager (HPM)**, the system is infinitely expandable through modular packages (`.hpkg`). In Hecos, plugins are only one part of the picture—the store hosts a rich variety of **installable modules** across all architectural layers:

* **🧩 Plugins & System Apps:** Deep hardware access, OS automation, browser scripting, image generation, messenger bridges, and system tooling.
* **📱 Autonomous Apps:** Full standalone web applications and productivity suites running entirely locally within Hecos.
* **⚙️ Core Modules & Libraries:** Extensible foundational components, shared backend libraries, and utility runtimes.
* **🎭 Personas & Soul Profiles:** New AI behavioral models, custom system prompts, and distinctive characters with curated voice profiles.
* **📚 Playbooks (Training, Coach & Roleplay):** Interactive instructional guides, training simulations, language tutors, coaching workflows, and scenario roleplays powered by the Presenter engine.
* **📊 Control Room Widgets:** Real-time monitoring cards, telemetry displays, quick-control toggles, and dashboard components.
* **🎨 UI Themes:** Curated aesthetic styles, custom palettes, and interface enhancements.
* **⚡ Skill Packs & MCP Servers:** Extra slash commands and universal tool bridges connecting to external APIs and protocols.

👉 **[Explore the Hecos Store (hecos-project.github.io/store/)](https://hecos-project.github.io/store/index.html)**

---

### 🛠️ Project Status

Now at **v0.53.0** under the codename **Phase II: Ghost Fire**. The core distributed architecture is stable, the **HPM ecosystem** is actively expanding with modular packages, the **Presenter & Playbook** training engines are integrated, and the visual Flows automation engine is ready for deployment.

---

### 🤝 Join the Evolution

We believe in open collaboration. Whether you are a developer, a designer, or a visionary, you are welcome in the Hecos ecosystem.

* 🌐 **Website:** [hecos-project.github.io](https://hecos-project.github.io)
* 📖 **Documentation:** [Hecos Wiki](https://github.com/Hecos-Project/Hecos/wiki)
* 📺 **YouTube:** [@Hecos-Project](https://www.youtube.com/@Hecos-Project) — [https://www.youtube.com/@Hecos-Project](https://www.youtube.com/@Hecos-Project)
* 📧 **Contact:** [hecos.project@gmail.com](mailto:hecos.project@gmail.com)
* ⚖️ **License:** AGPL v3

> *"The future isn't just automated. It's yours."*
