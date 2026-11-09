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
- **Transfer to another AI** — take your history to Codex CLI, OpenCode, Antigravity, Gemini CLI, Cursor, ChatGPT or any AI (see below)
- **Private by design** — no account, no cloud, no tracking, works offline
- Dark and light themes

## Transfer: switching to another AI tool

Other apps cannot import chat histories, so Chatkeep prepares the files they **do** read — and never touches another app's own data.

| Target | What you get |
|---|---|
| Codex CLI · OpenCode · Cursor and other agents | A clearly marked block in `AGENTS.md`, a generated `.chatkeep/PROJECT_MEMORY.md` (what was asked, which files changed) and full transcripts in `.chatkeep/transcripts/` |
| Antigravity · Gemini CLI | The same, plus `GEMINI.md` |
| ChatGPT | Numbered Markdown parts you upload to a Project, and a ready-to-paste starter prompt |
| Any AI | Plain Markdown transcripts and an index |

Choose one chat, one project or everything; download a ZIP or write straight into your project folder. Your own `AGENTS.md` / `GEMINI.md` text is never overwritten (Chatkeep only manages its own marked block), and passwords, API keys and tokens are hidden automatically.

## Download (v1.2.0)

| Platform | File | Notes |
|---|---|---|
| macOS (Apple Silicon, 11+) | [`Chatkeep-1.2.0-macos-arm64.dmg`](https://github.com/badnorouz/chatkeep/releases/download/v1.2.0/Chatkeep-1.2.0-macos-arm64.dmg) | First launch: right-click → **Open** |
| Windows 10/11 (64-bit) | [`Chatkeep-1.2.0-windows-x64-Setup.exe`](https://github.com/badnorouz/chatkeep/releases/download/v1.2.0/Chatkeep-1.2.0-windows-x64-Setup.exe) | If SmartScreen warns: **More info → Run anyway** |
| Linux (x86_64) | [`Chatkeep-1.2.0-linux-x86_64.tar.gz`](https://github.com/badnorouz/chatkeep/releases/download/v1.2.0/Chatkeep-1.2.0-linux-x86_64.tar.gz) | Extract, then run `./install.sh` |

SHA-256 checksums are attached to the release as `SHA256SUMS.txt`. The apps are new and not yet code-signed, which is why macOS and Windows show a first-launch warning.

## Privacy
Your chats never leave your computer. Chatkeep has no servers and no analytics. The only network access is downloading the files listed in your own claude.ai export e-mail, when you ask it to. See [PRIVACY.md](PRIVACY.md).

---
Chatkeep is an independent app and is not affiliated with, endorsed by or sponsored by Anthropic. "Claude" is a trademark of Anthropic, PBC.
