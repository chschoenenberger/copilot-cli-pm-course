# Module 0.1: Installation

## Install GitHub Copilot CLI

This module walks you through installing Copilot CLI on your system.

---

## Prerequisites

Before installing Copilot CLI, ensure you have:

1. **GitHub Account** with an active Copilot subscription
2. **PowerShell v6+** (Windows) or Terminal (macOS/Linux)
3. **Git** installed (for cloning the course)

### Check Your Prerequisites

```bash
# Check Git
git --version

# Check PowerShell version (Windows only, should be 6+)
$PSVersionTable.PSVersion
```

---

## Installation Methods

### Windows (WinGet) - Recommended

```bash
# Install via WinGet
winget install GitHub.Copilot

# Verify installation
copilot --version
```

### macOS / Linux (Homebrew)

```bash
# Install via Homebrew
brew install copilot-cli

# Verify installation
copilot --version
```

### All Platforms (npm)

```bash
# Install via npm
npm install -g @github/copilot

# Verify installation
copilot --version
```

### macOS / Linux (Install Script)

```bash
# Install via script
curl -fsSL https://gh.io/copilot-install | bash

# Verify installation
copilot --version
```

---

## Authentication

After installation, launch Copilot CLI and authenticate:

```bash
# Start Copilot CLI
copilot

# On first launch, you'll be prompted to log in
# Use the /login slash command and follow the on-screen instructions
/login
```

This will open a browser window where you can authenticate with your GitHub account.

---

## Test Your Installation

Let's make sure everything works:

```bash
# Start Copilot CLI
copilot

# You should see a welcome banner and prompt
# Try a simple question:
> What is 2 + 2?

# Exit with 'exit' or Ctrl+C
```

---

## Troubleshooting

### "copilot: command not found"

**Windows:** Make sure WinGet installed correctly, or try the npm method.

**macOS/Linux:** Ensure Homebrew bin is in your PATH:
```bash
export PATH="/opt/homebrew/bin:$PATH"
```

### Authentication Errors

Try logging in again:
```bash
copilot
/login
```

### Permission Denied (npm install)

You may need to fix npm permissions or use sudo:
```bash
sudo npm install -g @github/copilot
```

---

## Recommended Setup

### Editor Integration

For the best experience, use VS Code alongside Copilot CLI:
- Open your project folder in VS Code
- Run Copilot CLI in VS Code's integrated terminal
- See file changes in real-time

---

## Next Steps

Once installed and authenticated, proceed to **Module 0.2: Start & Clone** to get the course materials and start learning!

---

## Quick Reference

| Command | Description |
|---------|-------------|
| `copilot` | Start Copilot CLI |
| `copilot --version` | Check version |
| `/login` | Authenticate (inside Copilot CLI) |
| `/model` | Change AI model |
| `exit` | Exit Copilot CLI |
