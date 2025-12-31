# Local AI Assistant Using a Lightweight LLM

## Project Overview
This project demonstrates the design and deployment of a **local AI assistant** using a lightweight **Large Language Model (LLM)**.  
The system runs entirely on a local machine, ensuring **privacy, offline capability, and reduced dependency on cloud-based AI services**.

No application-level programming code was written. Instead, the project focuses on **configuration, deployment, and interaction** using open-source tools.

---

## Objectives
- Deploy a local AI assistant on a personal computer
- Run a lightweight LLaMA 3.2 model locally using Ollama
- Provide both CLI-based and web-based interaction
- Use Docker to host a browser-accessible AI interface
- Document all steps for reproducibility

---

## Tools and Technologies
- **Ollama** – Local LLM runtime
- **LLaMA 3.2 (1.24B)** – Lightweight language model
- **Docker** – Containerization platform
- **Open WebUI** – Web-based AI interface
- **PowerShell / macOS Terminal** – Command-line interaction

---

## Repository Structure
```

Local-AI-Assistant-Project/
│
├── commands/
│   └── setup-commands.md
│
├── screenshots/
│   ├── ollama-install.png
│   ├── llama-cli-chat.png
│   ├── docker-version.png
│   ├── openwebui-dashboard.png
│
├── documentation/
│   └── Local_AI_Assistant_Report.pdf
│
└── README.md

```

---

## Setup Instructions
All setup commands are documented in:

```

commands/setup-commands.md

```

The instructions support:
- Windows (PowerShell)
- macOS (Terminal / zsh)

---

## How the System Works
1. **Ollama** runs a local LLaMA 3.2 model on the host machine
2. The model can be accessed directly via the command line
3. **Docker** deploys Open WebUI as a container
4. Open WebUI connects to Ollama and provides a browser-based interface
5. Users interact with the AI assistant through CLI or web UI

---

## Screenshots and Documentation
Screenshots are provided to demonstrate:
- Successful installation of tools
- Model execution via CLI
- Docker container deployment
- AI interaction through Open WebUI

These screenshots are referenced in the project report.

---

## Video Demonstration
A short video demonstration is provided separately (YouTube link submitted with the assignment), showing:
- Model execution
- WebUI interaction
- System overview

---

## Notes
- This project emphasizes **deployment and configuration**, not software development
- No custom AI models were trained or fine-tuned
- All operations were performed locally
- The project is fully reproducible using the documented commands

---

## Author(s)
- *Willard Soriano*

---

## License
This project uses open-source tools and is intended for **educational purposes only**.
```

---
