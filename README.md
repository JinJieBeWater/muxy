<p align="center">
  <img src="Muxy/Resources/Assets.xcassets/AppIcon.appiconset/icon_128@2x.png" alt="Muxy" width="128" height="128">
</p>

<h1 align="center">Muxy</h1>

<p align="center">Lightweight and Memory efficient terminal for Mac built with SwiftUI and <a href="https://github.com/ghostty-org/ghostty">libghostty</a>.</p>
<p align="center"><p align="center"><a href="#install">Mac</a> | <a href="https://apps.apple.com/de/app/muxy/id6762464046?l=en-GB">iOS</a> | <a href="https://play.google.com/store/apps/details?id=com.muxy.app">Android</a> | <a href="https://discord.gg/4eMXAmJQ2n">Discord</a></p>

<div align="center">
  <img src="https://img.shields.io/github/downloads/muxy-app/muxy/total" />
  <img src="https://img.shields.io/github/v/release/muxy-app/muxy" />
  <img src="https://img.shields.io/github/license/muxy-app/muxy" />
  <img src="https://img.shields.io/github/commit-activity/m/muxy-app/muxy" />
</div>

## Screenshots

<img width="3004" alt="image" src="https://github.com/user-attachments/assets/721c6b4a-bd9c-4e4e-ade0-cd2597399801" />

## Features

- **Project-based workflow** — Organize terminals by project, grouped into collapsible project groups, with persistent workspace state
- **Vertical tabs** — Sidebar tab strip with drag-and-drop reordering, pinning, renaming, and middle-click close
- **Split panes** — Horizontal and vertical splits with keyboard navigation, resizable dividers, and pane maximize
- **Built-in VCS** — Git status, diff (unified and split), commit history, branch picker, and PR creation/listing via `gh`
- **Git worktrees** — Create, switch, and manage worktrees from the sidebar with per-pane branch tracking
- **Diff viewer** — Standalone unified/split diff tab with per-file navigation and inline comments
- **File tree** — Built-in project file browser with file operations and clipboard
- **Find in files** — Project-wide text search with match preview
- **Quick open & command palette** — Fuzzy-find files, projects, worktrees, commands, and history from a single omnibox
- **Text editor** — Native lightweight editor with syntax highlighting for most languages, search, and edit history
- **Markdown & HTML preview** — Render Markdown (with Mermaid diagrams) and HTML files inline, in code, preview, or split view
- **Image viewer** — View PNG, JPG, GIF, and WEBP with zoom, pan, fit-to-window, and actual-size controls
- **AI usage tracking** — Live token/cost usage panels for Claude Code, Codex, Cursor, Copilot, Amp, Factory, Droid, Kimi, MiniMax, OpenCode, Pi, and Z.ai
- **Extensions** — Run custom JavaScript extensions with their own tabs, commands, settings, console, and a scoped permission system
- **IDE integration** — Open files and folders in your preferred IDE directly from Muxy
- **Mobile companion apps** — Pair iOS and Android devices to control your Mac terminals remotely
- **Rich input panel** — Compose multi-line input with image attachments and drafts before sending to the terminal
- **Voice input** — Dictate into the input panel with on-device speech recognition
- **Notifications** — In-app notification center and native macOS notifications, with socket-based hooks (e.g. opencode plugin)
- **490+ themes** — Browse and search Ghostty themes with a built-in theme picker
- **Customizable shortcuts** — 60+ configurable keyboard shortcuts with conflict detection
- **Workspace & session persistence** — Tabs, splits, focus, and terminal sessions are saved and restored per project
- **In-terminal search** — Find text in terminal output with match navigation
- **Navigation history** — Back/forward navigation across tabs and projects
- **Drag and drop** — Reorder tabs and projects, drag tabs between panes to create splits, drop file paths into the terminal
- **Project icons** — Custom logos and color picker per project
- **Auto-updates** — Built-in update checking via Sparkle

## Requirements

- macOS 14+
- Swift 6.0+
- `gh` installed (optional for PR management)

## Install

### Homebrew

```bash
brew tap muxy-app/tap
brew install --cask muxy
```

### Manual

Download the latest release from the [releases page](https://github.com/muxy-app/muxy/releases)

### iOS

[Instructions](https://github.com/muxy-app/mobile)

### Android

[Instructions](https://github.com/muxy-app/mobile)

## Local Development

```bash
scripts/setup.sh          # downloads GhosttyKit.xcframework
swift build               # debug build
swift run Muxy             # run
```

## License

[MIT](LICENSE)
