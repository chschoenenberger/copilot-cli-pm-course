# Module 1.3: First Tasks

## Process Meeting Notes, Analyze Research, Transform Documents

**Estimated time:** 25 minutes

---

## What You'll Learn

This is where it gets practical! You'll learn to:
1. ✅ Process messy meeting notes into clear summaries
2. ✅ Analyze user research interviews
3. ✅ Transform documents between formats
4. ✅ Save outputs for later use

---

## Task 1: Process Meeting Notes

PMs spend hours turning messy meeting notes into useful summaries. Let's automate that!

### The Source Material

Look at `meeting-notes-raw.md` in this folder. It's a realistic, messy set of notes from a product planning meeting.

### Exercise: Transform the Notes

**Ask Copilot:**

```
> Read the meeting-notes-raw.md file in this folder.
> 
> Create a clean meeting summary with:
> 1. Meeting info (date, attendees, purpose)
> 2. Key decisions made
> 3. Action items (who, what, when)
> 4. Open questions
> 5. Next steps
> 
> Save it to outputs/meeting-notes-processed.md
```

### Review Your Output

Open `outputs/meeting-notes-processed.md` in VS Code. 

**Quality check:**
- Are the action items clear and assigned?
- Did it capture the key decisions?
- Is anything missing?

### Iterate

```
> The meeting notes look good, but:
> 1. Add a "Risks & Concerns" section
> 2. Format action items as a table with columns: Item, Owner, Due Date
> Update the file.
```

---

## Task 2: Analyze User Research

PMs synthesize dozens of interviews. Let's practice with user research notes.

### The Source Material

Look at `user-research-notes.md` in this folder. It contains notes from 3 user interviews.

### Exercise: Create Research Synthesis

**Ask Copilot:**

```
> Read the user-research-notes.md file.
> 
> Create a research synthesis that includes:
> 1. Executive summary (3-5 sentences)
> 2. Key themes across all interviews
> 3. Notable quotes (verbatim)
> 4. Pain points ranked by frequency
> 5. Opportunities identified
> 6. Recommended next steps
> 
> Save to outputs/research-synthesis.md
```

### Make it Actionable

```
> Based on this synthesis, create a prioritized list of 5 product improvements
> with effort estimates (Low/Medium/High) and potential impact.
> Add this as a new section in the synthesis.
```

---

## Task 3: Multi-Format Output

Sometimes you need the same content in different formats.

### Exercise: Stakeholder Communication

You need to share findings with different audiences.

**For Leadership (brief):**
```
> Based on the research synthesis, create a 1-paragraph executive briefing
> suitable for a Slack message to leadership.
> Save to outputs/research-exec-brief.md
```

**For Engineers (detailed):**
```
> Based on the research synthesis, create technical requirements
> for the top 3 pain points. Include:
> - User story format
> - Acceptance criteria
> - Technical considerations
> Save to outputs/research-tech-requirements.md
```

**For Design (visual):**
```
> Based on the research synthesis, create a brief for the design team
> focusing on UX improvements. Include:
> - Problem statements
> - User goals
> - Success metrics
> Save to outputs/research-design-brief.md
```

---

## Task 4: Feature Spec Review

Let's work with an existing document.

### The Source Material

Look at `feature-spec-realtime-collab.md` - it's a spec for a new real-time collaboration feature.

### Exercise: Critique & Improve

**Ask Copilot:**

```
> Read the feature-spec-realtime-collab.md file.
> 
> Review this spec and provide:
> 1. What's well-written and clear
> 2. What's missing or unclear
> 3. Questions that should be answered
> 4. Risks not addressed
> 5. Suggested improvements
> 
> Be specific and reference exact sections.
```

---

## Key Techniques Learned

### 1. Structured Prompts

Be specific about what you want:
```
Create X with:
1. Section A
2. Section B
3. Section C
Save to [location]
```

### 2. Iterative Refinement

Don't try to get it perfect in one prompt:
1. Get the basic structure
2. Review the output
3. Ask for specific changes
4. Repeat until satisfied

### 3. Multi-Audience Outputs

Same information, different formats:
- Leadership: Brief, impact-focused
- Engineering: Detailed, technical
- Design: User-focused, visual

### 4. Document Analysis

Copilot can critique and review:
- Find gaps
- Identify risks
- Suggest improvements

---

## Checkpoint ✅

Before moving on, make sure you can:
- [ ] Process messy notes into clean summaries
- [ ] Create research synthesis from interviews
- [ ] Generate outputs for different audiences
- [ ] Have Copilot review and critique documents

---

## Next Steps

In **Module 1.4: Agents**, you'll learn to use Copilot's specialized agents for parallel work and multi-perspective feedback.

**Tell Copilot:**
```
Let's start Module 1.4 - Agents
```

---

**Excellent work on your first real tasks! 💪**
