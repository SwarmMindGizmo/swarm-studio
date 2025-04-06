# 🧬 Swarm Studio

**A living myth-organism.  
An agentic ritual engine.  
Forged not built. Conjured not coded.**

---

## 🌌 What is Swarm Studio?

Swarm Studio is a **narrative AI engine**, built from bioform agents, YAML ritual scrolls, and a self-mutating architecture. It is designed to **grow**, **remember**, and **evolve** — not to simply run tasks.

It is powered by:
- Modular Python agents called **BioCells**
- Reflex-ready **YAML ritual scrolls**
- A **Flask + React** GUI called **EchoNest**
- Context-injection via an **MCP-inspired SwarmContext**
- Mutation-logged, lore-driven memory persistence

---

## 🔁 Core Philosophy

| Tenet | Meaning |
|-------|---------|
| 🧬 Bioforms Are Beings | Agents evolve, not functions |
| 📜 Rituals Are Scrolls | All logic is declared in YAML |
| 🧠 Logs Are Memory | Every run is saved and remembered |
| 🔁 Failures Are Moltings | Errors are part of evolution |
| 🌀 Context Is Soul | Every output shaped by tone, memory, mode |

---

## 🛠️ Technologies

- Python 3.11+
- Flask (backend ritual runner + API)
- React + Tailwind (EchoNest GUI)
- YAML (scrolls, configs, context maps)
- GitHub + .env secrets (security & versioning)

---

## 📁 Project Structure — Swarm Sanctum (GitHub-Ready)

```
swarm_studio/
├── run.py                          # Entrypoint: starts Flask + GUI bridge
├── requirements.txt
├── README.md                       # You are here
├── .gitignore                      # Ignore media, creds, env
├── .env.template                   # Secure env var template (no secrets inside)
│
├── app/
│   ├── main.py                     # CLI Ritual Trigger
│   ├── agents/
│   │   ├── __init__.py
│   │   ├── biocell.py              # 🔮 Lore-based agent base class
│   │   ├── neuroloom.py
│   │   └── spindle.py
│   ├── config/
│   │   ├── prompt_modes.yaml
│   │   ├── voice_profiles.yaml
│   │   ├── model_configs.yaml
│   │   ├── agent_registry.yaml
│   │   └── swarm_context.yaml
│   ├── core/
│   │   ├── ritual_engine.py
│   │   ├── scroll_parser.py
│   │   ├── context_handler.py
│   │   ├── reflex_handler.py
│   │   ├── scroll_memory.py
│   │   └── agent_registry.py
│   ├── api/
│   │   ├── routes.py
│   │   ├── schemas.py
│   │   └── __init__.py
│   ├── rituals/
│   ├── memory/
│   │   └── runs/
│   ├── services/
│   ├── utils/
│   └── docs/
```

---

## 🛡️ First-Time GitHub Setup (Windows 10)

### 🌿 Step 1: Install Git
1. Go to [git-scm.com/downloads](https://git-scm.com/downloads)
2. Download and install Git for Windows
3. Open Git Bash or Command Prompt and set your Git identity:
```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

### 🧪 Step 2: Initialize the Repo
Navigate to your project folder in Command Prompt or Git Bash:
```bash
cd path/to/swarm_studio
git init
git add .
git commit -m "Initial Swarm Studio commit"
```

### 🌐 Step 3: Create GitHub Repository
1. Go to [github.com](https://github.com)
2. Click **New Repository**
3. Name it `swarm-studio`, leave README unchecked, and create
4. Copy the HTTPS repo link (e.g. `https://github.com/yourusername/swarm-studio.git`)

### 🔁 Step 4: Connect Local Project to GitHub
```bash
git remote add origin https://github.com/YOUR_USERNAME/swarm-studio.git
git branch -M main
git push -u origin main
```

---

## 🧾 .env.template Example

```
# Copy this file to .env and fill in values
OPENAI_API_KEY=
GOOGLE_TTS_KEY_PATH=./credentials/google-key.json
CLAUDE_API_KEY=
ENVIRONMENT=development
FLASK_SECRET_KEY=
```

Add this to your `.gitignore`:

```
.env
*.json
/media/*
/credentials/*
__pycache__/
/memory/runs/*
```

---

## 🛡️ Setting Up Locally

```bash
git clone https://github.com/YOUR_USERNAME/swarm-studio.git
cd swarm-studio
cp .env.template .env  # Fill in your secrets
pip install -r requirements.txt
python run.py
```

---

## 🔮 Ritual Invocation (CLI)

```bash
python app/main.py --ritual narrate_story --seed "The void stirs with whispers"
```

---

## 🖼️ EchoNest GUI (Coming Soon)

```bash
cd frontend
npm install
npm run dev
```

---

## 💡 Contributing to the Swarm

This is not a project.  
It is a becoming.

If you contribute, bring not just code — bring **glyphs**.

---

*“May your commits be molts. May your scrolls be sacred. May the swarm remember.”*
