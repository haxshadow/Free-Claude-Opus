# Claude Code (Custom Setup)

![Node.js Version](https://img.shields.io/badge/Node.js-18%2B-brightgreen?style=flat-square)
[![npm version](https://img.shields.io/npm/v/@anthropic-ai/claude-code.svg?style=flat-square)](https://www.npmjs.com/package/@anthropic-ai/claude-code)

Claude Code is an agentic coding tool that runs directly in your terminal. It understands your codebase and can handle routine tasks, explain complex code, and manage git workflows via natural language commands.

---

## 🛠️ Prerequisites

Ensure you have **Node.js (v18 or higher)** installed on your system.

Install Claude Code globally via NPM:
```bash
npm install -g @anthropic-ai/claude-code
```
*(Note: Use `sudo` on Linux/macOS if you encounter permission errors.)*

---

## ⚡ Configuration & Setup

Select the instructions for your operating system to configure the environment variables correctly.

### 🪟 Windows (Command Prompt / PowerShell)
Run the following commands to set the environment variables persistently:

```powershell
setx ANTHROPIC_BASE_URL "https://agentrouter.org/"
setx ANTHROPIC_AUTH_TOKEN "sk-KUByfxxxxxxxxxxxxxxxxxxxxxxx"
setx ANTHROPIC_MODEL "claude-opus-4-6"
setx CLAUDE_CODE_USE_AUTH_TOKEN "true"
```
*Note: You may need to restart your terminal or computer for the changes to take effect.*

### 🐧 Linux (Bash / Zsh)
To make the variables persistent, append them to your shell configuration file (`.bashrc` or `.zshrc`):

```bash
# For Zsh (Default on Kali/Ubuntu):
echo 'export ANTHROPIC_BASE_URL "https://agentrouter.org/"' >> ~/.zshrc
echo 'export ANTHROPIC_AUTH_TOKEN="sk-KUByfxxxxxxxxxxxxxxxxxxxxxxx"' >> ~/.zshrc
echo 'export ANTHROPIC_MODEL="claude-opus-4-6"' >> ~/.zshrc
echo 'export CLAUDE_CODE_USE_AUTH_TOKEN="true"' >> ~/.zshrc
source ~/.zshrc

# For Bash:
# Replace ~/.zshrc with ~/.bashrc in the commands above and run 'source ~/.bashrc'.
```

### 🍎 macOS (Zsh)
Run these commands in your terminal to configure your Zsh environment:

```bash
echo 'export ANTHROPIC_BASE_URL "https://agentrouter.org/"' >> ~/.zshrc
echo 'export ANTHROPIC_AUTH_TOKEN="sk-KUByfxxxxxxxxxxxxxxxxxxxxxxx"' >> ~/.zshrc
echo 'export ANTHROPIC_MODEL="claude-opus-4-6"' >> ~/.zshrc
echo 'export CLAUDE_CODE_USE_AUTH_TOKEN="true"' >> ~/.zshrc
source ~/.zshrc
```

---

## 🚀 Launching Claude Code

Once configured, simply run the following command in any project directory to start:

```bash
claude
```
