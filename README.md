<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0A66C2&height=120&section=header"/>

# 🛡️ CyberSec Skills

**Reusable AI Agent Skills for Defensive Security Operations**

[![Under Construction](https://img.shields.io/badge/Status-Under%20Construction-yellow?style=for-the-badge&logo=construction&logoColor=white)](https://github.com/NLx64/CyberSec-Skills)
[![Agent Skills](https://img.shields.io/badge/Standard-Agent%20Skills-0A66C2?style=for-the-badge)](https://agentskills.io)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

<br>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700">

<br>

### 🚧 This repository is actively being developed 🚧

*New skills and improvements are being added regularly*

![Building](https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&pause=1000&color=F7B93E&center=true&vCenter=true&width=435&lines=Building+detection+skills...;Sharing+with+the+community...;Open+source+security+tools...;Stay+tuned+for+updates!)

</div>

---

## 📖 About

Hey! This repo is my way of giving back to the infosec community.

I've been building AI-powered skills to help security analysts automate repetitive tasks and focus on what really matters — finding threats and protecting systems. Everything here is **open source** and free to use.

The goal is simple: **share practical tools that actually help defenders**. No fluff, just stuff that works.

These skills follow the [Agent Skills open standard](https://agentskills.io), so they work with **Claude Code**, **GitHub Copilot**, **Codex**, and other AI agents. Use them, fork them, improve them — that's what open source is about.

> 📝 Want to understand the "why" behind this? Check out my post: [Agent Skills for Defensive Automation](https://nlx64.github.io/blog/agent-skills-defensive-automation/)

---

## 📦 Available Skills

| Skill | Category | Description | Status |
|-------|----------|-------------|--------|
| `pdf-triage-plus` | Document Analysis | Static triage for suspicious PDFs — catches what AV misses | 🚧 In Development |

*More skills coming soon...*

---

## 🚀 Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/NLx64/CyberSec-Skills.git

# Navigate to the skills directory
cd CyberSec-Skills/skills
```

### Usage with Claude Code

```bash
# Add a skill to your configuration
claude config add skill ./skills/document-analysis/pdf-triage-plus
```

---

## 📋 Skill Format

Each skill follows the Agent Skills standard with YAML frontmatter:

```yaml
---
name: skill-name
description: Brief description of what the skill does
version: 1.0.0
author: NLx64
tags: [security, detection, blue-team]
---

# Skill Instructions

Detailed instructions for the AI agent...
```

---

## ⚠️ Security Considerations

When using AI agents for security operations, keep in mind:

- **Prompt Injection**: Analyzed artifacts may contain malicious content
- **Hallucination**: Always verify agent outputs with human review
- **Approval Gates**: Implement human-in-the-loop for critical actions

---

## 🤝 Contributing

Got a skill that could help other defenders? PRs are welcome!

1. Fork the repository
2. Create your skill following the standard format
3. Submit a Pull Request

See [CONTRIBUTING.md](docs/CONTRIBUTING.md) for guidelines.

---

## 📚 Resources

- [Agent Skills Standard](https://agentskills.io) - Official specification
- [Blog Post](https://nlx64.github.io/blog/agent-skills-defensive-automation/) - Why I'm building this

---

## 📄 License

MIT License — use it however you want.

---

<div align="center">

### 👨‍💻 Author

**Nathan Ferreira** — [@NLx64](https://github.com/NLx64)

[![GitHub](https://img.shields.io/badge/GitHub-NLx64-181717?style=flat-square&logo=github)](https://github.com/NLx64)
[![Website](https://img.shields.io/badge/Website-nlx64.github.io-0A66C2?style=flat-square&logo=safari&logoColor=white)](https://nlx64.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nathan-ferreira-067035193/)

---

*Building tools for defenders, by a defender*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0A66C2&height=80&section=footer"/>

</div>
