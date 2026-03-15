# Contributing to AI Agent Skills ü§ù

Thank you for your interest in contributing! This document provides guidelines and instructions for contributing.

## üìã Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
- [Skill Submission Guidelines](#skill-submission-guidelines)
- [Development Setup](#development-setup)
- [Style Guidelines](#style-guidelines)
- [License](#license)

## Code of Conduct

By participating in this project, you agree to maintain a respectful and inclusive environment. Please be considerate of others and follow these principles:

- Use welcoming and inclusive language
- Be respectful of differing viewpoints
- Gracefully accept constructive criticism
- Focus on what is best for the community
- Show empathy towards other community members

## How to Contribute

### Reporting Issues

1. Check if the issue already exists
2. Use the issue template
3. Provide clear reproduction steps
4. Include relevant environment details

### Submitting Changes

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

## Skill Submission Guidelines

### Skill Structure

```
skills/your-skill-name/
‚îú‚îÄ‚îÄ SKILL.md              # Required: Main skill definition
‚îú‚îÄ‚îÄ README.md             # Required: Documentation
‚îú‚îÄ‚îÄ scripts/              # Optional: Utility scripts
‚îú‚îÄ‚îÄ references/           # Optional: Detailed guides
‚îî‚îÄ‚îÄ examples/             # Optional: Usage examples
```

### SKILL.md Requirements

```markdown
---
name: your-skill-name
description: |
  Clear description of what the skill does.
  When it should be used.
  What problems it solves.
---

# Your Skill Name

## Core Concept
[Brief explanation]

## Main Features
- Feature 1
- Feature 2

## Usage Examples
[Practical examples]
```

### Quality Checklist

- [ ] SKILL.md has proper YAML frontmatter
- [ ] Description is clear and comprehensive
- [ ] Includes practical examples
- [ ] Has appropriate references/links
- [ ] No personal information or API keys
- [ ] Respects copyright and licenses
- [ ] Tested and working

### Content Guidelines

**DO:**
- ‚ú?Provide clear, actionable content
- ‚ú?Include working code examples
- ‚ú?Reference official documentation
- ‚ú?Credit original sources
- ‚ú?Use inclusive language

**DON'T:**
- ‚ù?Include personal information
- ‚ù?Add API keys or secrets
- ‚ù?Copy copyrighted content without attribution
- ‚ù?Submit untested code
- ‚ù?Use offensive language

## Development Setup

### Prerequisites

```bash
# Python 3.8+
python --version

# Git
git --version

# OpenClaw (optional, for testing)
openclaw --version
```

### Local Setup

```bash
# Clone your fork
git clone https://github.com/Pete2048/ai-agent-skills.git
cd ai-agent-skills

# Install dependencies (if any)
pip install -r requirements.txt

# Create a test skill
cp -r templates/skill-template skills/test-skill
```

### Testing Your Skill

```bash
# Package the skill
cd skills/your-skill
openclaw skills package .

# Install locally
openclaw skills install your-skill.skill

# Test in a conversation
# Mention keywords that should trigger the skill
```

## Style Guidelines

### Markdown Style

- Use ATX style headers (`# Header`)
- Include blank lines before/after headers
- Use fenced code blocks with language hints
- Keep line length under 100 characters
- Use tables for structured data

### Code Style

- Follow PEP 8 for Python
- Use meaningful variable names
- Add comments for complex logic
- Include docstrings for functions
- Test edge cases

### Documentation Style

- Write clear, concise sentences
- Use active voice
- Include practical examples
- Provide context and rationale
- Link to relevant resources

## License

By contributing to this project, you agree that your contributions will be licensed under the MIT License.

## Getting Help

- Open an issue for questions
- Join our community discussions
- Check existing documentation

## Recognition

Contributors will be recognized in:
- README acknowledgments
- Release notes
- GitHub contributors page

---

Thank you for contributing! üéâ
