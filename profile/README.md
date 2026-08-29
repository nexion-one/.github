<h1 align="center">
  <img src="https://nexion.one/images/nexion-icon.svg" width="80" alt="Nexion" /><br/>
  Nexion
</h1>

<p align="center">
  <strong>The AI-native workspace for macOS</strong><br/>
  Built for developers who live in the terminal.
</p>

<p align="center">
  <a href="https://nexion.one">Website</a> &middot;
  <a href="#open-source">Open Source</a> &middot;
  <a href="https://nexion.one/repository/plugins">Plugin Repository</a> &middot;
  <a href="https://github.com/nexion-one/Nexion/issues">Support</a>
</p>

---

## Open Source

Nexion is proprietary software. The components that run outside the application, on your own
hosts and inside your own toolchain, are published under the MIT License.

| Repository | License | Description |
|:-------|:---|:------------|
| [**remote-agent**](https://github.com/nexion-one/remote-agent) | MIT | The Go daemon Nexion installs on hosts you own, over SSH, so opening a remote project is not one round trip per file listing. No third-party dependencies, no network listener, and authentication is your own SSH. |
| [**protocol**](https://github.com/nexion-one/protocol) | MIT | The wire contract between the Mac app and the phone: capability negotiation, payloads recorded from a real session, and an index of all 76 verbs generated from the source. |
| [**agent-transcripts**](https://github.com/nexion-one/agent-transcripts) | MIT | A Swift package for reading what the coding agent CLIs leave on disk: Claude Code, Codex, opencode and Gemini transcripts, and Claude Code's token usage. |

---

## Plugins

Nexion ships with a growing ecosystem of official plugins.  
Each plugin is a self-contained `.nexionplugin` bundle: drop it into `~/.nexion/Plugins/` and it just works.

> Browse the full collection at [nexion.one/repository/plugins](https://nexion.one/repository/plugins)

### Development Tools

| Plugin | Description |
|:-------|:------------|
| [**Dependency Checker**](https://github.com/nexion-one/plugin-dep-check) | Check for outdated dependencies with monorepo support. Auto-detects npm, pnpm, yarn, bun, pip, cargo, go, gem, composer. Security audit included. |
| [**Docker Manager**](https://github.com/nexion-one/plugin-docker-manager) | Manage Docker containers from the toolbar. Start, stop, restart, follow logs, compose up/down. Live container dashboard with status colors and port mapping. |
| [**Git Flow**](https://github.com/nexion-one/plugin-git-flow) | Structured git-flow branching from the command palette. Create and finish feature, release, and hotfix branches with automatic merge, tagging, and cleanup. |
| [**Script Runner**](https://github.com/nexion-one/plugin-script-runner) | Auto-discover project scripts from `package.json`, `Makefile`, `Cargo.toml`, and `pyproject.toml`. Run them directly from the command palette. |
| [**Run File**](https://github.com/nexion-one/plugin-run-file) | Right-click any file to run it with the correct interpreter. Supports 15+ languages out of the box. |

### Project Management

| Plugin | Description |
|:-------|:------------|
| [**TODO Tracker**](https://github.com/nexion-one/plugin-todo-tracker) | Scan your codebase for `TODO`, `FIXME`, `HACK`, and `NOTE` comments. Results grouped by file in a sidebar panel. |
| [**Dotenv**](https://github.com/nexion-one/plugin-dotenv) | Validate `.env` files against `.env.example`, detect missing variables, diff environments, and bootstrap new `.env` from templates. |
| [**Project Info**](https://github.com/nexion-one/plugin-project-info) | Auto-detect the tech stack on project open. Identifies languages, frameworks, package managers, build systems, and Git remote info. |
| [**Snippets**](https://github.com/nexion-one/plugin-snippets) | Global code snippets manager. Language tagging with auto-detect, fuzzy search, usage tracking, grouped sidebar, and clipboard copy. |

### Utilities

| Plugin | Description |
|:-------|:------------|
| [**System Monitor**](https://github.com/nexion-one/plugin-system-monitor) | Real-time CPU and memory usage in the status bar. Detailed stats on demand. |
| [**Pomodoro**](https://github.com/nexion-one/plugin-pomodoro) | Focus timer in the status bar. Configurable work/break cycles with notifications and session tracking. |
| [**Quick Commands**](https://github.com/nexion-one/plugin-quick-commands) | Power-user shortcuts to clear terminal, refresh Git, and refresh the file explorer. |

---

<p align="center">
  <a href="https://nexion.one">nexion.one</a>
</p>
