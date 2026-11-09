---
type: decision
created: 2026-11-09
tags:
  - taskflow
  - decision
status: accepted
---

# TaskFlow MCP Implementation

Implemented the TaskFlow MCP vault connector in commit 46a8e6cd8f890a393b1e4b3e210ec4e3a301870c (`feat: implement TaskFlow MCP vault connector`). The commit adds `connector/server.py`, a Python MCP server named “TaskFlow Vault” with visible `ping` and `search_notes` tools, and a vault path resolved relative to the connector. It adds `.vscode/mcp.json` to configure the local `taskflow-vault` stdio server using the workspace virtual-environment Python interpreter and `connector/server.py`, plus a GitHub HTTP MCP endpoint configured for the `repos` toolset and read-only access. It adds `mcp>=2,<3` to `requirements.txt` and updates `.gitignore` to exclude `.venv/`, `__pycache__/`, `*.pyc`, `.env`, and `.pytest_cache/`.

Changed files:
- `.gitignore` (added)
- `.vscode/mcp.json` (added)
- `connector/server.py` (added)
- `requirements.txt` (added)

## Пов'язані нотатки

- [[Agent Harness Terms]]
- [[Note-Conventions]]
