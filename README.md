# sameera207 Claude Code Plugin Marketplace

A personal Claude Code plugin marketplace catalog containing plugins built by sameera207.

## Plugins

| Plugin | Description |
|--------|-------------|
| `statusline` | Status bar showing context usage, git branch, tokens, session time and model |

## Adding this Marketplace to Claude Code

Add the following to your `~/.claude/settings.json` to register this marketplace:

```json
{
  "extraKnownMarketplaces": [
    {
      "name": "sameera207",
      "source": "github",
      "repo": "sameera207/claude-plugins"
    }
  ]
}
```

## Installing Plugins

Once the marketplace is registered, install plugins with a single command inside Claude Code:

```
/plugin install statusline@sameera207
```

## Available Plugins

### statusline

A status bar plugin for Claude Code that displays:
- Context usage
- Git branch
- Token count
- Session time
- Model name

**Source:** [sameera207/claude-statusline](https://github.com/sameera207/claude-statusline)
