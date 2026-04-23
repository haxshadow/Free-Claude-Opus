# Claude Code (Enhanced Agentic Tool)

![Node.js](https://img.shields.io/badge/Node.js-18%2B-brightgreen?style=flat-square) [![npm]](https://www.npmjs.com/package/@anthropic-ai/claude-code)

[npm]: https://img.shields.io/npm/v/@anthropic-ai/claude-code.svg?style=flat-square

Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows — all through natural language commands.

---

## ⚡ Claude Opus 4.6 Setup (PC/Windows)

To configure Claude Code with the **Opus 4.6** model via the agent router, execute the following commands in your terminal:

```powershell
# Install Claude Code globally
npm install -g @anthropic-ai/claude-code

# Set Environment Variables for Custom Routing
setx ANTHROPIC_BASE_URL "https://agentrouter.org/"
setx ANTHROPIC_AUTH_TOKEN "sk-KUByfxxxxxxxxxxxxxxxxxxxxxxx"
setx ANTHROPIC_MODEL "claude-opus-4-6"
setx CLAUDE_CODE_USE_AUTH_TOKEN "true"

# Launch Claude
claude
