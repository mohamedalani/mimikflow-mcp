# Installing the MimikFlow MCP connector

This is a **remote** MCP server. There is nothing to build and no package to install.

## Server details

- URL: `https://mimikflow.com/api/mcp`
- Transport: Streamable HTTP
- Authentication: OAuth 2.1 (PKCE S256), discovered automatically from the server
- Requirements: a MimikFlow account on Pro or Agence (the free trial works too)

## Add it to your MCP client

Add the bare URL `https://mimikflow.com/api/mcp` as a custom/remote MCP connector. Your client will discover OAuth at `/.well-known/oauth-authorization-server` and open a consent screen on mimikflow.com. Approve it, and the tools become available.

No API key, no token to copy, no environment variable.

## Verify it works

After connecting, ask your assistant for an account overview. A working connection returns your MimikFlow campaigns and pipeline statistics.

## Support

hello@mimikflow.com
