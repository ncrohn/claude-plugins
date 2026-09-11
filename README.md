# ncrohn-plugins

A plugin marketplace by Nick Crohn. Works with Claude Code and Codex.

## Usage

Add this marketplace to Claude Code:

```bash
/plugin marketplace add ncrohn/claude-plugins
```

Or Codex:

```bash
codex plugin marketplace add ncrohn/claude-plugins
```

Then install any plugin:

```bash
/plugin install claude-tamagotchi@ncrohn-plugins
codex plugin add shape@ncrohn-plugins
```

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [claude-tamagotchi](https://github.com/ncrohn/claude-tamagotchi) | A persistent Tamagotchi creature that lives in your Claude Code status line |
| [shape](https://github.com/ncrohn/shape) | Human-driven design and planning — you design, the agent supplies terrain, objections, and structure. Claude Code and Codex |
