# Module 1.5: Custom Agents

## Create Specialized Agents and Extend Capabilities

**Estimated time:** 15 minutes

---

## What You'll Learn

Beyond built-in agents, you can create **custom agents** and extend Copilot with **MCP servers**. You'll learn to:

1. ✅ Understand custom agent concepts
2. ✅ Create specialized reviewer personas
3. ✅ Learn about MCP server extensions
4. ✅ Set up reusable workflows

---

## Custom Agent Concepts

### What is a Custom Agent?

A custom agent is a specialized configuration that gives Copilot:
- A specific persona or expertise
- Focused instructions
- Particular tools or capabilities

### Use Cases for PMs

- **Spec Reviewer:** Reviews PRDs with engineering lens
- **Customer Advocate:** Evaluates features from user perspective
- **Competitor Analyst:** Analyzes competitive implications
- **Executive Summarizer:** Creates leadership-ready content

---

## Exercise 1: Create Persona-Based Reviews

Let's create three different reviewer "personas" for consistent feedback.

### The Engineer Reviewer

```
> I want you to act as "TechReviewer" - a senior staff engineer with 15 years experience.
> 
> When reviewing documents:
> - Focus on technical feasibility and edge cases
> - Question unclear requirements
> - Estimate complexity (Low/Medium/High)
> - Flag security and performance concerns
> - Use direct, concise language
> 
> Now review feature-spec-realtime-collab.md from the 1.3-first-tasks folder as TechReviewer.
```

### The Executive Reviewer

```
> Now switch to "ExecReviewer" - a VP of Product who reports to the CEO.
> 
> When reviewing documents:
> - Focus on business impact and ROI
> - Question resource allocation
> - Consider strategic fit
> - Flag timeline and dependency risks
> - Think about stakeholder communication
> 
> Review the same spec as ExecReviewer.
```

### The User Advocate

```
> Now switch to "UserAdvocate" - a UX researcher who has done 100+ user interviews.
> 
> When reviewing documents:
> - Focus on user needs and pain points
> - Question assumptions about user behavior
> - Identify missing use cases
> - Flag accessibility concerns
> - Reference our personas (Sarah, Mike, Alex)
> 
> Review the same spec as UserAdvocate.
```

---

## Exercise 2: Compile Multi-Perspective Feedback

Now let's synthesize the three reviews.

```
> Based on the TechReviewer, ExecReviewer, and UserAdvocate feedback,
> create a consolidated review summary with:
> 
> 1. Unanimous concerns (all three agreed)
> 2. Technical risks (from TechReviewer)
> 3. Business considerations (from ExecReviewer)
> 4. User experience gaps (from UserAdvocate)
> 5. Recommended changes prioritized by importance
> 
> Save to outputs/spec-multi-review.md
```

---

## MCP Servers (Advanced)

### What is MCP?

**Model Context Protocol (MCP)** allows Copilot to connect to external tools and services.

Examples:
- Connect to your database
- Query your analytics platform
- Access internal documentation
- Integrate with APIs

### Setting Up MCP (Overview)

MCP configuration typically involves:

1. **Install MCP Server:**
   ```bash
   npm install @modelcontextprotocol/server-filesystem
   ```

2. **Configure in settings:**
   ```json
   {
     "mcpServers": {
       "filesystem": {
         "command": "mcp-server-filesystem",
         "args": ["/path/to/allowed/directory"]
       }
     }
   }
   ```

3. **Use in prompts:**
   ```
   > Use the filesystem MCP to read files from /data/analytics/
   ```

### PM Use Cases for MCP

| MCP Server | PM Use Case |
|------------|-------------|
| Filesystem | Access broader file system |
| Database | Query product metrics |
| Slack | Search team discussions |
| GitHub | Access issues and PRs |
| Analytics | Pull user behavior data |

---

## Exercise 3: Reusable Workflow Template

Create a template for consistent spec reviews:

```
> Create a markdown template called "spec-review-workflow.md" that I can use
> for any feature spec review. Include:
> 
> 1. Pre-review checklist (what should be in the spec)
> 2. Three reviewer personas with their focus areas
> 3. Synthesis template for combining feedback
> 4. Decision matrix for prioritizing changes
> 
> Save to outputs/spec-review-workflow.md
```

---

## Key Concepts

### 1. Consistent Personas

Define personas once, use them repeatedly for consistent feedback.

### 2. Multi-Perspective Synthesis

Getting three viewpoints is more valuable than one deep dive.

### 3. Extensibility with MCP

MCP servers let you connect Copilot to your actual data and tools.

---

## Checkpoint ✅

Before moving on, make sure you:
- [ ] Understand how to create reviewer personas
- [ ] Can compile multi-perspective feedback
- [ ] Know what MCP servers are and their use cases

---

## Next Steps

In **Module 1.6: Project Memory**, you'll learn how copilot-instructions.md works and how to customize Copilot's behavior for your projects.

**Tell Copilot:**
```
Let's start Module 1.6 - Project Memory
```

---

**You're creating powerful custom workflows! 🛠️**
