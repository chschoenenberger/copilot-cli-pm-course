# Module 1.6: Project Memory

## Use copilot-instructions.md for Context and Instructions

**Estimated time:** 15 minutes

---

## What You'll Learn

Copilot CLI automatically reads `.github/copilot-instructions.md` to understand your project. You'll learn to:

1. ✅ Understand how project memory works
2. ✅ Create effective instruction files
3. ✅ Customize Copilot's behavior
4. ✅ Maintain context across sessions

---

## How Project Memory Works

### The copilot-instructions.md File

When Copilot CLI starts in a directory, it looks for:
```
.github/copilot-instructions.md
```

This file tells Copilot:
- What the project is about
- Terminology to use
- How to behave
- Important context

### Why It Matters

Without project memory, every conversation starts from zero. With it:
- ✅ Consistent terminology
- ✅ Relevant context always available
- ✅ Custom behavior rules
- ✅ Less repetitive prompting

---

## Exercise 1: Explore the Course Instructions

Let's look at how this course uses project memory.

```
> Read the .github/copilot-instructions.md file and summarize:
> 1. What does it tell you about TaskFlow?
> 2. What terminology rules does it set?
> 3. What behavior rules does it define?
```

---

## Exercise 2: Test the Terminology

The instructions file defines specific terminology. Let's test it!

**Ask Copilot:**

```
> Write a short paragraph about a user creating their first project in TaskFlow.
```

**Check the output:**
- Did it use "Workspace" instead of "Project" (for the container)?
- Did it use "Task" instead of "Ticket"?
- Did it use "Team Member" instead of "User"?

If not, the instructions might need strengthening!

---

## Exercise 3: Create Your Own Instructions

Let's create a custom instructions file for a hypothetical project.

```
> Create a copilot-instructions.md file for a new project with these requirements:
> 
> Project: Customer Support Dashboard
> Company: Acme Corp
> 
> Terminology:
> - "Case" not "Ticket"
> - "Agent" not "Representative"
> - "Resolution" not "Solution"
> 
> Writing style:
> - Professional but friendly
> - Always use active voice
> - Keep sentences under 20 words
> 
> Behavior:
> - When asked about metrics, always include comparison to last period
> - When creating reports, include an executive summary first
> - Always suggest next steps at the end of analyses
> 
> Save to outputs/sample-copilot-instructions.md
```

---

## Anatomy of a Good Instructions File

### Structure

```markdown
# Project Name - Copilot Instructions

## Project Overview
[What this project is and what Copilot should know]

## Terminology
[Specific terms to use and avoid]

## Writing Standards
[Style guidelines for content]

## Behavior Rules
[How Copilot should act in different situations]

## Key Context
[Important background information]
```

### Best Practices

| Do | Don't |
|----|-------|
| Be specific | Use vague instructions |
| Give examples | Assume Copilot knows context |
| Define terms | Use jargon without definition |
| Set clear rules | Give contradictory guidance |

---

## Exercise 4: Improve Instructions

The course's instructions file could always be better. Let's improve it!

```
> Read the current .github/copilot-instructions.md and suggest 3 specific improvements:
> 1. What's missing that would help Copilot understand the course better?
> 2. What rules could be clearer?
> 3. What examples would help?
> 
> Create an improved version and save to outputs/improved-instructions.md
```

---

## Memory Hierarchy

Copilot can read context from multiple levels:

| Level | Location | Scope |
|-------|----------|-------|
| Global | User settings | All projects |
| Project | `.github/copilot-instructions.md` | This project |
| Session | Conversation | Current chat |

Project instructions override global; session context adds to both.

---

## Key Concepts

### 1. Automatic Loading

No need to reference the file - Copilot reads it automatically.

### 2. Persistent Context

Instructions persist across sessions and conversations.

### 3. Behavioral Rules

You can define not just what Copilot knows, but how it behaves.

### 4. Team Consistency

Everyone on the team gets the same context and behavior.

---

## Checkpoint ✅

Before moving on, make sure you:
- [ ] Understand where copilot-instructions.md lives
- [ ] Can create effective instruction files
- [ ] Know how to customize Copilot's behavior

---

## Next Steps

In **Module 1.7: Navigation**, you'll master file operations, searching, and navigating complex projects efficiently.

**Tell Copilot:**
```
Let's start Module 1.7 - Navigation
```

---

**You've learned to shape Copilot's memory! 🧠**
