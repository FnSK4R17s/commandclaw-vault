<p align="center">
  <img src="logo.png" alt="CommandClaw Vault" width="240">
</p>

<h1 align="center">CommandClaw Vault</h1>

<p align="center">
  <strong>Template vault for Command Claw agents.</strong><br>
  <sub>Clone this repo to create a new agent. Open in Obsidian. Install skills. Go.</sub>
</p>

---

> [!WARNING]
> **🚧 Beta Software** — This project is under active development. Workflows and commands may be incomplete or broken. Your feedback helps make this better!
>
> 💬 **Have feedback or found a bug?**  Reach out at [**@_Shikh4r_** on X](https://x.com/_Shikh4r_)

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
