---
name: Bug Report
about: Report a bug with an MCP server configuration or connection
labels: bug
---

## Describe the Bug

Clear description of what isn't working.

## MCP Server

Which server(s) are affected?
- [ ] GitHub
- [ ] WordPress
- [ ] Google Search Console
- [ ] Google Analytics 4
- [ ] LinkedIn
- [ ] PostgreSQL
- [ ] Redis
- [ ] Notion
- [ ] Gumroad
- [ ] Firecrawl
- [ ] Puppeteer
- [ ] Telegram
- [ ] Filesystem

## Environment

- **Claude Code version:** (run `claude code --version`)
- **OS:** macOS / Linux / Windows
- **Node version:** (run `node --version`)
- **MCP version:** (check npm package version)

## Steps to Reproduce

1. 
2. 
3. 

## Expected Behavior

What should happen?

## Actual Behavior

What actually happens?

## Error Output

Share any error messages:

```
[paste error here]
```

## Configuration

Share your `.mcp.json` (with credentials removed):

```json
{
  "mcpServers": {
    "your-server": {
      "command": "...",
      "args": [...]
    }
  }
}
```

## Logs

Check Claude Code logs:

```bash
cat ~/.claude/logs/*
```

Share relevant log entries (with credentials removed).

## Additional Context

Anything else that might help?
