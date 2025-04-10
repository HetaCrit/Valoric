# Valoric

Valoric is an automated project creation system that intelligently interprets textual commands to generate project directories either natively on Windows 11 or within a Docker container. The system features:

- **Command Reception & Parsing:** Accepts commands through a CLI or REST API.
- **Decision Engine:** Determines whether to create a native project or a Dockerized one.
- **Project Management:** Automates the creation and setup of directories, files, virtual environments, and Dockerfiles.
- **Iterative Feedback Loop:** Validates project creation through automated tests and can re-trigger corrections if necessary.

## Key Features

- **Native vs. Containerized Projects:** Based on parsed command keywords such as "Docker" or context clues.
- **Central Orchestration:** Uses an orchestrator (written in Python or Go) to manage the workflow end-to-end.
- **Modular Design:** With separate components for command parsing, decision making, and directory management.
- **Extensible Architecture:** Easy to expand with features like audio-to-text integration or advanced AI evaluations.

## Getting Started

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your_username/Valoric.git
   cd Valoric
