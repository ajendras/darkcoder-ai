<div align="center">

<a href="https://darkcoder.ai"><img src="./assets/hero.svg" width="100%" alt="DarkCoder.ai — Self-hosted AI gateway"/></a>

<a href="https://darkcoder.ai"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2600&pause=900&color=22C55E&center=true&vCenter=true&width=760&height=46&lines=One+endpoint.+Every+AI+model.;Copilot+%C2%B7+Claude+%C2%B7+Gemini+%C2%B7+Grok+%C2%B7+DeepSeek;Automatic+fallback+%E2%80%94+never+stop+coding;Encrypted+keys+%C2%B7+revocable+gateway+keys" alt="One endpoint. Every AI model. · Copilot · Claude · Gemini · Grok · DeepSeek · Automatic fallback — never stop coding · Encrypted keys · revocable gateway keys"/></a>

<p>
  <a href="https://darkcoder.ai"><img src="https://img.shields.io/badge/Live-darkcoder.ai-22c55e?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live site"/></a>
  <img src="https://img.shields.io/website?url=https%3A%2F%2Fdarkcoder.ai&style=for-the-badge&label=status&up_message=online&down_message=offline" alt="Status"/>
  <img src="https://img.shields.io/badge/Source-Private-334155?style=for-the-badge&logo=github&logoColor=white" alt="Source private"/>
  <a href="https://ajendra.info"><img src="https://img.shields.io/badge/Built_by-Ajendra-a855f7?style=for-the-badge&logo=codeigniter&logoColor=white" alt="Built by Ajendra"/></a>
</p>

<p>
  <a href="#-overview"><b>Overview</b></a> &nbsp;•&nbsp;
  <a href="#-features"><b>Features</b></a> &nbsp;•&nbsp;
  <a href="#-tech-stack"><b>Tech</b></a> &nbsp;•&nbsp;
  <a href="#%EF%B8%8F-architecture"><b>Architecture</b></a> &nbsp;•&nbsp;
  <a href="#-source-code"><b>Source</b></a>
</p>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:22c55e,50:22d3ee,100:a855f7&height=3&section=header" width="100%" alt=""/>

## ✨ Overview

**DarkCoder.ai** is a self-hosted AI gateway. Connect your own GitHub Copilot, Claude, Gemini, Grok, DeepSeek and local Ollama accounts and get **a single OpenAI-compatible endpoint** with automatic fallback between them.

It ships with encrypted key storage, revocable gateway keys, a built-in AI chat, an admin cockpit, a Windows app and a VS Code extension, so you never stop coding when one provider hits a limit.

<div align="center">
  <a href="https://darkcoder.ai"><img src="https://ajendra.info/uploads/projects/darkcoder-ai.jpg" width="92%" alt="DarkCoder.ai screenshot"/></a>
  <br/><sub>🖥️ Live at <a href="https://darkcoder.ai"><b>darkcoder.ai</b></a></sub>
</div>

## 🚀 Features

<div align="center">
  <img src="./assets/features.svg" width="100%" alt="DarkCoder.ai feature highlights"/>
</div>

| Feature | What it does |
|:--|:--|
| **Unified endpoint** | One OpenAI-compatible API in front of every provider you own. |
| **Auto fallback** | Rate-limited or down? Requests roll over to the next provider. |
| **Bring your accounts** | Copilot, Claude, Gemini, Grok, DeepSeek and local Ollama. |
| **Encrypted keys** | Provider keys stored encrypted; gateway keys are revocable. |
| **Admin cockpit** | Manage providers, keys and usage from one dashboard. |
| **Desktop + IDE** | Windows app, VS Code extension and a built-in AI chat. |

## 🧰 Tech Stack

<div align="center">

<img src="https://img.shields.io/badge/AI_Gateway-8b5cf6?style=for-the-badge" alt="AI Gateway"/>
<img src="https://img.shields.io/badge/OpenAI_compatible-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI compatible"/>
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama"/>
<img src="https://img.shields.io/badge/VS_Code_extension-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VS Code extension"/>
<img src="https://img.shields.io/badge/Windows_app-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows app"/>

</div>

## 🏗️ Architecture

```mermaid
flowchart LR
    A["VS Code / Windows app / any OpenAI client"] -->|"OpenAI-compatible API"| G{{"DarkCoder.ai gateway"}}
    G --> K[("Encrypted key vault")]
    G -->|primary| C1["GitHub Copilot"]
    G -.->|fallback| C2["Claude"]
    G -.->|fallback| C3["Gemini / Grok / DeepSeek"]
    G -.->|local| C4["Ollama"]
```

## 🔒 Source Code

> [!NOTE]
> This is a **showcase repository**. The production source code of **DarkCoder.ai** is private and is not published here.
> Want a walkthrough, a similar build for your business, or licensing? **[Get in touch →](https://ajendra.info/contact)**

## 👤 Author

<div align="center">

**Ajendra** — Full Stack Developer · Security Researcher · AI Engineer · Startup Advisor

<a href="https://ajendra.info"><img src="https://img.shields.io/badge/Website-ajendra.info-8b5cf6?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"/></a>
<a href="https://github.com/ajendras"><img src="https://img.shields.io/badge/GitHub-ajendras-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="https://www.instagram.com/me_ajendra/"><img src="https://img.shields.io/badge/Instagram-me__ajendra-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/></a>
<a href="mailto:contact@ajendra.info"><img src="https://img.shields.io/badge/Email-contact%40ajendra.info-ec4899?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email"/></a>

<sub>⭐ If you like this project, star the repo — and check out my other work on <a href="https://ajendra.info/projects">ajendra.info/projects</a>.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:030712,50:22c55e,100:a855f7&height=120&section=footer" width="100%" alt=""/>

</div>
