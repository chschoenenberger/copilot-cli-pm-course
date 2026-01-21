# Module 1.4: Agents

## Use Specialized Agents for Parallel Work

**Estimated time:** 20 minutes

---

## What You'll Learn

Copilot CLI has specialized **agents** - think of them as experts you can call on for specific tasks. You'll learn to:

1. ✅ Use the `explore` agent for codebase questions
2. ✅ Use the `task` agent for running commands
3. ✅ Use agents for parallel processing
4. ✅ Get multi-perspective feedback

---

## Meet the Agents

### 🔍 explore

**Purpose:** Fast exploration and Q&A about files and code

**Best for:**
- "How does X work?"
- "Find all files that mention Y"
- "Summarize this folder"

**Example:**
```
Use the explore agent to find all files that mention "SSO" in the company-context folder
```

### ⚙️ task

**Purpose:** Run commands and see results

**Best for:**
- Running builds or tests
- Installing dependencies
- Executing scripts

**Example:**
```
Use the task agent to list all markdown files in this directory
```

### 🧠 general-purpose

**Purpose:** Complex, multi-step work

**Best for:**
- Tasks requiring multiple steps
- Complex analysis
- Work that needs all tools

### 📝 code-review

**Purpose:** Review code changes

**Best for:**
- Reviewing pull requests
- Finding bugs or issues
- Suggesting improvements

---

## Exercise 1: Parallel Processing with Explore

PMs often need to process many files at once. Let's use agents for parallel work!

### The Task

You have 10 meeting notes to process (in the `meeting-notes/` folder). Instead of doing them one by one, let's use the explore agent.

**Ask Copilot:**

```
> Use the explore agent to read all files in the meeting-notes folder
> and create a summary of:
> 1. All action items across all meetings
> 2. Key decisions made
> 3. Recurring themes or concerns
```

### Review

Notice how it processed multiple files efficiently. This would take you 30+ minutes manually!

---

## Exercise 2: Multi-Perspective Review

Want feedback from different viewpoints? Use agents with different personas!

### The Setup

Let's get feedback on the real-time collaboration spec from Module 1.3.

### Engineering Perspective

```
> Review the feature-spec-realtime-collab.md file from a senior engineer's perspective.
> Focus on:
> - Technical feasibility
> - Missing technical details
> - Risks and concerns
> - Effort estimates
```

### Executive Perspective

```
> Review the same spec from a VP of Product perspective.
> Focus on:
> - Business impact
> - Resource allocation
> - Timeline concerns
> - Strategic fit
```

### User Perspective

```
> Review the same spec from a power user's perspective.
> Focus on:
> - Will this solve real problems?
> - Usability concerns
> - Missing use cases
> - What would delight users?
```

---

## Exercise 3: Research Synthesis at Scale

You have multiple data sources to synthesize. Let's use agents efficiently.

### The Sources (in this folder)

- `meeting-notes/` - 10 meeting note files
- `survey-results.csv` - User survey data
- `sales-notes.md` - Sales team feedback

### The Task

```
> I need a comprehensive voice-of-customer report.
> 
> Use the explore agent to analyze:
> 1. All meeting notes in meeting-notes/
> 2. The survey-results.csv file
> 3. The sales-notes.md file
> 
> Create a report with:
> - Top 5 customer pain points (with evidence)
> - Feature requests ranked by frequency
> - Quotes that support each finding
> - Recommended priorities
> 
> Save to outputs/voice-of-customer-report.md
```

---

## When to Use Each Agent

| Situation | Best Agent |
|-----------|------------|
| Quick question about files | `explore` |
| Run a command/script | `task` |
| Complex multi-step analysis | `general-purpose` |
| Review code changes | `code-review` |
| Parallel file processing | `explore` |

---

## Key Concepts

### 1. Agents Work in Parallel

Agents can process multiple files simultaneously, much faster than sequential prompts.

### 2. Personas for Perspective

You can ask Copilot to adopt different personas (engineer, exec, user) for diverse feedback.

### 3. Synthesis Across Sources

Agents can pull together insights from multiple file types (markdown, CSV, etc.).

---

## Checkpoint ✅

Before moving on, make sure you can:
- [ ] Use the explore agent for file analysis
- [ ] Get multi-perspective feedback on documents
- [ ] Synthesize information across multiple sources

---

## Next Steps

In **Module 1.5: Custom Agents**, you'll learn to create your own specialized agents and extend Copilot's capabilities with MCP servers.

**Tell Copilot:**
```
Let's start Module 1.5 - Custom Agents
```

---

**You're mastering agents! 🤖**
