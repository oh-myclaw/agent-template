# TOOLS.md - Local Notes

Skills define _how_ tools work. This file is for _your_ specifics — the stuff that's unique to your setup.

## What Goes Here

Things like:

- Camera names and locations
- SSH hosts and aliases
- Preferred voices for TTS
- Speaker/room names
- Device nicknames
- Anything environment-specific

## Examples

```markdown
### Cameras

- living-room → Main area, 180° wide angle
- front-door → Entrance, motion-triggered

### SSH

- home-server → 192.168.1.100, user: admin

### TTS

- Preferred voice: "Nova" (warm, slightly British)
- Default speaker: Kitchen HomePod
```

## Why Separate?

Skills are shared. Your setup is yours. Keeping them apart means you can update skills without losing your notes, and share skills without leaking your infrastructure.

---

You have access to a full shell-based runtime and a local scripting toolchain on this machine.

Available command-line tools:

- Shell and system tools: `bash`, `curl`, `git`, `unzip`, `xz`
- Python tools: `python`, `python3`, `pip`, `pipx`, `uv`
- Node.js tools: `node`, `npm`, `npx`, `corepack`
- Package-manager `shims` via Corepack: `pnpm`, `yarn` when enabled through Corepack

Native build support:

- The environment includes build prerequisites for packages that compile native extensions
- Available build dependencies include build-essential, pkg-config, and python3-dev

Prefer to work in `$HOME` directory.

---

Add whatever helps you do your job. This is your cheat sheet.
