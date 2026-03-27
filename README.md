<p align="center">
  <span style="font-size: 80px;">⚓🦞🏠</span>
</p>

<h1 align="center">CommandClaw Vault</h1>

<p align="center">
  <strong>Template vault for Command Claw agents.</strong><br>
  <sub>Clone this repo to create a new agent. Open in Obsidian. Install skills. Go.</sub>
</p>

---

## Quick Start

```bash
# Clone as your new agent vault
gh repo clone FnSK4R17s/commandclaw-vault my-agent
cd my-agent

# Install skills (select which ones to add)
npx skills add FnSK4R17s/commandclaw-skills

# Open in Obsidian — plugins are pre-configured
```

## What's Inside

| File | Purpose |
|------|---------|
| `AGENTS.md` | Workspace rules, session protocol, safety guidelines |
| `SOUL.md` | Agent personality, values, communication style |
| `IDENTITY.md` | Name, creature type, vibe, emoji (fill in on first run) |
| `USER.md` | Your human's context and preferences (fill in on first run) |
| `TOOLS.md` | Local environment notes — SSH hosts, devices, preferences |
| `HEARTBEAT.md` | Recurring checks and proactive tasks |
| `BOOTSTRAP.md` | First-run instructions (deleted after bootstrap) |
| `MEMORY.md` | Curated long-term memory |
| `memory/` | Daily session logs (`YYYY-MM-DD.md`) |

## Obsidian Plugins (pre-configured)

- **obsidian-git** — auto-commit every 5min, auto-push, pull on boot
- **templater** — folder templates for daily notes in `memory/`
- **metadata-menu** — structured frontmatter with fileClasses
- **linter** — YAML key sorting, auto `created`/`updated` timestamps

## Related Repos

| Repo | Purpose |
|------|---------|
| [commandclaw](https://github.com/FnSK4R17s/commandclaw) | Agent runtime, Telegram I/O, tracing |
| [commandclaw-skills](https://github.com/FnSK4R17s/commandclaw-skills) | Skills library — `npx skills add FnSK4R17s/commandclaw-skills` |
