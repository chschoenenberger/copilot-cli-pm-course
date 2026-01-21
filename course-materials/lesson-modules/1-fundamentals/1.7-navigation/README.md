# Module 1.7: Navigation

## Master File Operations and Searching

**Estimated time:** 15 minutes

---

## What You'll Learn

Efficiently navigating and searching files is essential for PM work. You'll learn to:

1. ✅ Search files by content
2. ✅ Find files by name patterns
3. ✅ Navigate complex folder structures
4. ✅ Perform bulk file operations

---

## Searching Files

### Search by Content

Find all files containing specific text:

```
> Find all files that mention "SSO" in the company-context folder
```

```
> Search for files containing "activation rate" anywhere in course-materials
```

### Search with Context

Get matches with surrounding context:

```
> Find mentions of "Sarah" in the personas file and show me the 
> surrounding context (5 lines before and after each mention)
```

### Search Patterns

Use patterns for flexible matching:

```
> Find all files mentioning any percentage (like 45%, 60%, etc.)
```

---

## Finding Files

### By Name

Find files matching a pattern:

```
> Find all markdown files in the lesson-modules folder
```

```
> Find all files named README.md in this repository
```

### By Type

Find files of specific types:

```
> Find all CSV files in the course
```

```
> List all image files (png, jpg, svg)
```

### By Location

Explore directory structure:

```
> What's in the company-context folder?
```

```
> Show me the structure of the 1-fundamentals folder
```

---

## Exercise 1: Information Hunt

Let's practice finding information across files.

**Task:** Find answers to these questions using search:

```
> Help me answer these questions by searching the course files:
> 
> 1. What is TaskFlow's current activation rate?
> 2. Which persona cares most about keyboard shortcuts?
> 3. What's the ARR goal for enterprise deals?
> 4. When is the mobile app supposed to launch?
> 
> Show me where you found each answer.
```

---

## Exercise 2: Content Audit

PMs often need to audit content across files.

```
> Audit all company-context files for:
> 1. Outdated information (dates in the past)
> 2. Placeholder text (TBD, TODO, [insert])
> 3. Inconsistent terminology
> 
> Create a report of findings.
```

---

## Exercise 3: Bulk Operations

Sometimes you need to work with many files at once.

### List and Summarize

```
> List all files in the 1-fundamentals folder and give me a 
> one-sentence summary of what each module covers
```

### Create an Index

```
> Create an index of all markdown files in course-materials with:
> - File path
> - Title (first heading)
> - Brief description
> 
> Save to outputs/course-index.md
```

---

## Navigation Shortcuts

### Quick File Access

Instead of navigating step by step:

```
# Long way:
> Go to company-context folder, then find personas file, then read it

# Short way:
> Read company-context/taskflow-personas.md
```

### Relative Paths

Use relative paths from current directory:

```
> Read ../company-context/taskflow-overview.md
```

### Glob Patterns

Use wildcards for multiple files:

```
> Read all *.md files in company-context/
```

---

## PM Navigation Scenarios

### Scenario 1: Preparing for a Meeting

```
> I have a meeting about enterprise features in 10 minutes.
> Find and summarize all content related to:
> - Enterprise customers
> - SSO
> - Security requirements
> - The TechCorp deal
```

### Scenario 2: Onboarding a New PM

```
> A new PM is joining the team. Create a reading list of the most
> important files in order, with a brief description of why each matters.
```

### Scenario 3: Quarterly Planning

```
> I'm preparing for Q2 planning. Find all mentions of:
> - Roadmap items
> - OKRs
> - Goals
> - Priorities
> 
> Compile into a planning reference document.
```

---

## Key Commands Summary

| Task | Example Prompt |
|------|----------------|
| Search content | "Find files mentioning X" |
| Find by name | "Find all files named X" |
| List contents | "What's in folder X?" |
| Show structure | "Show me the structure of X" |
| Bulk read | "Read all .md files in X" |
| Create index | "Create an index of all files in X" |

---

## Checkpoint ✅

Before moving on, make sure you can:
- [ ] Search files by content
- [ ] Find files by name and type
- [ ] Navigate folder structures efficiently
- [ ] Perform bulk operations on multiple files

---

## Module 1 Complete! 🎉

You've finished all of Module 1: Copilot CLI Fundamentals!

**What you've learned:**
- ✅ Basic Copilot CLI interaction
- ✅ Visual workspace setup
- ✅ Processing and transforming documents
- ✅ Using specialized agents
- ✅ Creating custom workflows
- ✅ Project memory with instructions
- ✅ File navigation and searching

---

## Next Steps

Ready for advanced PM workflows? Module 2 covers:
- **2.1 Write a PRD** - Create professional product requirements
- **2.2 Analyze Data** - Work with CSV data and metrics
- **2.3 Product Strategy** - Strategic planning and competitive analysis

**Tell Copilot:**
```
Let's start Module 2.1 - Write a PRD
```

---

**Congratulations on completing Module 1! 🏆**
