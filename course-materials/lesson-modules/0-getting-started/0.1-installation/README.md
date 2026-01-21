# Module 0.1: Installation

## Install GitHub Copilot CLI

This module walks you through installing Copilot CLI on your system.

---

## Prerequisites

Before installing Copilot CLI, ensure you have:

1. **GitHub Account** with Copilot subscription
2. **Node.js 18+** installed
3. **Git** installed

### Check Your Prerequisites

```bash
# Check Node.js version (should be 18+)
node --version

# Check Git
git --version
```

---

## Installation Methods

### Method 1: npm (Recommended)

```bash
# Install globally
npm install -g @githubnext/github-copilot-cli

# Verify installation
copilot --version
```

### Method 2: Homebrew (macOS)

```bash
# Install via Homebrew
brew install gh-copilot

# Verify installation
copilot --version
```

### Method 3: Manual Download

Visit [GitHub Copilot CLI releases](https://github.com/githubnext/github-copilot-cli/releases) and download for your platform.

---

## Authentication

After installation, authenticate with your GitHub account:

```bash
# Start authentication
copilot auth login

# Follow the prompts to:
# 1. Open browser
# 2. Enter the code shown
# 3. Authorize the application
```

### Verify Authentication

```bash
# Check auth status
copilot auth status
```

You should see confirmation that you're logged in.

---

## Test Your Installation

Let's make sure everything works:

```bash
# Start Copilot CLI
copilot

# You should see a welcome message and prompt
# Try a simple command:
> What is 2 + 2?

# Exit with 'exit' or Ctrl+C
```

---

## Troubleshooting

### "copilot: command not found"

**Solution:** Ensure npm global bin is in your PATH:

```bash
# Find npm global bin location
npm config get prefix

# Add to PATH (add to your shell profile)
export PATH="$PATH:$(npm config get prefix)/bin"
```

### Authentication Errors

**Solution:** Clear and re-authenticate:

```bash
copilot auth logout
copilot auth login
```

### Permission Denied

**Solution:** You may need sudo on some systems:

```bash
sudo npm install -g @githubnext/github-copilot-cli
```

---

## Recommended Configuration

### Editor Integration

For the best experience, use VS Code with:
- GitHub Copilot extension
- Terminal integration

### Shell Aliases (Optional)

Add to your shell profile for convenience:

```bash
# Add to ~/.bashrc, ~/.zshrc, or PowerShell profile
alias cop="copilot"
```

---

## Next Steps

Once installed and authenticated, proceed to **Module 0.2: Start & Clone** to get the course materials and start learning!

---

## Quick Reference

| Command | Description |
|---------|-------------|
| `copilot` | Start Copilot CLI |
| `copilot --version` | Check version |
| `copilot auth login` | Authenticate |
| `copilot auth status` | Check auth status |
| `copilot auth logout` | Log out |
| `exit` | Exit Copilot CLI |
