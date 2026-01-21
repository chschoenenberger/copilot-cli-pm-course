# Module 1.2: Visualizing Files

## Set Up Your Visual Workspace

**Estimated time:** 15 minutes

---

## What You'll Learn

Working in the terminal is powerful, but sometimes you want to SEE your files. This module shows you how to use VS Code alongside Copilot CLI.

By the end, you'll:
1. ✅ Have VS Code open next to your terminal
2. ✅ See file changes in real-time
3. ✅ Know how to work visually with Copilot CLI outputs

---

## Why Visual + Terminal?

**Terminal (Copilot CLI):**
- Great for processing, transforming, searching
- Fast for multi-file operations
- Powerful for complex tasks

**Visual Editor (VS Code):**
- See file structure at a glance
- Read and edit with syntax highlighting
- Better for reviewing long documents

**Best of both worlds:** Use them together!

---

## Setup: VS Code

### Step 1: Open VS Code

Open the course folder in VS Code:

```bash
# From terminal (in course-materials folder):
code .
```

Or:
1. Open VS Code
2. File → Open Folder
3. Navigate to `copilot-cli-pm-course/course-materials`

### Step 2: Arrange Your Windows

**Recommended layout:**
```
┌─────────────────────────────┐
│         VS Code             │
│   (file explorer + editor)  │
├─────────────────────────────┤
│    Terminal (Copilot CLI)   │
└─────────────────────────────┘
```

You can use VS Code's integrated terminal, or a separate terminal window.

### Step 3: Enable Auto-Refresh

VS Code auto-refreshes by default. When Copilot creates or modifies a file, you'll see it update automatically.

---

## Exercise 1: Watch Files Update

Let's see this in action!

**In VS Code:**
1. Open the `outputs/` folder in the sidebar
2. Keep it visible

**In Copilot CLI:**
```
> Create a file called outputs/visual-test.md with the content:
> # Visual Test
> This file was created by Copilot CLI!
> Current time: [include current timestamp]
```

**Watch VS Code:**
- You should see `visual-test.md` appear in the file explorer
- Click it to see the contents

---

## Exercise 2: Real-Time Editing

**In Copilot CLI:**
```
> Read outputs/visual-test.md and add a new section called "Updates"
> with the text "This was added in a second step"
```

**In VS Code:**
- Watch the file update in real-time!

---

## Exercise 3: Side-by-Side Workflow

Here's a realistic PM workflow:

**Step 1:** Ask Copilot to process something
```
> Read company-context/taskflow-personas.md
> Create a quick reference card for each persona with:
> - Name and role
> - Top 3 needs
> - Must-have features
> Save it to outputs/persona-cheatsheet.md
```

**Step 2:** Review in VS Code
- Open `outputs/persona-cheatsheet.md`
- Read through the content
- Identify any changes you want

**Step 3:** Iterate with Copilot
```
> The persona cheatsheet looks good but add a "Quotes" section
> for each persona with their most memorable quote
```

**Step 4:** Review again in VS Code
- See the updates
- Make any manual edits if needed

---

## Pro Tips

### 1. Use Split View

In VS Code, split your editor:
- Source file on the left
- Output file on the right
- Watch transformations happen

### 2. Markdown Preview

For `.md` files, use VS Code's Markdown Preview:
- `Cmd+Shift+V` (Mac) or `Ctrl+Shift+V` (Windows)
- See formatted output as you work

### 3. File Watching

If files aren't updating:
- Check VS Code's auto-refresh setting
- Try clicking the folder in explorer to refresh

---

## Alternative Editors

While we recommend VS Code, you can use any editor:

| Editor | Best For |
|--------|----------|
| **VS Code** | Most versatile, great extensions |
| **Cursor** | AI-native, Copilot integration |
| **Obsidian** | Markdown-focused, great for notes |
| **Sublime Text** | Lightweight, fast |

The key is having a visual view alongside your terminal.

---

## Checkpoint ✅

Before moving on, make sure you can:
- [ ] Open VS Code with the course folder
- [ ] See files update when Copilot creates them
- [ ] Work in a side-by-side workflow

---

## Next Steps

In **Module 1.3: First Tasks**, you'll put these skills to use processing meeting notes, analyzing research, and transforming documents.

**Tell Copilot:**
```
Let's start Module 1.3 - First Tasks
```

---

**Nice work setting up your visual workspace! 👀**
