# GitHub Copilot CLI PM Course

An interactive course teaching **Product Managers** how to use **GitHub Copilot CLI** effectively for their daily work.

> **Adapted from** the excellent [Claude Code PM Course](https://github.com/carlvellotti/claude-code-pm-course) by Carl Vellotti.

## What You'll Learn

- **File Operations** - Read, search, organize, and manage PM documents
- **Agents** - Use explore, task, and code-review agents for parallel workflows
- **Custom Agents & MCP** - Create specialized reviewers and extend capabilities
- **Project Memory** - Use `copilot-instructions.md` to customize Copilot's behavior
- **Real PM Workflows** - Write PRDs, analyze data, develop product strategy

## Course Structure

### Module 0: Getting Started
- **0.0 Introduction** - Course overview and what you'll learn
- **0.1 Installation** - Install GitHub Copilot CLI and prerequisites
- **0.2 Start & Clone** - Launch Copilot CLI and clone this course

### Module 1: Copilot CLI Fundamentals
- **1.1 Welcome** - Introduction to TaskFlow and the course project
- **1.2 Visualizing Files** - Set up your visual workspace with VS Code
- **1.3 First Tasks** - Process meeting notes, analyze research, work with files
- **1.4 Agents** - Use explore, task, and general-purpose agents
- **1.5 Custom Agents** - Create specialized agents with MCP servers
- **1.6 Project Memory** - Use copilot-instructions.md for context
- **1.7 Navigation** - Master file operations and searches

### Module 2: Advanced PM Scenarios
- **2.1 Write a PRD** - Partner with AI to create product requirements
- **2.2 Analyze Data** - Data-driven product decisions with CSV analysis
- **2.3 Product Strategy** - Strategic planning and competitive analysis

## How to Use This Course

### Interactive Track (Recommended)

1. **Clone this repository:**
   ```bash
   git clone https://github.com/chschoenenberger/copilot-cli-pm-course.git
   cd copilot-cli-pm-course/course-materials
   ```

2. **Start Copilot CLI:**
   ```bash
   copilot
   ```

3. **Begin the first lesson:**
   ```
   Let's start Module 1.1 - Welcome to the course!
   ```

4. Follow the guided, hands-on lessons

### Reference Track
Each module has a `REFERENCE_GUIDE.md` that can be read standalone for quick reference.

## Key Differences from Claude Code

| Claude Code | Copilot CLI Equivalent |
|-------------|------------------------|
| `CLAUDE.md` | `.github/copilot-instructions.md` |
| `@filename` mentions | Direct file paths or `#file:` |
| `/start-1-1` slash commands | Natural language prompts |
| Parallel agents | `explore`, `task`, `code-review` agents |
| Custom sub-agents | Custom agents + MCP servers |

## Prerequisites

- **GitHub Copilot subscription** (Individual, Business, or Enterprise)
- **PowerShell v6+** (Windows) or Terminal (macOS/Linux)
- Basic familiarity with product management
- Willingness to learn command-line basics

## Quick Start

```bash
# Install GitHub Copilot CLI

# Windows (via WinGet)
winget install GitHub.Copilot

# macOS/Linux (via Homebrew)
brew install copilot-cli

# Or via npm (all platforms)
npm install -g @github/copilot
```

```bash
# Launch and authenticate
copilot
# On first launch, use /login to authenticate with GitHub

# Clone and start the course
git clone https://github.com/chschoenenberger/copilot-cli-pm-course.git
cd copilot-cli-pm-course/course-materials
copilot
```

## About This Course

This course teaches PMs how to use GitHub Copilot CLI as a thinking partner, not just an automation tool. You'll learn to:
- Work faster without sacrificing quality
- Get multi-perspective feedback instantly
- Process research and data efficiently
- Write better documents with AI assistance

**Time to Complete:** ~4-6 hours for full interactive track

## The TaskFlow Company

Throughout this course, you'll work for **TaskFlow**, a fictional B2B SaaS task management platform for remote teams. Think "Asana meets Linear, but built for async-first companies."

- **Stage:** Series B startup ($20M raised, 50 employees)
- **Your Role:** Senior PM for activation & onboarding
- **Product:** Task management for manufacturing/operations teams

All context is pre-created - you're stepping into a working company!

## License

This work is licensed under [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/).

Adapted from the original Claude Code PM Course by Carl Vellotti.
You may view and share this course content with attribution, but commercial use and modifications are not permitted.

---

**Ready to level up your PM skills with AI? Let's go! 🚀**
