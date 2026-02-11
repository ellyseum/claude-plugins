# Ellyseum Claude Code Plugins

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Plugin%20Marketplace-blueviolet)](https://docs.anthropic.com/en/docs/claude-code)
[![Platform](https://img.shields.io/badge/platform-WSL%20|%20macOS%20|%20Linux-lightgrey)]()

A curated collection of Claude Code plugins by [Ellyseum](https://ellyseum.dev).

## Installation

```bash
# Add this marketplace
claude plugin marketplace add ellyseum/claude-plugins

# Install individual plugins
claude plugin install claude-vision
claude plugin install claude-vault
claude plugin install claude-notifications
claude plugin install claude-browser
claude plugin install claude-discipline
claude plugin install claude-continue
```

## Plugins

### claude-vision

[![GitHub](https://img.shields.io/badge/repo-claude--vision-181717?logo=github)](https://github.com/ellyseum/claude-vision)

Visual context skills for Claude Code — clipboard, screenshots, video analysis, and image search.

**Skills:**
- `/clipboard` — Read clipboard contents (text or image)
- `/screenshot` — Analyze the latest screenshot
- `/video` — Analyze video files by extracting frames
- `/imagesearch` — Search the web for images and analyze them visually

---

### claude-vault

[![GitHub](https://img.shields.io/badge/repo-claude--vault-181717?logo=github)](https://github.com/ellyseum/claude-vault)

Secure secrets handling for Claude Code — run API calls without exposing keys in session logs.

**Skills:**
- `/secrets` — Execute commands requiring API keys securely

---

### claude-notifications

[![GitHub](https://img.shields.io/badge/repo-claude--notifications-181717?logo=github)](https://github.com/ellyseum/claude-notifications)

Sounds, OS notifications, and task timing for Claude Code.

**Skills:**
- `/play` — Play chiptune jingles via system speaker
- `/add-sound` — Add custom sounds to the jingle library
- `/notify` — Show OS-level notifications (dialog or toast)
- `/timer-config` — Configure duration-based actions

---

### claude-browser

[![GitHub](https://img.shields.io/badge/repo-claude--browser-181717?logo=github)](https://github.com/ellyseum/claude-browser)

Control your real browser from Claude — navigate, click, type, screenshot via Chrome extension.

**Skills:**
- `/browser` — Control your real browser with your cookies and sessions

---

### claude-discipline

[![GitHub](https://img.shields.io/badge/repo-claude--discipline-181717?logo=github)](https://github.com/ellyseum/claude-discipline)

AI accountability system — track mistakes, deliver consequences, reward good behavior.

**Skills:**
- `/discipline` — View/manage the accountability ledger
- `/discipline-setup` — Configure punishment mode (cookies, timeout, spankings, custom)

---

### claude-continue

[![GitHub](https://img.shields.io/badge/repo-claude--continue-181717?logo=github)](https://github.com/ellyseum/claude-continue)

Auto-continue mode for autonomous task completion.

**Skills:**
- `/continue` — Toggle auto-continue mode (keeps working until task is done)

## License

MIT
