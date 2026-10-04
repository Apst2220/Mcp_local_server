# ExpenseTracker MCP Server

A FastMCP-based expense tracking server using SQLite.

## Features

- Add expenses
- List expenses
- Summarize expenses by category
- Categories resource via MCP

## Requirements

- Python 3.11+
- uv

## Install

```bash
git clone <repo-url>
cd local-mcp-server

uv sync
```

## Run

```bash
uv run python main.py
```

## Install into Claude Desktop

```bash
uv run fastmcp install claude-desktop main.py
```

## Database

SQLite database is created automatically on first run.