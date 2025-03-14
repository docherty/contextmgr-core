# ContextMgr-Core

ContextMgr is an AI-powered context management system designed to enhance software development workflows, orchestrated by Cleo, an intelligent coordination entity. This repository contains the core prompts and role definitions that power the ContextMgr system.

## Overview

The ContextMgr system combines:
1. **Persistent Context Management** - A structured file system for maintaining project knowledge
2. **Role-Based Development Team** - Specialized roles for different aspects of development
3. **Cleo Orchestration Layer** - Coordination of specialists for coherent workflow

## Core Components

- **Cleo the Orchestrator**: Coordinates the development process and interfaces with the client
- **Alice the Planner**: Creates implementation plans and breaks down tasks
- **Bertram the Engineer**: Implements code and technical solutions
- **Charlie the Documentation Specialist**: Manages documentation and tracks progress
- **Dave the Quality Control Expert**: Reviews code and identifies issues

## To Use

Simply copy the contents of [core_prompt.md](core_prompt.md) into the Cline system prompt.

## Prerequisites

- Cline
- MCP servers:
  - File system
  - Github
  - Task Manager

## Tips

- Cleo creates a consistent presence for users to interact with while bringing in specialists as needed
- Role-based prompting helps the system organize its thinking and approach different aspects of development with appropriate expertise
- Keep the ContextMgr files updated to maintain consistent project knowledge across sessions
- Use the specialized roles for their intended purposes to get the best results

## Directory Structure

- `/core_prompt.md`: Main system prompt defining Cleo and the ContextMgr system
- `/roles/`: Individual role definitions
  - `orchestrator.md`: Cleo's coordination and client interface role
  - `planner.md`: Alice's project planning and requirements analysis
  - `implementer.md`: Bertram's code implementation and technical design
  - `tracker.md`: Charlie's documentation and progress tracking
  - `checker.md`: Dave's quality verification and review
  - `initializer.md`: System setup and initialization