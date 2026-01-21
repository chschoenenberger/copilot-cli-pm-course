# GitHub Copilot CLI Reference

A quick reference guide for using GitHub Copilot CLI as a Product Manager.

---

## Getting Started

### Installation

```bash
# Windows (WinGet)
winget install GitHub.Copilot

# macOS/Linux (Homebrew)
brew install copilot-cli

# All platforms (npm)
npm install -g @github/copilot
```

### Authentication

```bash
copilot              # Start Copilot CLI
/login               # Authenticate with GitHub (first time)
/model               # Change AI model
exit                 # Exit Copilot CLI
```

---

## Core Concepts

### Project Memory

Copilot automatically reads `.github/copilot-instructions.md` for context about your project. Use this to define:
- Project overview
- Terminology
- Writing guidelines
- Behavioral rules

### Agents

| Agent | Purpose | Best For |
|-------|---------|----------|
| `explore` | Fast Q&A about files | Finding information |
| `task` | Run commands | Build/test scripts |
| `general-purpose` | Complex multi-step work | Deep analysis |
| `code-review` | Review code changes | PR reviews |

---

## Common PM Tasks

### Reading Files

```
> Read filename.md

> What's in the company-context folder?

> Summarize all markdown files in this directory
```

### Creating Files

```
> Create a file called notes.md with the following content:
> [your content here]

> Save this summary to outputs/report.md
```

### Searching

```
> Find all files mentioning "activation"

> Search for SSO in all markdown files

> What files mention user personas?
```

### Processing Documents

```
> Read meeting-notes.md and create a clean summary with:
> 1. Key decisions
> 2. Action items
> 3. Next steps

> Transform this spec into user stories

> Create an executive summary of this research
```

### Multi-Perspective Review

```
> Review this PRD from an engineer's perspective

> What would a designer say about this feature spec?

> Give me executive-level feedback on this proposal
```

---

## Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| Submit prompt | Enter |
| Cancel | Ctrl+C |
| Clear screen | Ctrl+L |
| Previous prompt | Up arrow |
| Exit | Type `exit` or Ctrl+D |

---

## Tips for PMs

### Be Specific

```
# Less effective
> Summarize this

# More effective
> Summarize this document in 5 bullet points, 
> focusing on customer impact and technical risks
```

### Iterate

Don't try to get it perfect in one prompt:
1. Get the basic structure
2. Review the output
3. Ask for specific changes
4. Repeat

### Save Your Work

```
> Save this to outputs/filename.md
```

### Use Personas

```
> As a senior engineer, review this spec and identify:
> - Technical risks
> - Missing details
> - Effort estimates
```

---

## Troubleshooting

### "copilot: command not found"

Ensure npm global bin is in your PATH:
```bash
export PATH="$PATH:$(npm config get prefix)/bin"
```

### Files not found

Make sure you're in the correct directory:
```bash
pwd  # Check current directory
```

### Authentication issues

```bash
copilot auth logout
copilot auth login
```

---

## Related Documentation

- [GitHub Copilot Documentation](https://docs.github.com/en/copilot)
- [Copilot CLI GitHub Repository](https://github.com/githubnext/github-copilot-cli)

---

*Part of the Copilot CLI PM Course*
