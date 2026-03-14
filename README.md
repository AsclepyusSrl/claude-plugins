# Asclepyus Claude Code Plugins

Private plugin marketplace for Asclepyus Srl.

## Setup

Add this marketplace to your Claude Code installation:

```
/plugin marketplace add AsclepyusSrl/claude-plugins
```

## Available Plugins

| Plugin | Description | Install |
|--------|-------------|---------|
| **repository-foundation** | Audit and setup Python repo DevOps foundations | `/plugin install repository-foundation@asclepyus-plugins` |

## Commands

### repository-foundation

| Command | What it does |
|---------|-------------|
| `/repository-foundation:check` | Audit only — scans repo, reports gaps. Read-only. |
| `/repository-foundation:setup` | Full setup — audit + implement all missing pieces. |
| `/repository-foundation:fix` | Targeted — fix only what's broken or missing. |
