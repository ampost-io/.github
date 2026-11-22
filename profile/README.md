# Ampost

**One API to publish, schedule and track posts on every social network.**

[Ampost](https://ampost.io?ref=github) posts to Instagram, Facebook, Threads, X, YouTube, Pinterest,
Bluesky, Telegram and Discord with one call: text, images, videos, threads and first comments, checked
against each platform's rules before anything is sent. Use it from code (REST API and SDKs), from AI
agents (hosted MCP server) or from no-code tools.

```sh
curl https://api.ampost.io/api/posts \
  -H "Authorization: Bearer $AMPOST_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"text": "Hello from Ampost", "targets": [{"platforms": ["bluesky", "threads"]}], "publishNow": true}'
```

## Start here

| | |
| --- | --- |
| [API docs](https://ampost.io/docs?ref=github) | REST reference, errors, idempotency, webhooks, media upload |
| [OpenAPI document](https://api.ampost.io/openapi.json) | Every endpoint, for code generators and agents |
| [MCP server](https://ampost.io/docs/mcp?ref=github) | `https://api.ampost.io/mcp` for Claude Code, Cursor, VS Code, Codex and other MCP clients |
| [How-to guides](https://ampost.io/how-to?ref=github) | n8n, Make, Python, GitHub Actions, Google Sheets, RSS, with templates |
| [Pricing](https://ampost.io/pricing?ref=github) | Free plan to start, no card |

## Repositories

| Repo | What it is |
| --- | --- |
| [ampost-node](https://github.com/ampost-io/ampost-node) | TypeScript / JavaScript SDK: `npm install ampost` |
| [ampost-python](https://github.com/ampost-io/ampost-python) | Python SDK, sync and async: `pip install ampost` (soon on PyPI) |
| [ampost-cli](https://github.com/ampost-io/ampost-cli) | Post and schedule from the terminal and CI: `npm install -g ampost-cli` |
| [n8n-nodes-ampost](https://github.com/ampost-io/n8n-nodes-ampost) | n8n community node: install `n8n-nodes-ampost` in Settings → Community Nodes |
| [make-ampost](https://github.com/ampost-io/make-ampost) | Make app and scenario templates (RSS, Google Sheets, AI post with approval, YouTube cross-post); scenario blueprints work today with Make's HTTP module |
| [ampost-skills](https://github.com/ampost-io/ampost-skills) | Claude Code plugin and Agent Skills: the hosted MCP server plus skills for real jobs (post everywhere, a blog post into platform posts, a week in the queue, video to Reels and Shorts, a weekly analytics report, CSV import) |

## Links

[Website](https://ampost.io?ref=github) · [Docs](https://ampost.io/docs?ref=github) ·
[llms.txt](https://ampost.io/llms.txt?ref=github) · [Status](https://ampost.io/status?ref=github) ·
Support: support@ampost.io
