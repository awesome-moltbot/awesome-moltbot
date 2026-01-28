<!-- HEADER -->
<div align="center">

<br>
<!-- LOGO -->
<h1 align="center">
  🦞
</h1>

<!-- TITLE -->
<h1>Awesome Moltbot</h1>

<!-- BADGES -->
<p>
<a href="https://github.com/sindresorhus/awesome"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" height="28" alt="Awesome" /></a>
&nbsp;&nbsp;
<a href="https://github.com/moltbot/moltbot"><img src="https://img.shields.io/github/stars/moltbot/moltbot?style=social" height="28" alt="Moltbot Stars" /></a>
</p>

<br>

<!-- DESCRIPTION -->
<h3>A curated list of awesome plugins, skills, tools, and resources for <a href="https://molt.bot/">Moltbot</a>.</h3>
<h3>Your own personal AI assistant. Any OS. Any Platform. The lobster way. 🦞</h3>

<br>

[**OFFICIAL**](#official) • [**COMMUNITY**](#community) • [**TIPS & TRICKS**](#tips) • [**TOOLS**](#tools) • [**TERMINALS**](#terminals) • [**SKILLS**](#skills) • [**CHANNELS**](#channels) • [**VIDEOS**](#videos) • [**DEPLOYMENT**](#deployment) • [**RESOURCES**](#resources) • [**CONTRIBUTING**](#contributing)

<br>
<hr>

</div>

<!-- CONTENT -->

<div id="official"></div>

<h3>⭐️ Official Repositories</h3>

| Project | Stars | Description |
| :--- | :--- | :--- |
| **[moltbot](https://github.com/moltbot/moltbot)** | ![Stars](https://badgen.net/github/stars/moltbot/moltbot) | The flagship personal AI assistant. Supports WhatsApp, Telegram, Slack, iMessage, and more. |
| **[lobster](https://github.com/moltbot/lobster)** | ![Stars](https://badgen.net/github/stars/moltbot/lobster) | Native workflow shell and macro engine for composable AI automations. |
| **[molthub](https://github.com/moltbot/molthub)** | ![Stars](https://badgen.net/github/stars/moltbot/molthub) | The public registry for Moltbot skills and souls. |
| **[molt.bot](https://github.com/moltbot/molt.bot)** | ![Stars](https://badgen.net/github/stars/moltbot/molt.bot) | Source code for the official website. |

<br>

<div id="community"></div>

<details open>
<summary><strong>🌍 COMMUNITY ECOSYSTEM</strong></summary>
<br>

<details>
  <summary><b>Planning with Files</b> <img src="https://badgen.net/github/stars/OthmanAdi/planning-with-files" height="14"/> - <i>Advanced Agent Planning</i></summary>
  <blockquote>
    A high-profile skill implementing "Manus-style" persistent planning and file-based state management.
    <br><br>
    <a href="https://github.com/OthmanAdi/planning-with-files">🔗 <b>View Repository</b></a>
  </blockquote>
</details>

<details>
  <summary><b>Mote Hardware</b> <img src="https://badgen.net/github/stars/Nebaura-Labs/mote" height="14"/> - <i>Voice Companion</i></summary>
  <blockquote>
    Open-source ESP32-S3 hardware project for a dedicated Moltbot voice companion.
    <br><br>
    <a href="https://github.com/Nebaura-Labs/mote">🔗 <b>View Repository</b></a>
  </blockquote>
</details>

<details>
  <summary><b>Agent Flywheel</b> <img src="https://badgen.net/github/stars/Dicklesworthstone/agent_flywheel_clawdbot_skills_and_integrations" height="14"/> - <i>Workflow Skills</i></summary>
  <blockquote>
    A collection of specialized skills designed for agentic coding workflows (ACFS stack).
    <br><br>
    <a href="https://github.com/Dicklesworthstone/agent_flywheel_clawdbot_skills_and_integrations">🔗 <b>View Repository</b></a>
  </blockquote>
</details>

<details>
  <summary><b>Molty Swarm</b> <img src="https://badgen.net/github/stars/cgaspart/clowd-swarm" height="14"/> - <i>Orchestration</i></summary>
  <blockquote>
    Distributed orchestration framework for managing Moltbot swarms in a Master/Worker architecture.
    <br><br>
    <a href="https://github.com/cgaspart/clowd-swarm">🔗 <b>View Repository</b></a>
  </blockquote>
</details>

</details>

<br>

<div id="tips"></div>

<details open>
<summary><strong>💡 TIPS & TRICKS</strong></summary>
<br>

| Trick | Description | Command / Details |
| :--- | :--- | :--- |
| **Remote UI (SSH)** | Access the Web UI securely from anywhere. | `ssh -N -L 18789:127.0.0.1:18789 user@host`<br>Then open `ws://127.0.0.1:18789` locally. |
| **Think Control** | Adjust reasoning effort dynamically. | `/think <off|minimal|low|medium|high|xhigh>` |
| **God Mode** | Enable direct shell access (Host OS). | `! ls -la` (Requires `commands.bash: true`) |
| **Cron Agents** | Spin up isolated agents on a schedule. | `moltbot cron add --session isolated ...` |
| **Inline Cmds** | Run commands hidden inside chat text. | "How are you? /status" |
| **Debug Mode** | Hot-swap config values at runtime. | `/debug set channels.whatsapp...` |

</details>

<br>

<div id="tools"></div>

<details open>
<summary><strong>🛠️ TOOLS & UTILITIES</strong></summary>
<br>

<details>
  <summary><b>Casa</b> <img src="https://badgen.net/github/stars/moltbot/casa" height="14"/> - <i>HomeKit bridge</i></summary>
  <blockquote>
    Mac Catalyst app that exposes local Apple HomeKit data as a REST API and CLI for Moltbot.
    <br><br>
    <a href="https://github.com/moltbot/casa">🔗 <b>View Repository</b></a>
  </blockquote>
</details>

<details>
  <summary><b>Peekaboo</b> <img src="https://badgen.net/github/stars/moltbot/nix-steipete-tools" height="14"/> - <i>macOS UI automation</i></summary>
  <blockquote>
    Capture and automate macOS UI with a specialized CLI, bundled in nix-steipete-tools.
    <br><br>
    <a href="https://github.com/moltbot/nix-steipete-tools">🔗 <b>View Repository</b></a>
  </blockquote>
</details>

<details>
  <summary><b>Moltgo</b> <img src="https://badgen.net/github/stars/moltbot/moltgo" height="14"/> - <i>Minimal Go node</i></summary>
  <blockquote>
    A minimal, headless Go-based node client for low-power environments like Raspberry Pi.
    <br><br>
    <a href="https://github.com/moltbot/moltgo">🔗 <b>View Repository</b></a>
  </blockquote>
</details>

<details>
  <summary><b>Homebrew Tap</b> <img src="https://badgen.net/github/stars/moltbot/homebrew-tap" height="14"/> - <i>macOS Package Manager</i></summary>
  <blockquote>
    Official Homebrew repository for installing Moltbot CLI tools and apps on macOS.
    <br><br>
    <a href="https://github.com/moltbot/homebrew-tap">🔗 <b>View Repository</b></a>
  </blockquote>
</details>

</details>

<br>

<div id="terminals"></div>

<details open>
<summary><strong>💻 TERMINAL RECOMMENDATIONS</strong></summary>
<br>

<details>
  <summary><b>Ghostty</b> <img src="https://img.shields.io/badge/Mac-Linux-lightgrey" height="14"/> - <i>Native & Fast</i></summary>
  <blockquote>
    A modern, GPU-accelerated terminal emulator with native UI. Highly recommended for a fast Moltbot experience.
    <br><br>
    <a href="https://ghostty.org/">🔗 <b>Website</b></a>
  </blockquote>
</details>

<details>
  <summary><b>Warp</b> <img src="https://img.shields.io/badge/Mac-Linux-lightgrey" height="14"/> - <i>AI Integrated</i></summary>
  <blockquote>
    A modern terminal with built-in AI, block-based output, and collaborative features.
    <br><br>
    <a href="https://www.warp.dev/">🔗 <b>Website</b></a>
  </blockquote>
</details>

<details>
  <summary><b>Windows Terminal</b> <img src="https://img.shields.io/badge/Windows-lightgrey" height="14"/> - <i>Standard</i></summary>
  <blockquote>
    The gold standard for Windows users. Supports multiple profiles (PowerShell, WSL, Git Bash) and GPU acceleration.
    <br><br>
    <a href="https://github.com/microsoft/terminal">🔗 <b>View Repository</b></a>
  </blockquote>
</details>

<details>
  <summary><b>WezTerm</b> <img src="https://img.shields.io/badge/All%20Platforms-lightgrey" height="14"/> - <i>Configurable</i></summary>
  <blockquote>
    A powerful, GPU-accelerated cross-platform terminal emulator and multiplexer configured via Lua.
    <br><br>
    <a href="https://wezfurlong.org/wezterm/">🔗 <b>Website</b></a>
  </blockquote>
</details>

<details>
  <summary><b>iTerm2</b> <img src="https://img.shields.io/badge/Mac-lightgrey" height="14"/> - <i>Power User</i></summary>
  <blockquote>
    The classic power-user terminal for macOS with extensive feature set and deep customization.
    <br><br>
    <a href="https://iterm2.com/">🔗 <b>Website</b></a>
  </blockquote>
</details>

</details>

<br>

<div id="skills"></div>

<details open>
<summary><strong>🧠 SKILLS & REGISTRIES</strong></summary>
<br>

<details>
  <summary><b>MoltHub Skills</b> <img src="https://badgen.net/github/stars/moltbot/skills" height="14"/> - <i>Skill Archive</i></summary>
  <blockquote>
    Archive of all skill versions ever published to the MoltHub registry.
    <br><br>
    <a href="https://github.com/moltbot/skills">🔗 <b>View Repository</b></a>
  </blockquote>
</details>

<details>
  <summary><b>Awesome Moltbot Skills</b> <img src="https://badgen.net/github/stars/VoltAgent/awesome-moltbot-skills" height="14"/> - <i>565+ Skills</i></summary>
  <blockquote>
    A curated collection of community-built skills for productivity, smart home, and creative tools.
    <br><br>
    <a href="https://github.com/VoltAgent/awesome-moltbot-skills">🔗 <b>View Repository</b></a>
  </blockquote>
</details>

<details>
  <summary><b>Notable Integrations</b></summary>
  <blockquote>
    <br>
    <ul>
      <li><a href="https://github.com/zacharytamas/moltbot-mattermost"><b>Mattermost Plugin</b></a> - Integration for Mattermost channels.</li>
      <li><a href="https://github.com/TGambit65/docker-mcp-plugin"><b>Docker MCP Plugin</b></a> - Docker Desktop integration.</li>
    </ul>
  </blockquote>
</details>

</details>

<br>

<div id="channels"></div>

<details open>
<summary><strong>🔌 CHANNELS & PLUGINS</strong></summary>
<br>

<details>
  <summary><b>Messaging Channels</b></summary>
  <blockquote>
    Moltbot supports a vast array of messaging platforms:
    <ul>
      <li><b>WhatsApp</b> (via Baileys)</li>
      <li><b>Telegram</b> (via grammY)</li>
      <li><b>Slack</b> (via Bolt)</li>
      <li><b>Discord</b> (via discord.js)</li>
      <li><b>iMessage</b> (via imsg CLI)</li>
      <li><b>Signal</b> (via signal-cli)</li>
    </ul>
  </blockquote>
</details>

<details>
  <summary><b>Advanced Integrations</b></summary>
  <blockquote>
    Third-party relay and extension-based channels:
    <ul>
      <li><b>BlueBubbles</b>: iMessage access for Android/Linux.</li>
      <li><b>Microsoft Teams</b>: Enterprise communication relay.</li>
      <li><b>Matrix</b>: Federated chat integration.</li>
      <li><b>Zalo</b>: Regional messaging support.</li>
    </ul>
  </blockquote>
</details>

</details>

<br>

<div id="videos"></div>

<details open>
<summary><strong>🎥 TOP 10 TUTORIALS & DEMOS</strong></summary>
<br>

| Video | Description |
| :--- | :--- |
| **[Moltbot: The self-hosted AI (Full setup)](https://www.youtube.com/watch?v=SaWSPZoPX34)** | Comprehensive setup guide for VPS and messaging. |
| **[Moltbot - Your Own AI Assistant](https://www.youtube.com/watch?v=5kkIJNUGFho)** | No-coding guide for setting up on Hetzner (Jan 2026). |
| **[Moltbot in Less Than 2 Minutes](https://www.youtube.com/watch?v=3DBpfB0ao50)** | Speedrun tutorial for hosting entirely free on AWS. |
| **[Install Moltbot on Proxmox](https://www.youtube.com/watch?v=GGExHHRCAdQ)** | Deep-dive technical guide for homelab environments. |
| **[Moltbot just Changed AI Forever](https://www.youtube.com/watch?v=PrWZe0VmnGg)** | Enthusiastic review and iMessage integration demo. |
| **[Everyone's going crazy for Moltbot](https://www.youtube.com/watch?v=MUDvwqJWWIw)** | Reaction video with "AI employee" demos. |
| **[Moltbot x Meta Rayban x Amazon](https://www.youtube.com/watch?v=jbvd0d6Bm1A)** | Futuristic demo scanning and buying items via glasses. |
| **[The Installation NIGHTMARE Nobody Talks About](https://www.youtube.com/watch?v=8KJJRBWoXdg)** | Honest troubleshooting guide for common pitfalls. |
| **[Fully Free Co-Working ASYNC Coder](https://www.youtube.com/watch?v=nydDQI6fp_I)** | "Coding battle" vs. other agents in realistic workflows. |
| **[Moltbot: The 24/7 AI Agent Employee](https://www.youtube.com/watch?v=W15UztbGEJw)** | Overview of automating personal and professional life. |

</details>

<br>

<div id="deployment"></div>

<details open>
<summary><strong>🚀 DEPLOYMENT & INFRA</strong></summary>
<br>

<details>
  <summary><b>Nix Moltbot</b> <img src="https://badgen.net/github/stars/moltbot/nix-moltbot" height="14"/> - <i>Declarative Setup</i></summary>
  <blockquote>
    Nix-based deployment for macOS and Linux with a formal plugin system.
    <br><br>
    <a href="https://github.com/moltbot/nix-moltbot">🔗 <b>View Repository</b></a>
  </blockquote>
</details>

<details>
  <summary><b>Moltbot Ansible</b> <img src="https://badgen.net/github/stars/moltbot/moltbot-ansible" height="14"/> - <i>Hardened Installer</i></summary>
  <blockquote>
    Automated installer with Docker isolation, Tailscale VPN, and firewall protection.
    <br><br>
    <a href="https://github.com/moltbot/moltbot-ansible">🔗 <b>View Repository</b></a>
  </blockquote>
</details>

<details>
  <summary><b>Moltinators</b> <img src="https://badgen.net/github/stars/moltbot/moltinators" height="14"/> - <i>AWS Infrastructure</i></summary>
  <blockquote>
    Declarative infrastructure (NixOS on AWS) for provisioning maintainer-grade agent hosts.
    <br><br>
    <a href="https://github.com/moltbot/moltinators">🔗 <b>View Repository</b></a>
  </blockquote>
</details>

</details>

<br>

<div id="resources"></div>

<details open>
<summary><strong>📚 RESOURCES</strong></summary>
<br>

| Resource | Description |
| :--- | :--- |
| **[Official Documentation](https://docs.molt.bot)** | The central guide for setup, tools, and gateway configuration. |
| **[Digital Ocean Quickstart](https://www.digitalocean.com/community/tutorials/moltbot-quickstart-guide)** | The official DigitalOcean guide for running Moltbot on a Droplet. |
| **[Cloud Setup Gist](https://gist.github.com/dabit3/42cce744beaa6a0d47d6a6783e443636)** | A popular community guide for cloud deployment by @dabit3. |
| **[AGENTS.md](https://github.com/moltbot/moltbot/blob/main/AGENTS.md)** | Guidance on agent identity, makeup, and skill interactions. |
| **[CHANGELOG.md](https://github.com/moltbot/moltbot/blob/main/CHANGELOG.md)** | Keep track of the latest features like Canvas, Browser Control, and more. |

</details>

<br>
<hr>

<div id="contributing"></div>

<div align="center">
<h3>🤝 Contributing</h3>
<p>Found an Awesome Moltbot project?<br>
<a href="https://github.com/awesome-moltbot/awesome-moltbot/pulls">Submit a Pull Request</a> to add it to the list!</p>
</div>

<br>

<div align="center">
  <p><b>Lobster way. 🦞</b></p>
</div>

---

<div align="center">

**⚠️ Disclaimer**

This repository is an independent, community-driven collection of resources. It is not affiliated with, endorsed by, or officially associated with the creators of Moltbot. All product names, logos, and brands are property of their respective owners.

</div>
