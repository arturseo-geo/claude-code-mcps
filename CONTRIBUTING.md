# Contributing to Claude Code MCP Servers

Thank you for considering contributing to this MCP servers collection! This guide will help you get started.

## Before You Start

- The MCP specification is maintained by Anthropic: https://modelcontextprotocol.io/
- Claude Code documentation: https://docs.anthropic.com/en/docs/claude-code
- Each server must be production-tested and documented

## Adding a New Server

### 1. Test the Server

- Install the MCP server locally
- Verify it works with Claude Code
- Test edge cases and error handling
- Document any quirks or limitations

### 2. Update README.md

Add entry to the **Servers** table:

```markdown
| **YourServer** | Description | Auth type | Status |
|---|---|---|---|
| Your description | OAuth/Token/Key | ✅ Prod |
```

### 3. Add Configuration Section

Add a section under **Configuration** with:
- JSON example
- How to get credentials
- Any setup steps

### 4. Add Use Case

Add 1-2 examples under **Use Cases** showing how this server pairs with others.

### 5. Submit PR

- Create a branch: `git checkout -b add-yourserver`
- Commit changes: `git commit -m "Add YourServer MCP documentation"`
- Push and open PR with description of the server and why it's useful

## Code of Conduct

- Be respectful and constructive
- Focus on production reliability
- Document security implications
- Test thoroughly before PR

## Questions?

Open an issue or reach out to [@TheGEO_Lab](https://x.com/TheGEO_Lab) on X.
