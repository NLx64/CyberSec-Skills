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

![Building](https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&pause=1000&color=F7B93E&center=true&vCenter=true&width=435&lines=Building+detection+skills...;Adding+incident+response+workflows...;Documenting+malware+analysis+procedures...;Stay+tuned+for+updates!)

</div>

---

## 📖 About

This repository contains a collection of **Agent Skills** designed for defensive security operations. Skills are versioned, reusable procedures that AI agents can execute to assist security analysts with common tasks.

Based on the [Agent Skills open standard](https://agentskills.io), these skills work across multiple platforms including **Claude Code**, **GitHub Copilot**, **Codex**, and other compatible AI agents.

> 📝 Read the full article: [Agent Skills for Defensive Automation](https://nlx64.github.io/blog/agent-skills-defensive-automation/)

---

## 🎯 Skill Categories

<table>
<tr>
<td align="center" width="33%">

### 🚨 Incident Response

Skills for standardizing incident handling procedures

</td>
<td align="center" width="33%">

### 🔬 Malware Analysis

Automated analysis and threat reporting

</td>
<td align="center" width="33%">

### 📄 Document Analysis

Triage and analysis of suspicious files

</td>
</tr>
</table>

---

## 📦 Available Skills

| Skill | Category | Description | Status |
|-------|----------|-------------|--------|
| `initial-incident-intake` | Incident Response | Standardizes first-hour incident response procedures | 🔜 Coming Soon |
| `malware-analysis` | Malware Analysis | Produces analyst-grade threat reports with structured reasoning | 🔜 Coming Soon |
| `pdf-triage-plus` | Document Analysis | Structural analysis of suspicious documents | 🔜 Coming Soon |

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
# Add to your Claude Code configuration
claude config add skill ./skills/incident-response/initial-incident-intake
```

### Skill Structure

```
skills/
├── incident-response/
│   └── initial-incident-intake/
│       └── SKILL.md
├── malware-analysis/
│   └── malware-analysis/
│       └── SKILL.md
└── document-analysis/
    └── pdf-triage-plus/
        └── SKILL.md
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

When using AI agents for security operations, consider:

- **Prompt Injection**: Analyzed artifacts may contain malicious content
- **Supply Chain**: Validate skill sources before use
- **Hallucination**: Always verify agent outputs with human review
- **Approval Gates**: Implement human-in-the-loop for critical actions

---

## 🤝 Contributing

Contributions are welcome! If you have skills to share:

1. Fork the repository
2. Create your skill following the standard format
3. Add documentation and examples
4. Submit a Pull Request

See [CONTRIBUTING.md](docs/CONTRIBUTING.md) for detailed guidelines.

---

## 📚 Resources

- [Agent Skills Standard](https://agentskills.io) - Official specification
- [Blog Post](https://nlx64.github.io/blog/agent-skills-defensive-automation/) - Detailed explanation and use cases
- [Claude Code Documentation](https://docs.anthropic.com/claude-code) - Platform integration

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

### 👨‍💻 Author

**Nathan Ferreira** — [@NLx64](https://github.com/NLx64)

[![GitHub](https://img.shields.io/badge/GitHub-NLx64-181717?style=flat-square&logo=github)](https://github.com/NLx64)
[![Website](https://img.shields.io/badge/Website-nlx64.github.io-0A66C2?style=flat-square&logo=safari&logoColor=white)](https://nlx64.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nathan-ferreira-067035193/)

---

*Building AI-powered tools for the security community*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0A66C2&height=80&section=footer"/>

</div>
