# Security Policy

## Reporting Security Issues

If you discover a security vulnerability, **please do not open a public issue**. Instead:

1. Email **artur@thegeolab.net** with:
   - Description of the vulnerability
   - Steps to reproduce
   - Potential impact
   - Suggested fix (if applicable)

2. Include your GitHub username so we can credit you

3. Allow 7-14 days for assessment and patch

## Security Best Practices for MCP Servers

### Credentials Management

**DO:**
- Store credentials in environment variables
- Use `.env` files (git-ignored)
- Rotate API keys regularly
- Use minimal permission scopes
- Use service accounts with limited roles

**DON'T:**
- Commit `.mcp.json` with real credentials
- Hardcode API keys in config files
- Share credentials in issues/PRs
- Use personal accounts for API access
- Store credentials in version control

### Server Configuration

**DO:**
- Validate all inputs
- Use HTTPS/TLS for connections
- Implement rate limiting
- Log security events
- Use timeouts for network requests

**DON'T:**
- Trust user input without validation
- Use plaintext connections
- Allow unlimited concurrent requests
- Expose stack traces in errors
- Cache sensitive data unnecessarily

## Known Issues

None currently documented. If you find a vulnerability, please report it securely (see above).

## Security Updates

We provide security updates for the latest version. Update regularly.

Older versions may have unpatched vulnerabilities.

## Questions?

Contact [@TheGEO_Lab](https://x.com/TheGEO_Lab) on X or email artur@thegeolab.net
