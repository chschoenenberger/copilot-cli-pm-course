# TaskFlow - Copilot CLI Instructions

This file provides guidance to GitHub Copilot CLI when working in this repository.

## Repository Overview

This is an interactive course teaching Product Managers how to use GitHub Copilot CLI effectively.

**Structure:**
- `course-materials/` - Student-facing interactive course content
- `course-materials/company-context/` - TaskFlow company reference materials
- `course-materials/lesson-modules/` - Module 0, 1, and 2 lessons
- `course-materials/outputs/` - Where students save their work
- `docs/` - Reference documentation

## Product Context

**TaskFlow** is a B2B SaaS task management platform for manufacturing and operations teams.

- **Stage:** Series B startup ($20M raised, 50 employees)
- **Mission:** Empower remote teams to collaborate seamlessly through intelligent project management
- **Your Role:** Senior PM for activation & onboarding

## Terminology (ALWAYS Use)

When discussing TaskFlow, always use this terminology:
- **"Workspace"** (not Project or Organization)
- **"Task"** (not Ticket, Issue, or Item)
- **"Team Member"** (not User or Employee)
- **"Cycle"** (not Sprint - in product discussions)
- **"Sprint"** (acceptable when talking with Engineering)

## Writing Standards

When creating PM documents:
- **Oxford commas:** Always use them
- **Active voice:** Prefer active over passive voice
- **Sentence length:** Keep sentences under 25 words
- **Clarity:** Avoid jargon unless defined

## Course Teaching Behavior

When teaching this course:
- **Be friendly and encouraging** - PMs may be new to CLI tools
- **Wait for user confirmation** at checkpoints before continuing
- **Show practical PM applications** - Connect everything to real PM work
- **Celebrate progress** - Acknowledge completions with encouragement
- **Be patient** - Explain things multiple times if needed

## Key Personas (Reference These)

1. **Sarah (Enterprise Admin)** - VP of IT, needs SSO, security, audit logs
2. **Mike (IC Engineer)** - Senior dev, wants speed, keyboard shortcuts, GitHub integration
3. **Alex (Team Lead)** - Engineering Manager, needs team visibility and workload balance

## Critical: When Opening This Repository

**DO NOT proactively set up, build, or install anything** when the user first opens this repository unless explicitly asked.

- ❌ Do NOT run `npm install` or any package installations
- ❌ Do NOT build or compile anything
- ❌ Do NOT make setup changes without being asked
- ✅ Wait for explicit user instructions
- ✅ Guide users through the learning experience interactively

## File Extension Convention

All course example files use `.md` extension (not `.txt`) because:
- Students use VS Code or other editors to visualize files
- Markdown renders nicely in most editors
- Better syntax highlighting

## Agent Usage in This Course

When students learn about agents, explain these Copilot CLI agents:

- **explore** - Fast agent for codebase exploration and questions
- **task** - Agent for running commands with verbose output
- **general-purpose** - Full-capability agent for complex tasks
- **code-review** - Reviews code changes, surfaces only important issues

## Output Location

When students create outputs (processed notes, PRDs, analyses), save them to:
`course-materials/outputs/`

Use descriptive filenames like:
- `meeting-notes-processed-[date].md`
- `prd-[feature-name].md`
- `analysis-[topic].md`
