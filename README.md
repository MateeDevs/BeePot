<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/assets/banner-dark.svg">
  <img src=".github/assets/banner-light.svg" width="100%" alt="BeePot — the agent-first git client, for beginners and pros alike">
</picture>

<p align="center">
  <a href="https://github.com/MateeDevs/BeePot/releases/latest/download/BeePot.zip"><img src="https://img.shields.io/badge/dynamic/xml?url=https%3A%2F%2Fgithub.com%2FMateeDevs%2FBeePot%2Freleases%2Flatest%2Fdownload%2Fappcast.xml&query=%2F%2F%2A%5Blocal-name%28%29%3D%27shortVersionString%27%5D&label=Download%20for%20Mac&prefix=v&style=for-the-badge&logo=apple&logoColor=white&color=E08A10&labelColor=1F1606" height="40" alt="Download BeePot for Mac"></a>
</p>

<p align="center">
  <a href="https://github.com/MateeDevs/BeePot/releases"><img src="https://img.shields.io/github/release-date/MateeDevs/BeePot?label=released&color=F9B83A&labelColor=2B2112" alt="Release date"></a>
  <img src="https://img.shields.io/badge/macOS-26%2B-F9B83A?logo=apple&logoColor=white&labelColor=2B2112" alt="macOS 26 or later">
  <img src="https://img.shields.io/badge/Apple%20silicon%20%26%20Intel-universal-F9B83A?labelColor=2B2112" alt="Apple silicon and Intel">
  <img src="https://img.shields.io/badge/updates-automatic%20%26%20signed-F9B83A?labelColor=2B2112" alt="Automatic, signed updates">
</p>

<!-- Screenshot: add .github/assets/screenshot.png (the main window, ~2400 px wide) and uncomment.
<p align="center">
  <img src=".github/assets/screenshot.png" width="100%" alt="BeePot showing projects in the sidebar and the changes an agent made">
</p>
-->

Claude Code, Codex, Cursor and friends change files in many projects at once. **BeePot** shows you
what they changed, which project needs you right now, and keeps versions of your work so nothing
gets lost. Projects are sorted by the latest activity, so the one waiting for you is always on top.

## Two ways to work

|  | 🐝 **Bee** | 🧑‍🌾 **Beekeeper** |
| --- | --- | --- |
| **For** | Designers, writers, PMs — anyone building with an AI agent | Developers who know git |
| **Words** | Plain words, no git jargon | The full git vocabulary |
| **Saving** | Save points and one **Sync** button that shows what goes online first | Stage, commit, push, pull, branches, stashes |

Pick one in the first-run setup and switch any time in Settings.

## What it does

<table>
  <tr>
    <td width="50%" valign="top">
      <img src=".github/assets/feature-projects.svg" width="44" alt=""><br>
      <b>All your projects on one screen</b><br>
      Sorted by what needs you: an agent waiting for input, work ready to upload, conflicts, reviews.
    </td>
    <td width="50%" valign="top">
      <img src=".github/assets/feature-agents.svg" width="44" alt=""><br>
      <b>Knows your coding agents</b><br>
      Claude Code, Codex, Cursor, Gemini CLI, Pi, OpenCode, Aider and more: which one works where, and whether it’s busy, done or needs you.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <img src=".github/assets/feature-changes.svg" width="44" alt=""><br>
      <b>See what changed</b><br>
      Every file and every line, with a short summary in plain words.
    </td>
    <td valign="top">
      <img src=".github/assets/feature-previews.svg" width="44" alt=""><br>
      <b>Previews, not just diffs</b><br>
      Markdown, images, web pages and SwiftUI / Jetpack Compose screens, before and after the change.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <img src=".github/assets/feature-safety.svg" width="44" alt=""><br>
      <b>A safety net</b><br>
      Automatic backups every 15 minutes, when an agent starts and before every Sync. Go back any time.
    </td>
    <td valign="top">
      <img src=".github/assets/feature-ai.svg" width="44" alt=""><br>
      <b>AI commit messages</b><br>
      Written by the agent you already have, with your own account. No extra API key.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <img src=".github/assets/feature-discover.svg" width="44" alt=""><br>
      <b>Finds your projects</b><br>
      Reads your agents’ history on this Mac and offers the projects they worked in.
    </td>
    <td valign="top">
      <img src=".github/assets/feature-reviews.svg" width="44" alt=""><br>
      <b>Reviews</b><br>
      GitHub pull requests sent to you, right next to your own work.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <img src=".github/assets/feature-notifications.svg" width="44" alt=""><br>
      <b>Notifications</b><br>
      When an agent needs you or finishes, when a review arrives, when a new version is ready.
    </td>
    <td valign="top">
      <img src=".github/assets/feature-fast.svg" width="44" alt=""><br>
      <b>Keyboard first</b><br>
      <kbd>⌘</kbd> <kbd>K</kbd> to jump anywhere, <kbd>⇧</kbd> <kbd>⇧</kbd> to search a project.
    </td>
  </tr>
