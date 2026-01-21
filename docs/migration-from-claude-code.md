# Migration Guide: Claude Code → GitHub Copilot CLI

This guide helps users familiar with Claude Code transition to GitHub Copilot CLI.

---

## Overview

Both tools are terminal-based AI assistants, but they have different conventions and capabilities. This guide maps concepts between them.

---

## Key Differences

| Feature | Claude Code | Copilot CLI |
|---------|-------------|-------------|
| Project memory | `CLAUDE.md` | `.github/copilot-instructions.md` |
| File references | `@filename` mentions | Direct file paths |
| Custom commands | `/start-1-1` slash commands | Natural language prompts |
| Agents | Parallel agents, sub-agents | explore, task, code-review agents |
| Session management | Persistent sessions | Session per terminal |

---

## Project Memory

### Claude Code
```
CLAUDE.md (in project root)
```

### Copilot CLI
```
.github/copilot-instructions.md
```

Both files serve the same purpose: providing persistent context about your project.

### Migration

1. Copy content from `CLAUDE.md`
2. Create `.github/copilot-instructions.md`
3. Adapt any Claude-specific instructions

---

## File References

### Claude Code
```
Can you read @meeting-notes.md and summarize it?
```

### Copilot CLI
```
Can you read meeting-notes.md and summarize it?
```

Copilot CLI doesn't require the `@` prefix. Just use the filename or path directly.

---

## Custom Commands

### Claude Code
```
/start-1-1
/review-prd
/analyze-data
```

### Copilot CLI
```
Let's start Module 1.1
Review this PRD
Analyze this data file
```

Copilot CLI doesn't have slash commands. Use natural language instead.

---

## Agents

### Claude Code

Claude Code has a concept of parallel agents that can work simultaneously on different tasks.

### Copilot CLI

Copilot CLI has specialized agents:

| Copilot Agent | Similar to Claude Code... |
|---------------|---------------------------|
| `explore` | Quick exploration tasks |
| `task` | Running commands |
| `general-purpose` | Full analysis work |
| `code-review` | Document/code review |

**Usage:**
```
> Use the explore agent to find all files mentioning activation

> Review this code from a security perspective
```

---

## Common Patterns

### Reading Multiple Files

**Claude Code:**
```
Please read @file1.md @file2.md @file3.md and compare them
```

**Copilot CLI:**
```
Read file1.md, file2.md, and file3.md and compare them
```

### Creating Files

**Claude Code:**
```
Create a new file at outputs/summary.md with this content
```

**Copilot CLI:**
```
Create a file called outputs/summary.md with this content
```

### Searching

**Claude Code:**
```
Search for mentions of "SSO" in the codebase
```

**Copilot CLI:**
```
Find all files that mention "SSO"
```

---

## Capabilities Comparison

### Available in Both

✅ Read files
✅ Write/create files
✅ Search files
✅ Run commands
✅ Process documents
✅ Project-level context

### Claude Code Unique

- Slash commands
- `@` mentions
- Some custom agent configurations

### Copilot CLI Unique

- Native GitHub integration
- explore/task/code-review agent modes
- Different MCP server ecosystem

---

## Tips for Transitioning

### 1. Update Your Instructions File

Move from `CLAUDE.md` to `.github/copilot-instructions.md`.

### 2. Drop the `@` Prefix

Just use filenames directly.

### 3. Use Natural Language

Instead of `/command`, describe what you want:
- `/start-1-1` → "Let's start Module 1.1"
- `/review` → "Review this document"

### 4. Learn the Agents

Familiarize yourself with:
- `explore` for quick questions
- `task` for running commands
- `code-review` for reviewing changes

### 5. Same Mental Model

The core interaction is the same:
- Talk naturally
- Ask for file operations
- Iterate on outputs
- Save your work

---

## Quick Reference

| Claude Code | Copilot CLI Equivalent |
|-------------|------------------------|
| `CLAUDE.md` | `.github/copilot-instructions.md` |
| `@file.md` | `file.md` |
| `/command` | "Please [do action]" |
| Parallel agents | `explore` agent |
| Sub-agents | Custom personas in prompts |

---

## Getting Help

- Copilot CLI: `copilot --help`
- This course: See `docs/copilot-cli-reference.md`
- GitHub Docs: https://docs.github.com/en/copilot

---

*Part of the Copilot CLI PM Course*
