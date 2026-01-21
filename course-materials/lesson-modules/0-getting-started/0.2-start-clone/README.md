# Module 0.2: Start & Clone

## Get the Course Materials and Launch Copilot CLI

This module helps you clone the course repository and start your first Copilot CLI session.

---

## Step 1: Clone the Repository

Open your terminal and run:

```bash
# Clone the course repository
git clone https://github.com/chschoenenberger/copilot-cli-pm-course.git

# Navigate to course materials
cd copilot-cli-pm-course/course-materials
```

---

## Step 2: Explore the Structure

Take a look at what's included:

```bash
# List the course structure
ls -la

# You should see:
# - company-context/     (TaskFlow company files)
# - lesson-modules/      (Course modules)
# - outputs/             (Where you'll save work)
```

---

## Step 3: Start Copilot CLI

From the `course-materials` directory:

```bash
# Start Copilot CLI
copilot
```

You should see a welcome message and a prompt.

---

## Step 4: Your First Interaction

Try these commands to get oriented:

```
> What files are in this directory?

> Summarize the company-context folder

> What is TaskFlow?
```

---

## Understanding the Course Files

### Company Context
```
company-context/
├── taskflow-overview.md    # Company background, your role
├── taskflow-personas.md    # User personas (Sarah, Mike, Alex)
├── taskflow-product.md     # Product features and roadmap
└── taskflow-competitive.md # Competitive landscape
```

### Lesson Modules
```
lesson-modules/
├── 0-getting-started/      # Where you are now
├── 1-fundamentals/         # Core Copilot CLI skills
└── 2-advanced/             # Advanced PM workflows
```

### Outputs
```
outputs/                    # Save your work here
```

---

## Key Concepts

### Project Memory

Copilot CLI reads `.github/copilot-instructions.md` automatically. This gives it context about:
- What TaskFlow is
- Terminology to use
- How to behave in this course

### Working Directory

Copilot CLI can see and work with files in your current directory. That's why we start from `course-materials/`.

### Natural Language

You don't need special commands. Just talk to Copilot naturally:
- "Read the personas file and summarize it"
- "Create a new file called notes.md"
- "Search for all mentions of SSO"

---

## Quick Reference

| Action | What to Say |
|--------|-------------|
| List files | "What files are here?" |
| Read file | "Read taskflow-overview.md" |
| Create file | "Create a file called test.md with hello world" |
| Search | "Search for mentions of activation" |
| Get help | "How do I use agents?" |

---

## Next Steps

You're all set! When you're ready to begin the main course, tell Copilot:

```
Let's start Module 1.1 - Welcome to the course!
```

Or open the file directly:
```
lesson-modules/1-fundamentals/1.1-welcome/README.md
```

---

## Troubleshooting

### "I can't see the files"

Make sure you're in the `course-materials` directory:
```bash
pwd  # Should show .../copilot-cli-pm-course/course-materials
```

### "Copilot doesn't know about TaskFlow"

The copilot-instructions.md should be automatically loaded. Try:
```
> Read the copilot-instructions.md file from the .github folder
```

### "My changes aren't saving"

Make sure you ask Copilot to save:
```
> Save this to outputs/my-notes.md
```

---

**Ready to learn? Let's go! 🚀**
