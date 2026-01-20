# Contributing to CyberSec Skills

Thank you for your interest in contributing! This document provides guidelines for contributing skills to this repository.

## How to Contribute

### 1. Fork and Clone

```bash
git clone https://github.com/YOUR_USERNAME/CyberSec-Skills.git
cd CyberSec-Skills
```

### 2. Create a New Skill

1. Choose the appropriate category directory under `skills/`
2. Create a new directory with your skill name (use kebab-case)
3. Add a `SKILL.md` file following the format below

### 3. Skill Format

Every skill must include YAML frontmatter:

```yaml
---
name: your-skill-name
description: A brief description (used for skill matching)
version: 1.0.0
author: YourGitHubUsername
tags: [relevant, tags, here]
---

# Skill Title

## Overview
Describe what this skill does and when to use it.

## Instructions
Detailed instructions for the AI agent to follow.

## Inputs
What information the skill expects.

## Outputs
What the skill produces.
```

### 4. Submit a Pull Request

1. Create a feature branch: `git checkout -b add-skill-name`
2. Commit your changes: `git commit -m "feat: add skill-name skill"`
3. Push to your fork: `git push origin add-skill-name`
4. Open a Pull Request

## Guidelines

### Do's

- Follow the Agent Skills standard format
- Include clear, actionable instructions
- Add relevant tags for discoverability
- Test your skill before submitting
- Document any dependencies or requirements

### Don'ts

- Don't include sensitive information or credentials
- Don't create skills that could be used maliciously
- Don't submit incomplete or untested skills

## Code of Conduct

- Be respectful and constructive
- Focus on improving security operations
- Share knowledge openly

## Questions?

Open an issue or reach out to [@NLx64](https://github.com/NLx64).

---

*Thank you for helping build tools for the security community!*
