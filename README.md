# Hi, I'm Thomas 👋

**Full-stack and game developer** based in France. I build web platforms, multiplayer games, desktop tools and the servers they run on. Over the past year, AI has become part of what I ship and of how I work.

- 🛠️ Lately: a self-hosted AI image-generation platform (SDXL), served through a website and a Discord bot and backed by a fleet of GPU machines
- 🎮 Making multiplayer games in **Unity 6** (URP, FishNet, Netcode for GameObjects)
- 🤖 Coding every day with **Claude Code**, and building tools around AI-assisted development
- 💬 Ask me about FastAPI backends, Unity netcode, self-hosting, or running AI models in production
- 😄 Pronouns: he/him

## 🤖 AI

<p>
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude Code" />
  <img src="https://img.shields.io/badge/Stable_Diffusion_(SDXL)-6E40C9?style=for-the-badge" alt="Stable Diffusion SDXL" />
  <img src="https://img.shields.io/badge/LoRA-8A2BE2?style=for-the-badge" alt="LoRA" />
  <img src="https://img.shields.io/badge/Qwen3_(GGUF)-615CED?style=for-the-badge" alt="Qwen3 GGUF" />
  <img src="https://img.shields.io/badge/ONNX_Runtime-005CED?style=for-the-badge&logo=onnx&logoColor=white" alt="ONNX Runtime" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/Whisper-412991?style=for-the-badge" alt="Whisper" />
  <img src="https://img.shields.io/badge/Piper_TTS-2E7D32?style=for-the-badge" alt="Piper TTS" />
</p>

| | What I've built with it |
|---|---|
| **Image generation** | SDXL pipelines on Stable Diffusion WebUI Forge: checkpoints, a LoRA library synced to every machine, hires fix, a priority queue with fair turn-taking, and a WebSocket protocol between the GPU workers and the API |
| **Local LLMs** | Qwen3-4B (GGUF, Q4) running on the workers' CPUs to rewrite users' prompts and write image captions, with no external API |
| **ML in production** | A WD14 tagger on ONNX Runtime inside the API, used as a content-moderation guardrail (classification, quarantine) |
| **Speech** | Whisper (voice → intent → action) and Piper (local French text-to-speech) in a Raspberry Pi home assistant |
| **AI-assisted development** | Claude Code as my daily driver: project instructions, prompt files, permissions, MCP servers. I also use Codex and Antigravity |
| **Tools for AI workflows** | A browser extension that turns SonarQube issues into an AI prompt, and a cross-platform desktop app (Electron) that tracks Claude Code, Codex and Antigravity token usage for a team |
| **Trying new models** | I test new models on complete projects, such as [ORBITAL](https://github.com/Lenitra/test_fable5), a real-time 3D satellite viewer |

## 🧰 Tech stack

**Languages**<br>
<img src="https://skillicons.dev/icons?i=cs,py,ts,js,java,html,css,bash,powershell" alt="C#, Python, TypeScript, JavaScript, Java, HTML, CSS, Bash, PowerShell" />

**Frontend and desktop**<br>
<img src="https://skillicons.dev/icons?i=react,nextjs,vue,tailwind,vite,threejs,electron,dotnet" alt="React, Next.js, Vue, Tailwind, Vite, Three.js, Electron, .NET" />

**Backend and data**<br>
<img src="https://skillicons.dev/icons?i=fastapi,flask,spring,nodejs,postgres,sqlite,mongodb" alt="FastAPI, Flask, Spring Boot, Node.js, PostgreSQL, SQLite, MongoDB" />

**Game development**<br>
<img src="https://skillicons.dev/icons?i=unity,gradle" alt="Unity, Gradle" />

**Infrastructure**<br>
<img src="https://skillicons.dev/icons?i=docker,debian,linux,nginx,cloudflare,githubactions,raspberrypi,git" alt="Docker, Debian, Linux, Nginx, Cloudflare, GitHub Actions, Raspberry Pi, Git" />

Also: SQLAlchemy (async) and SQLModel, Caddy, Cloudflare Tunnel, Paper plugins for Minecraft (Java 21), Discord bots, Firefox and Safari extensions, VS Code extensions, WinForms, PWAs, and the Stripe, Spotify and Patreon APIs.

## 📌 Featured projects

| Project | What it is | Stack |
|---|---|---|
| [TGE Launcher](https://github.com/Lenitra/tge-launcher) | One-click launcher for a virtual trucking company in Euro Truck Simulator 2: updates the mod, configures TrucksBook and starts the game | C# · .NET 9 |
| [Holo Project](https://github.com/Lenitra/holo_project) | Raspberry Pi home assistant with a four-sided holographic display, voice commands and a web remote | Python · Node.js · React |
| [ORBITAL](https://github.com/Lenitra/test_fable5) | Real-time 3D satellite viewer: orbits propagated with SGP4 from TLEs, day/night Earth, clouds, bloom | Three.js · Vite |
| [SonarQube → AI prompt](https://github.com/Lenitra/sonar-prompt-debug) | Firefox and Safari extension that condenses SonarQube issues into a ready-to-paste prompt, through the official API, without data leaving the browser | JavaScript |
| [Terminal Macros](https://github.com/Lenitra/terminal-macro-vscode-ext) | VS Code extension: buttons in the status bar and a side panel to run your commands, with each project's scripts picked up automatically | JavaScript |
| [FastAPI Project Initializer](https://github.com/Lenitra/FastApi-project-initializer) | Generates a FastAPI app from a list of entities: entity, repository and service layers, full CRUD, JWT auth with roles | Python · SQLModel |

## 📫 Connect with me

- [Email](mailto:thomaslemartinel@gmail.com)
- [Discord](https://discord.gg/7sgXaAsv9Y)
