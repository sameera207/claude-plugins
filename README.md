# sameera207 Claude Code Plugin Marketplace

A personal Claude Code plugin marketplace catalog containing plugins built by sameera207.

## Plugins

| Plugin | Description |
|--------|-------------|
| `claude-diagram` | Auto-generates Mermaid diagrams from plans, renders in a full-screen browser viewer with zoom/pan |
| `claude-statusline` | Status bar showing context usage, git branch, tokens, session time and model |

## Installation

Run these commands inside Claude Code:

```
/plugin marketplace add sameera207/claude-plugins
```

Then install whichever plugin you want:

```
/plugin install claude-diagram@sameera207
/plugin install claude-statusline@sameera207
```

## Available Plugins

### claude-diagram

Auto-generates Mermaid diagrams whenever Claude writes a plan or todos, and renders them in a full-screen browser viewer. Also available on-demand via `/explain-diagram`.

Features:
- Automatic diagram generation on `TodoWrite` / `ExitPlanMode` — no API key required
- Smart diagram type inference (flowchart, sequence, ER, class, state, gantt, gitGraph, C4Context)
- Full-screen light-theme viewer that scales to fit any number of elements
- Zoom (scroll wheel or `+`/`-` keys) and drag-to-pan
- Copy Mermaid source button

**Source:** [sameera207/claude-diagram](https://github.com/sameera207/claude-diagram)

---

### claude-statusline

A status bar plugin for Claude Code that displays:
- Context usage
- Git branch
- Token count
- Session time
- Model name

**Source:** [sameera207/claude-statusline](https://github.com/sameera207/claude-statusline)
