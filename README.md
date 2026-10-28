# UGCHooks Agent Skill

**Paste a product link, get 100 TikToks and Reels.**

This skill tells an agent how to use the UGCHooks MCP server: create a post batch from a product link, read hooks, slide text, captions and hashtags, write unlocked parts, and hand finished renders to UGC API for posting.

[Website](https://ugchooks.app) · [Setup guide](https://ugchooks.app/integrations/) · [MCP repository](https://github.com/saeedmsdi-ugchooks/mcp-server)

## When to use it

> Make a UGCHooks batch for https://yourapp.com and give me the five strongest hooks.

> Read my latest batch and rewrite the captions in a drier tone.

## Install

```sh
npx skills add saeedmsdi-ugchooks/agent-skill
```

Skill installation and MCP connection are separate: connect `https://ugchooks.app/mcp` in a remote MCP client, or use `npx -y ugchooks-mcp` for a stdio client with Node.js 22+. Sign in through the browser and review the requested permissions.
