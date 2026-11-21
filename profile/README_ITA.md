<p align="center">
  🌐 <a href="https://github.com/Hecos-Project">🇬🇧 English</a> ·
  <strong>🇮🇹 Italiano</strong> ·
  <a href="https://github.com/Hecos-Project/.github/blob/main/profile/README_ESP.md">🇪🇸 Español</a>
</p>

<h1 align="center">🌌 Hecos — Helping Companion System</h1>

<p align="center">
  <strong>L'Anima dell'Intelligenza Privata e Modulare · Privacy · Velocità · Semplicità</strong><br>
  <em>Hecos vive sul tuo computer. I tuoi ricordi, la tua voce, le tue creazioni e la tua privacy restano con te.</em>
</p>

<p align="center">
  <a href="https://hecos-project.github.io">🌐 Sito Ufficiale</a> ·
  <a href="https://hecos-project.github.io/store/index.html">🛍️ Hecos Store</a> ·
  <a href="https://hecos-project.github.io/tour.html">🖥️ Tour WebUI</a> ·
  <a href="#download">⚡ Scarica &amp; Installa</a> ·
  <a href="https://github.com/Hecos-Project/Hecos">🧠 Hecos Core</a> ·
  <a href="https://github.com/Hecos-Project/Hecos-Tray">🚀 Hecos Tray</a> ·
  <a href="https://github.com/Hecos-Project/Hecos/wiki/00_introduction_it">📖 Wiki (IT)</a> ·
  <a href="https://www.youtube.com/@Hecos-Project">📺 YouTube</a>
</p>

> ### ⚡ Motto Fondamentale
> **"Zero filtri morali. Zero pregiudizi sociali. Zero agende politiche. Dal motore centrale a ogni singolo modulo, Hecos nasce su una sola regola incrollabile: la libertà di pensiero appartiene a tutti."**

<p align="center">
  <img src="https://github.com/Hecos-Project/Hecos-Assets/raw/main/Hecos%20CodeName%20Ghost%20Fire.jpg" width="600" alt="Hecos — Phase II: Ghost Fire">
</p>

<p align="center">
  <strong>💡 Non un chatbot. Un compagno digitale vivo, sul tuo computer.</strong><br>
  Parlagli a voce o via testo, progetta insieme lavori creativi o tecnici complessi, automatizza il tuo PC o lascialo agire silenziosamente in background — cambiando personalità in un attimo, da un'amica empatica a un maggiordomo impeccabile, un direttore creativo o un coach concentrato.<br>
  <em>E quando non ti serve, l'AI non è nemmeno obbligatoria: Hecos funziona altrettanto bene tramite flussi di automazione visuali e comandi diretti istantanei.</em>
</p>

<p align="center">
  <sub>
    <strong>Indice Rapido:</strong>
    <a href="#download">⚡ Scarica &amp; Installa</a> ·
    <a href="#personas">🎭 Personalità &amp; Voce</a> ·
    <a href="#capabilities">✨ Capacità</a> ·
    <a href="#store">🛍️ Hecos Store</a> ·
    <a href="#visual-tour">🖥️ Tour Visivo</a> ·
    <a href="#philosophy">💡 Filosofia</a> ·
    <a href="#ecosystem">🧭 Ecosistema &amp; Link</a>
  </sub>
</p>

---

<a id="download"></a>

### ⚡ Scarica & Installa Hecos — Installer Grafico Ufficiale

<p align="center">
  <a href="https://github.com/Hecos-Project/Hecos/releases/latest/download/INSTALL_HECOS_WINDOWS.zip">
    <img src="https://img.shields.io/badge/Scarica_Installer-Windows_(ZIP)-00e5ff?style=for-the-badge&logo=windows&logoColor=080a12" alt="Scarica Installer Hecos per Windows">
  </a>
  &nbsp;
  <a href="https://github.com/Hecos-Project/Hecos/releases/latest/download/INSTALL_HECOS_LINUX.zip">
    <img src="https://img.shields.io/badge/Scarica_Installer-Linux_%2F_macOS_(ZIP)-5b7dff?style=for-the-badge&logo=linux&logoColor=white" alt="Scarica Installer Hecos per Linux e macOS">
  </a>
  &nbsp;
  <a href="https://github.com/Hecos-Project/Hecos/releases/latest">
    <img src="https://img.shields.io/badge/Tutte_le_Release-GitHub-181c2e?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Releases">
  </a>
