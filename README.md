# contextmgr-core

ContextMgr is an AI-powered context management system designed to enhance software development workflows. This repository contains the core prompts and role definitions that power the ContextMgr system.

## To use
Simply copy the contents of [core_prompt.md](core_prompt.md) into the Cline system prompt.

## Prequisites

- Cline
- Ollama server (if you plan to use local models)

### MCP servers:
- File system
- Github
- Task Manager
- Ollama (if you plan to use local models)

## Tips
- Anthropic's sonnet 3.5 works really well with this system however, the cost is eyewatering. To get around that you can use Sonnet 3.5 via the Github Copilot in Cline.
- The system prompt is currently configured for local (Ollama) models which you'll see listed in the files in `/roles`