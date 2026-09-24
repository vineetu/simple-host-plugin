# Simple Host for Claude

Describe a website to Claude and it goes online at its own address, with forms that save, private lists only you can read, visitor counts, and your own domain when you want one.

This plugin bundles the Simple Host skills and the Simple Host connector (`https://simple-host.app/mcp`). The first time Claude needs it, a Simple Host sign-in window opens: sign in with Google or an emailed code, then Allow. After that every chat is signed in.

## Install in Claude Code

```
/plugin marketplace add vineetu/simple-host-plugin
/plugin install simple-host@simple-host
```

## GitHub Copilot

This repository is also an [Agent Plugins](https://agent-plugins.org) package (`plugin.json`, `mcp.json`, `skills/` at the root), so Copilot can install it from the Awesome Copilot marketplace once listed. To connect Copilot in VS Code by hand: run **MCP: Add Server** from the Command Palette, choose **HTTP**, paste `https://simple-host.app/mcp`, name it `simple-host`, and sign in when asked.

## Source

Generated from [github.com/vineetu/simple-host](https://github.com/vineetu/simple-host) (`plugins/simple-host`). Please open issues there.

MIT licensed. Website: https://simple-host.app