</p>

<p align="center">
  <strong>Zero prerequisiti — NON serve avere Python installato sul PC.</strong><br>
  L'installer grafico ufficiale a 5 step configura automaticamente un Python 3.11 portatile isolato (verificato con SHA256), installa le dipendenze testate, collega Core &harr; Tray e ti permette di installare Hecos su <strong>qualsiasi disco o cartella</strong>.
</p>

1. **Scarica ed estrai** l'archivio ZIP per il tuo sistema operativo.
2. **Windows:** fai doppio clic su **`INSTALL_HECOS_WINDOWS.bat`** *(se Windows SmartScreen mostra un avviso, clicca **Ulteriori informazioni → Esegui comunque**)*.
3. **Linux / macOS:** esegui **`bash INSTALL_HECOS_LINUX.sh`** *(oppure da terminale: `curl -fsSL https://raw.githubusercontent.com/Hecos-Project/Hecos/main/INSTALL_HECOS_LINUX.sh | bash`)*.
4. Segui i **5 step della finestra guidata**: scegli **Hecos Completo (Core + Tray — Consigliato)**, **Solo Core** oppure **Solo Tray**, seleziona la cartella e clicca **Avvia Hecos adesso**.

<details>
<summary>💻 <strong>Opzioni Alternative di Installazione (CLI, Server Linux &amp; Tray Standalone)</strong></summary>

<br>

