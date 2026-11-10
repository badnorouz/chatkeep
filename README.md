<p align="center"><img src="assets/icon-512.png" width="110" alt="Chatkeep"></p>

<h1 align="center">Chatkeep</h1>
<p align="center"><b>Back up, browse and search every Claude conversation. Free.</b></p>

<p align="center">
  <a href="https://badnorouz.github.io/chatkeep/"><b>Website</b></a> ·
  <a href="https://github.com/badnorouz/chatkeep/releases/latest"><b>Download</b></a> ·
  <a href="PRIVACY.md">Privacy</a> ·
  <a href="LICENSE.txt">License</a>
</p>

Chatkeep is a **free** desktop app that keeps your **Claude Code**, **Cowork** and **claude.ai** chats safe on your own computer — and lets you search every word.

- **Search inside every conversation**, with highlighted matches (works in Persian and Arabic too)
- **One-click backup** of Claude Code and Cowork chats and their files; nothing is ever deleted from your backup
- **Import claude.ai Export Data** — even the manifest with download links; duplicates are skipped
- **Every file Claude made** in one place, with preview, download and export to Markdown / HTML / JSON
- **Transfer to another AI — automatically** — your chats appear as real chats in Codex CLI, OpenCode and Gemini CLI, and Antigravity, ChatGPT or any AI can read them too (see below)
- **Private by design** — no account, no cloud, no tracking, works offline
- Dark and light themes

## Transfer: switching to another AI tool — automatically

Pick the tools you use and click once. Chatkeep finds them on your computer and loads your history into them.

| Tool | What happens |
|---|---|
| **OpenCode** | Your Claude Code chats are loaded as **real chats** (using OpenCode's own `import`) and appear in its session list |
| **Codex CLI** | Your Claude Code chats are written as **real Codex sessions** and appear in its thread list |
| **Gemini CLI** | Your Claude Code chats appear as **real sessions** of the matching project folder |
| **Antigravity** | Reads a note that points to all your history (it keeps its own chats in a private format) |
| ChatGPT · Cursor · any AI | A package you prepare by hand: numbered Markdown parts and a starter prompt, or `AGENTS.md` + transcripts |

On top of that, everything — every project's digest, all chats (including claude.ai) and the files Claude created — is saved in one folder, `Chatkeep-Transfer`, and each selected tool gets a small, clearly marked note in its global instructions file pointing to it. Your own text in those files is never changed, a one-time backup is kept, re-running updates instead of duplicating, and **Remove** undoes it. Passwords, API keys and tokens are hidden automatically.

## Download (v1.3.0)

| Platform | File | Notes |
|---|---|---|
| macOS (Apple Silicon, 11+) | [`Chatkeep-1.3.0-macos-arm64.dmg`](https://github.com/badnorouz/chatkeep/releases/download/v1.3.0/Chatkeep-1.3.0-macos-arm64.dmg) | First launch: if macOS can't verify the app, open **System Settings → Privacy & Security → Open Anyway** (or run `xattr -cr /Applications/Chatkeep.app`) |
| Windows 10/11 (64-bit) | [`Chatkeep-1.3.0-windows-x64-Setup.exe`](https://github.com/badnorouz/chatkeep/releases/download/v1.3.0/Chatkeep-1.3.0-windows-x64-Setup.exe) | If SmartScreen warns: **More info → Run anyway** |
| Linux (x86_64) | [`Chatkeep-1.3.0-linux-x86_64.tar.gz`](https://github.com/badnorouz/chatkeep/releases/download/v1.3.0/Chatkeep-1.3.0-linux-x86_64.tar.gz) | Extract, then run `./install.sh` |

SHA-256 checksums are attached to the release as `SHA256SUMS.txt`. The apps are new and not yet code-signed, which is why macOS and Windows show a first-launch warning.

## Privacy
Your chats never leave your computer. Chatkeep has no servers and no analytics. The only network access is downloading the files listed in your own claude.ai export e-mail, when you ask it to. See [PRIVACY.md](PRIVACY.md).

---
Chatkeep is an independent app and is not affiliated with, endorsed by or sponsored by Anthropic. "Claude" is a trademark of Anthropic, PBC.
