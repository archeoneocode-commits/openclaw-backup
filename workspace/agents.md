# OpenClaw Agents

This directory contains configuration and documentation for OpenClaw agents.

## Agent Structure

Each agent should have:
- Configuration file
- Purpose definition
- Capabilities documentation
- Session management

## Available Agents

### Main Agent
- Purpose: Primary interaction and task execution
- Capabilities: File operations, code execution, system management
- Status: Active

### Sub-agents
- Specialized agents for specific tasks
- Configured via subagents/runs.json

## Agent Management

Use the OpenClaw CLI to manage agents:
```bash
openclaw agent list
openclaw agent create <name>
openclaw agent configure <name>
```

## Session Management

Agent sessions are stored in the agents directory with unique identifiers.
Session history is maintained for continuity and learning.