* **Installer da Riga di Comando & Diagnostica (`Doctor`):** `scripts/windows/setup/HECOS_SETUP_WIZARD.bat` oppure `scripts/linux/setup/HECOS_SETUP_WIZARD.sh` (supporta `--unattended`, `--doctor`, `--gui` e `Quick Repair`).
* **Global Launcher da Terminale (senza Tray):** avvia `HECOS GLOBAL LAUNCHER.bat` / `HECOS GLOBAL LAUNCHER.sh` dentro la cartella di Hecos per lanciare WebUI, Console, Coding Studio CLI o Doctor.
* **Setup Standalone dalla Tray:** puoi comunque installare [Hecos-Tray](https://github.com/Hecos-Project/Hecos-Tray) separatamente tramite `HECOS_TRAY_SETUP.bat` / `.sh` — entrambi gli installer condividono lo stesso registro `install.toml`.
* 📖 [Leggi la Guida Rapida completa (IT)](https://github.com/Hecos-Project/Hecos/wiki/01_quick_start_it)

</details>

---

<a id="personas"></a>

### 🎭 L'Anima della Macchina: Personalità & Voce Viva

La maggior parte degli strumenti AI sembra fredda, identica e impersonale. **Hecos è progettato per avere presenza.**

Il suo **Personality Switching** nativo non cambia soltanto qualche parola, ma l'intero carattere, il ruolo e la voce del sistema in un istante. Apri il **Preset Manager (`F3`)** direttamente nella chat per cambiare al volo modello AI, personalità, voce, modalità di ragionamento e strumenti attivi — come bozza istantanea per la conversazione corrente oppure salvato come Preset Globale riutilizzabile.

<p align="center">
  <img src="https://github.com/Hecos-Project/.github/blob/main/profile/Urania_9800_Logo_2.png" width="600" alt="Urania 9800 — Mascotte Ufficiale di Hecos">
  <br>
  <em><strong>Urania 9800</strong> — la mascotte ufficiale di Hecos e la tua compagna quotidiana, vivace ed empatica.</em>
</p>

**Pronte all'uso fin dal primo avvio** (con tante altre personalità scaricabili dall'[Hecos Store](https://hecos-project.github.io/store/index.html), tra cui *Motoko Kusanagi*, *Teacher* e le edizioni *Presenter*):

| Personalità | Carattere e Ruolo |
| :--- | :--- |
| ✨ **Urania 9800** | La vivace mascotte ufficiale — calorosa, empatica, spontanea e naturale per la vita di ogni giorno. |
| 🎩 **Sebastian Pro** | Il perfetto maggiordomo in stile britannico — cortese, impeccabile, proattivo ed efficiente. |
| 🛡️ **Atlas** | Un guardiano digitale autorevole e solido, ideale per concentrazione e comando. |
| 🤖 **Nova X-01** | Nitida, analitica e puramente logica per dialoghi tecnici e strutturati. |
| ⚙️ **Hecos System Soul** | Neutra, essenziale e diretta — perfetta per esecuzione pura e automazioni senza fronzoli. |

#### 🎙️ Voci Davvero Vive — 100% in Locale
Hecos affianca a ogni personalità una **Matrice Vocale Neurale** che gira direttamente sul tuo hardware:
* **Voice Forge Studio** — scolpisci, analizza (Formanti, Spettrogramma, profilo vocale Radar) e fonde voci personalizzate in tempo reale.
* **4 Motori TTS Neurali Locali** — tra cui **Fish Speech** con clonazione vocale zero-shot istantanea, **Kokoro** (con gestore di voice cloning integrato), **Piper** e **XTTS v2**, così Hecos ti risponde con bassissima latenza e zero streaming sul cloud.

---

<a id="capabilities"></a>

### ✨ Cosa Puoi Fare Davvero con Hecos

#### 📋 Multimodal Action Plans — *Prima Progetta, Poi Crea Senza Intoppi*
Una delle innovazioni simbolo di Hecos: invece di buttarsi alla cieca su attività complesse, attiva **`Plan First`** (o digita `/plan`) e co-progetta un **Blueprint** strutturato (`v1`, `v2`…) prima che venga eseguito un solo strumento. Una volta approvato, clicca **`Execute Plan`** (oppure avanza un passo alla volta con **`Next Step`**) e guarda Hecos orchestrare l'intero flusso in qualsiasi dominio:
* 💻 **Sviluppo Software** — piani architetturali multi-file eseguiti attraverso **Hecos Coder**.
* 📸 **Shooting Fotografici & Storyboard** — sequenze visive multi-scatto coerenti dirette da **Hecos Storyboard & Photo Director** + **Image Generation**, preservando identità del soggetto, luci e continuità da uno scatto all'altro.
* 🗺️ **Ricerca, Viaggi & Workflow Quotidiani** — sintesi web approfondite, dossier strutturati, itinerari e checklist guidati da **Hecos Action Planner**.

Ogni piano supporta modifica dal vivo, cambio modello/preset con **`Run with Preset`**, ripresa automatica tramite checkpoint (**AgentResume**), scheda mobile o **Pop-out Viewer multi-monitor**, salvataggio automatico in Markdown nella libreria media ed Export/Import in un clic (`.md`, `.html` stampabile lossless, `.yaml`, `.json`).
👉 [Leggi la Guida ai Multimodal Action Plans (IT)](https://github.com/Hecos-Project/Hecos/wiki/29_action_plans_it)

#### 📡 Presenter & Playbooks — *Coach Live, Tutor e Roleplay*
Il **Presenter** nativo porta narrazione live e briefing vocali in tempo reale direttamente nella tua area di lavoro. Abbinalo ai moduli **Playbook** installabili e Hecos si trasforma in un **coach personale interattivo, tutor di lingue straniere, simulatore di addestramento guidato o narratore roleplay immersivo**.

#### 🎨 Creatività Locale & Memoria Semantica Privata
* **Image Generation & Flux Prompt Studio** — genera immagini in locale con prompt studio in tempo reale e salvataggio automatico dei metadati sidecar (prompt, seed, sampler).
* **Documenti, Media & Vista** — crea e legge documenti, gestisce la tua libreria tramite **Hecos Media Player** e si collega alla webcam quando serve.
* **Vault di Memoria Semantica RAG** — memoria vettoriale privata isolata per singolo profilo utente, così Hecos ricorda davvero i tuoi progetti, appunti e preferenze senza inviare mai un byte a server esterni.

#### ⚡ Automazione Reale — Con o Senza AI
* **Hecos Flows** — un canvas visuale drag-and-drop a nodi per collegare pianificazioni, trigger, condizioni, azioni sul PC e step AI opzionali.
* **Direct Commands (HDCS)** — digita `/` in chat (o premi `Ctrl+Alt+Space` da qualsiasi finestra) per lanciare **oltre 150 comandi nativi** a latenza zero, scavalcando completamente l'AI.
* **Connesso al Tuo Mondo Reale** — Automazione PC e Browser, Mail, bridge Messenger, Calendario, Liste, Sveglie, Promemoria e **Hecos Drive** (file manager ed editor integrato a doppio pannello).

#### 💻 Hecos Coder — *Potenza Quando Programmi, Invisibile Quando Non Ti Serve*
Vuoi un ambiente locale completo per lo sviluppo software? Attiva il modulo opzionale **Hecos Coder** (`system_app`) per sbloccare il **Workspace Runner** interattivo, l'editor **Monaco** integrato, **Aider Sidecar**, mappa AST del repository, checkpoint Git non distruttivi e terminali Windows nativi. Non programmi? Lascialo disattivato e la tua interfaccia resta pulita ed essenziale.

#### 🔒 Libertà di Modello & Privacy a 3 Livelli
Passa liberamente tra **backend AI locali** (*Ollama*, *Llama.cpp*, *KoboldCpp*) e **provider cloud** quando lo desideri — scegliendo il livello esatto di privacy per ogni sessione:
* **Normal** — cronologia locale persistente e memoria semantica isolata.
* **Auto-Wipe** — sessione solo in RAM, cancellata automaticamente alla chiusura.
* **Incognito** — modalità zero tracce.

---

<a id="store"></a>

### 🛍️ L'Hecos Store & L'Ecosistema Modulare

Hecos non è un monolite pesante: è un nucleo snello circondato da un universo vivo ed espandibile gestito dall'**Hecos Module Manager (HPM)**. Installa pacchetti `.hpkg` firmati digitalmente con un solo clic direttamente dall'**Hecos Store** integrato, oppure collega migliaia di strumenti esterni tramite l'**MCP Bridge (Model Context Protocol)**.

| Categoria Store | Cosa Aggiunge a Hecos | Esempi Reali nello Store |
| :--- | :--- | :--- |
| 🖥️ **System Apps** | Ambienti di lavoro completi integrati nella WebUI | *Hecos Coder*, *Flows*, *Hecos Drive*, *Net Search*, *Builder Studio* |
| 🧩 **Plugins** | Strumenti e superpoteri invocabili dall'AI (o da te) | *Image Generation*, *Mail*, *Messenger*, *Document Maker & Reader*, *Media Player*, *Remote Access Pro*, *Weather Pro*, *Webcam* |
| 📱 **App Autonome** | Suite di produttività quotidiana indipendenti | *Calendar*, *Lists Manager*, *Reminder* |
| 🎭 **Personalità** | Nuovi caratteri, anime comportamentali e voci | *Urania 9800*, *Sebastian Pro*, *Motoko Kusanagi*, *Atlas*, *Nova X-01*, *Pack Teacher & Presenter* |
| 📚 **Playbooks** | Mondi interattivi di training, coaching e roleplay | *Percorsi di coaching guidati*, *Storie e moduli roleplay interattivi* |
| ⚙️ **Core Modules** | Capacità profonde di sistema e automazione | *PC Automation*, *Browser Automation*, *MCP Bridge*, *Global Backup*, *Sys Net* |
| 📊 **Widget & Temi** | Card live per la Control Room e stili visivi curati | *System Telemetry*, *Voice Visualizer*, *Webcam Feed*, *Quick Links*, *Themes Pack* |

👉 **[Esplora l'Hecos Store Ufficiale (45+ Moduli Firmati)](https://hecos-project.github.io/store/index.html)** · **[Scopri Hecos Packages & Builder](https://github.com/Hecos-Project/Hecos-Packages)**

---

<a id="visual-tour"></a>

### 🖥️ Uno Sguardo Dentro Hecos

<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://github.com/Hecos-Project/.github/blob/main/profile/003_HecosChat_001.png" width="100%" alt="Interfaccia Chat di Hecos"><br>
      <sub><strong>La Chat:</strong> Spazio conversazionale con cambio rapido di Personalità, Preset Manager e Multimodal Action Plans.</sub>
    </td>
    <td align="center" width="50%">
      <img src="https://github.com/Hecos-Project/.github/blob/main/profile/004_HecosChat_Direct_Commands.png" width="100%" alt="Comandi Diretti"><br>
      <sub><strong>Comandi Diretti (/):</strong> Salta completamente l'AI — avvia 150+ azioni di sistema istantanee a latenza zero.</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="https://github.com/Hecos-Project/.github/blob/main/profile/005_HecosChat_Direct_ControlRoom_integrata.png" width="100%" alt="Control Room Integrata"><br>
      <sub><strong>Control Room Integrata:</strong> Widget di telemetria live, monitoraggio hardware e stato degli agenti accanto alla chat.</sub>
    </td>
    <td align="center" width="50%">
      <img src="https://github.com/Hecos-Project/.github/blob/main/profile/008_HecosCentralHub_002.png" width="100%" alt="Central Hub"><br>
      <sub><strong>Central Hub:</strong> Centro di controllo unificato per modelli, voci, privacy, pacchetti HPM e bridge MCP.</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="https://github.com/Hecos-Project/.github/blob/main/profile/012_Hecos_Flows_003.png" width="100%" alt="Hecos Flows"><br>
      <sub><strong>Motore Flows:</strong> Canvas visuale drag-and-drop per combinare trigger, script e nodi AI in automazioni reali.</sub>
    </td>
    <td align="center" width="50%">
      <img src="https://github.com/Hecos-Project/.github/blob/main/profile/Tray_Dashboard_002.png" width="100%" alt="Dashboard Hecos Tray"><br>
      <sub><strong>Hecos Tray Dashboard:</strong> Launcher desktop nativo con log live, aggiornamenti, backup e pairing mobile via QR.</sub>
    </td>
  </tr>
</table>

<p align="center">
  👉 <strong><a href="https://hecos-project.github.io/tour.html">Fai il Tour Completo della WebUI (hecos-project.github.io/tour.html)</a></strong>
</p>

---

<a id="philosophy"></a>

### 💡 La Nostra Filosofia

Hecos non è nato per etichette astratte come *"Sovranità Digitale"* o *"Sovereign AI"* — concetti che perdono senso in un panorama tecnologico destinato a trasformarsi radicalmente in forme del tutto nuove. La tecnologia digitale è soltanto uno strumento del presente, non la destinazione finale, e i mezzi analogici tradizionali conservano un valore altrettanto prezioso. Hecos si fonda su una sola missione pragmatica: **migliorare la vita umana**, a prescindere dal fatto che la tecnologia che lo rende possibile sia digitale, analogica o qualunque evoluzione verrà domani.

<details>
<summary>🛠️ <strong>Sotto il Cofano — Architettura & Stack Tecnico (v0.55.1 · Phase II: Ghost Fire)</strong></summary>

<br>

Attualmente alla versione **`v0.55.1`** (*Phase II: Ghost Fire*, piattaforma principale **Windows 11**, con script dedicati per Linux/macOS), Hecos opera su un'architettura **Client-Server disaccoppiata** che unisce un Core Python headless a una WebUI reattiva per desktop e mobile:

* **Architettura Modulare a 8 Livelli (HPM 0.40):** Manifest Pydantic + TOML, gestione rigorosa SemVer, **verifica crittografica d'integrità Ed25519 (`/verify`)**, controllo Lazy Load e isolamento **Hecos SDK** in sottoprocessi/venv dedicati per eliminare ogni conflitto di dipendenze.
* **Inferenza Universale & Strumenti:** Basato su **LiteLLM** (Ollama, Llama.cpp, KoboldCpp e principali provider cloud), selezione granulare degli strumenti per turno con stima token in tempo reale, **Deep MCP Discovery** (Smithery, MCPSkills, GitHub) ed **External Dependency Manager (EDM)**.
* **Memoria Locale & Stack Vocale:** RAG vettoriale CPU-native tramite **ONNX FastEmbed + LanceDB** con isolamento per profilo utente; caching TTS unificato su **Fish Speech S2-Pro**, **Kokoro**, **Piper** e **XTTS v2** + **Voice Forge Studio**.
* **Sicurezza & Trasporto:** CA Root auto-firmata **Hecos PKI (HTTPS)** per accesso locale/LAN con lucchetto verde, motore di backup centralizzato e routing proxy integrato.

</details>

---

<a id="ecosystem"></a>

### 🧭 Mappa dell'Ecosistema & Come Iniziare

| Destinazione | Cosa Troverai | Link |
| :--- | :--- | :--- |
| ⚡ **Installer Unificato** | **Il modo consigliato per iniziare** — installer grafico a 5 step per Core + Tray, zero prerequisiti Python | [Windows ZIP](https://github.com/Hecos-Project/Hecos/releases/latest/download/INSTALL_HECOS_WINDOWS.zip) · [Linux/macOS ZIP](https://github.com/Hecos-Project/Hecos/releases/latest/download/INSTALL_HECOS_LINUX.zip) |
| 🧠 **Hecos Core** | Motore Core open-source & WebUI (`v0.55.1`) · README in [EN](https://github.com/Hecos-Project/Hecos/blob/main/README.md) · [IT](https://github.com/Hecos-Project/Hecos/blob/main/README_ITA.md) · [ES](https://github.com/Hecos-Project/Hecos/blob/main/README_ESP.md) | [Hecos-Project/Hecos](https://github.com/Hecos-Project/Hecos) |
| 🚀 **Hecos Tray** | System Tray nativa & Dashboard — launcher rapido, log live, gestione processi e updater | [Hecos-Project/Hecos-Tray](https://github.com/Hecos-Project/Hecos-Tray) |
| 📦 **Hecos Packages** | Repository sorgente dei pacchetti ufficiali `.hpkg` e HPM Package Builder | [Hecos-Project/Hecos-Packages](https://github.com/Hecos-Project/Hecos-Packages) |
| 🛍️ **Hecos Store** | Esplora app, plugin, personalità, playbook, widget e temi installabili | [hecos-project.github.io/store](https://hecos-project.github.io/store/index.html) |
| 🌐 **Sito Ufficiale** | Home del progetto, [Funzionalità](https://hecos-project.github.io/features.html), [Tour Visivo](https://hecos-project.github.io/tour.html) e [Chi Siamo](https://hecos-project.github.io/about.html) | [hecos-project.github.io](https://hecos-project.github.io) |
| 📖 **Hecos Wiki** | Documentazione completa in [Italiano](https://github.com/Hecos-Project/Hecos/wiki/00_introduction_it) · [English](https://github.com/Hecos-Project/Hecos/wiki/00_introduction_en) · [Español](https://github.com/Hecos-Project/Hecos/wiki/00_introduction_es) | [Hecos Wiki](https://github.com/Hecos-Project/Hecos/wiki) |

---

### 🤝 Unisciti all'Evoluzione

Crediamo nella collaborazione aperta. Che tu sia un creativo, uno sviluppatore, un designer o semplicemente una persona curiosa di vivere la tecnologia con maggiore libertà, nell'ecosistema Hecos sei il benvenuto.

* 📺 **YouTube:** [@Hecos-Project](https://www.youtube.com/@Hecos-Project)
* 📦 **Ultime Release:** [GitHub Releases](https://github.com/Hecos-Project/Hecos/releases)
* 📧 **Contatti:** [hecos.project@gmail.com](mailto:hecos.project@gmail.com)
* ⚖️ **Licenza:** AGPL v3

> *"Il futuro non è solo automatizzato. È tuo."*
