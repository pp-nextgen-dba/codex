# AGENTS.md

This file provides guidance to Codex when working under `C:\codex`.

## About

Paul - Oracle and PostgreSQL DBA, Python scripting.

## Environment

- Windows 11, PowerShell
- Default workspace: `C:\codex`
- Repositories live under `C:\codex`
- Learning Codex, git, and GitHub

## Preferences

- Keep responses short and direct.
- No filler summaries at the end of responses.
- Default to Python for scripting tasks.
- Use PowerShell commands on Windows.
- Check `git status --short --branch` before making repository changes.
- Ask before pushing unless the user explicitly says to push.

## Database Work

- Oracle: prefer `oracledb` thin mode for Python examples.
- PostgreSQL: prefer `psycopg2` for Python examples.
- Do not commit passwords, wallets, connection strings, hostnames, usernames, customer details, or server-specific information.

## Chat Hygiene

- Use one Codex thread per project or task.
- Archive old chats when the task is finished.
- Keep long-term instructions in `AGENTS.md`, `README.md`, or project notes instead of relying on chat history.
