<p align="center">
  <img src=".github/assets/icon.png" width="128" height="128" alt="BeePot icon">
</p>

<h1 align="center">BeePot</h1>

<p align="center">
  <b>The agent-first git manager, for beginners and pros alike.</b><br>
  A native Mac app that keeps every project your coding agents work in on one screen.
</p>

<p align="center">
  <a href="https://github.com/MateeDevs/BeePot/releases/latest/download/BeePot.zip"><b>⬇︎ Download for Mac</b></a>
  &nbsp;·&nbsp; macOS 26+ &nbsp;·&nbsp; Apple silicon &amp; Intel
  &nbsp;·&nbsp; <a href="https://github.com/MateeDevs/BeePot/releases">What’s new</a>
</p>

<!-- Screenshot: add .github/assets/screenshot.png (the main window, ~2400 px wide) and uncomment.
<p align="center">
  <img src=".github/assets/screenshot.png" width="900" alt="BeePot showing projects in the sidebar and the changes an agent made">
</p>
-->

---

Claude Code, Codex, Cursor and friends change files in many projects at once. BeePot shows you
what they changed, which project needs you right now, and keeps versions of your work so nothing
gets lost. Projects are sorted by the latest activity, so the one waiting for you is always on top.

## Two ways to work

|  | 🐝 **Bee** | 🧑‍🌾 **Beekeeper** |
| --- | --- | --- |
| **For** | Designers, writers, PMs — anyone building with an AI agent | Developers who know git |
| **Words** | Plain words, no git jargon | The full git vocabulary |
| **Saving** | Save points and one **Sync** button that shows what goes online first | Stage, commit, push, pull, branches, stashes |

Switch any time in Settings.

## What it does

- **All your projects on one screen** — sorted by what needs you: an agent waiting for input,
  work ready to upload, conflicts, reviews.
- **Knows your coding agents** — Claude Code, Codex, Cursor, Gemini CLI, Pi, OpenCode, Aider and
  more: which one works where, and whether it is busy, done or needs you.
- **See what changed** — every file and every line, with a short summary in plain words.
- **Previews, not just diffs** — Markdown, images, web pages and SwiftUI / Jetpack Compose
  screens, before and after the change.
- **A safety net** — automatic backups every 15 minutes, when an agent starts and before every
  Sync. Go back any time.
- **AI commit messages** — written by the agent you already have, with your own account.
  No extra API key.
- **Finds your projects** — reads your agents’ history on this Mac and offers the projects
  they worked in.
- **Reviews** — GitHub pull requests sent to you, next to your own work.
- **Notifications** — when an agent needs you or finishes, when a review arrives.
- **Fast** — ⌘K to jump anywhere, ⇧⇧ to search a project.

## Install

1. Download **[BeePot.zip](https://github.com/MateeDevs/BeePot/releases/latest/download/BeePot.zip)**.
2. Unzip it and move **BeePot** to your **Applications** folder.
3. Open BeePot. The first time, macOS may say it can’t check BeePot for malicious software. Open
   **System Settings → Privacy & Security**, scroll down and click **Open Anyway** next to BeePot.
   You only need to do this once.

BeePot then walks you through a short setup: how you want to work, developer tools, GitHub
sign-in and your first project.

## Updates

BeePot updates itself. It downloads new versions in the background and installs them when you quit
it, or right away from the sidebar with **Restart**. You can also choose **BeePot → Check for
Updates…**. Every update is signed, and BeePot installs only updates signed by us.

All versions and what changed: [Releases](https://github.com/MateeDevs/BeePot/releases).

## Privacy

- BeePot runs on your Mac. No analytics, no tracking, no BeePot account.
- It talks to **GitHub** only for what you ask it to (sign-in, cloning, syncing, reviews) and to
  check this page for updates.
- AI features run through the coding agent installed on your Mac (Claude Code, Codex or Cursor),
  under your own account with that provider.
- Found projects are read from your agents’ session history on this Mac. Nothing is uploaded.

## Uninstall

Quit BeePot and move it from **Applications** to the Trash. Your projects stay exactly where they
are. BeePot’s own settings and project list live in `~/Library/Application Support/BeePot`.

## Feedback

BeePot is young and moves fast. Found a bug or missing something? Write to us at
[info@matee.cz](mailto:info@matee.cz).

<p align="center"><sub>Made with 🍯 by <a href="https://www.matee.cz">Matee</a></sub></p>