</table>

## Install

1. Download **[BeePot.zip](https://github.com/MateeDevs/BeePot/releases/latest/download/BeePot.zip)**.
2. Unzip it and move **BeePot** to your **Applications** folder.
3. Open BeePot. A short setup walks you through how you want to work, developer tools, GitHub
   sign-in and your first project.

> [!IMPORTANT]
> The first time, macOS may say it can’t check BeePot for malicious software. Open
> **System Settings → Privacy & Security**, scroll down and click **Open Anyway** next to BeePot.
> You only need to do this once.

## Updates

BeePot updates itself. It downloads new versions in the background and installs them when you quit
it, or right away from the sidebar with **Restart**. You can also choose
**BeePot → Check for Updates…**, and **Help → What’s New in BeePot…** shows what changed.

> [!NOTE]
> Every update is signed, and BeePot installs only updates signed by us.

All versions and their notes: **[Releases](https://github.com/MateeDevs/BeePot/releases)**.

## Privacy

- 🏠 BeePot runs on your Mac. No analytics, no tracking, no BeePot account.
- 🐙 It talks to **GitHub** only for what you ask it to (sign-in, cloning, syncing, reviews) and to
  check this page for updates.
- 🤖 AI features run through the coding agent installed on your Mac (Claude Code, Codex or Cursor),
  under your own account with that provider.
- 🔍 Found projects are read from your agents’ session history on this Mac. Nothing is uploaded.

## FAQ

<details>
<summary><b>Does BeePot change my files?</b></summary>
<br>
Only when you ask it to: committing, syncing, restoring a backup. Previews render from BeePot’s own
copy of the project, so nothing a preview build writes lands in your folder.
</details>

<details>
<summary><b>Do I need to know git?</b></summary>
<br>
No. In <b>Bee</b> mode BeePot speaks plain words: save points, Sync, backups. Switch to
<b>Beekeeper</b> when you want every git control.
</details>

<details>
<summary><b>Which coding agents does it work with?</b></summary>
<br>
BeePot sees Claude Code, Codex, Pi, Cursor Agent, Gemini CLI, OpenCode, Aider, Amp, GitHub Copilot,
Goose and Zed. AI commit messages and summaries use Claude Code, Codex or Cursor.
</details>

<details>
<summary><b>Why does macOS warn me the first time?</b></summary>
<br>
BeePot isn’t notarized by Apple yet. Click <b>Open Anyway</b> once (see <a href="#install">Install</a>);
updates after that install without asking.
</details>

<details>
<summary><b>How do I uninstall it?</b></summary>
<br>
Quit BeePot and move it from <b>Applications</b> to the Trash. Your projects stay exactly where they
are. BeePot’s own settings and project list live in <code>~/Library/Application Support/BeePot</code>.
</details>

## Feedback

BeePot is young and moves fast. Found a bug or missing something? Write to us at
**[info@matee.cz](mailto:info@matee.cz)**.

<br>

<p align="center">
  <img src=".github/assets/icon.png" width="48" alt=""><br>
  <sub>Made with 🍯 by <a href="https://www.matee.cz">Matee</a></sub>
</p>
