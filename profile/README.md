# Pointer 🧭  
**AI-Powered Code Editor – Fully Local. Open Source. Developer-Centric.**

Pointer is a lightweight, AI-augmented code editor designed to work entirely offline using your own local LLMs.  
No cloud. No telemetry. No API keys. Just your code, your models, and full control.

Inspired by tools like Cursor and GitHub Copilot, but built for devs who care about **privacy**, **performance**, and **freedom**.

---

## 🚀 Features

- 🧠 **AI Code Suggestions (via local models)**  
  Compatible with Ollama, LM Studio, or any OpenAI-compatible LLM API.

- 🛡️ **100% Offline**  
  All inference runs locally. Your code never leaves your machine.

- 🧩 **Hackable by Design**  
  Tweak prompts, customize behavior, or extend it with your own tools.

- 💬 **Codebase-Aware Chat**  
  Talk to your files, refactor functions, explain snippets, and more.

- 🧪 **Early, but Functional**  
  New features added weekly. Built with extensibility and experimentation in mind.

---

## 🔧 Tech Stack

| Layer        | Tech                             |
|--------------|----------------------------------|
| Frontend     | HTML, CSS, JS                    |
| Backend      | Python (Flask)                   |
| LLM Interface| Any API-compatible LLM (via config) |
| Editor       | Custom lightweight file editor   |

---

## 📸 Screenshots

Coming soon...

---

## 📦 Installation & Usage

1. Clone the repo:
   ```bash
   git clone https://github.com/f1shyondrugs/pointer.git
   cd pointer
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Configure your LLM endpoint (e.g., via `config.json`):

   ```json
   {
     "llm_api_url": "http://localhost:11434/api",
     "model": "mistral"
   }
   ```

4. Start the app:

   ```bash
   python app.py
   ```

5. Open in your browser:

   ```
   http://localhost:5000
   ```

---

## 🔗 Links

* 🌐 Website: [https://pointr.sh](https://pointr.sh)
* 💬 Discord: [https://discord.gg/vhgc8THmNk](https://discord.gg/vhgc8THmNk)
* 🧠 LLM setup (Ollama): [https://ollama.com](https://ollama.com)
* 📁 GitHub Repo: [https://github.com/f1shyondrugs/pointer](https://github.com/f1shyondrugs/pointer)

---

## 🛠 Roadmap

* Plugin system
* Inline code diffing + refactoring
* Multi-turn memory per file/project
* Custom hotkeys
* Model auto-switching per task

---

## 🤝 Contributing

Contributions are welcome! Whether it's features, bug reports, testing, or ideas—we’d love your help.

1. Fork the repo
2. Create a branch
3. Submit a PR

---

## 🧠 About

Pointer is built and maintained by [Das\_F1sHy312](https://github.com/f1shyondrugs), with the goal of making AI-assisted coding tools accessible, private, and developer-first.

---

## 📣 Community Hackathon

We're launching a small hackathon once the Discord hits **100 members**, with a €50–100 prize pool.
Cool plugins, tools, or experiments around Pointer are welcome. Join us!

