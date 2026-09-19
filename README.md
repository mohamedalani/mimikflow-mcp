# MimikFlow MCP

Homepage: https://mimikflow.com/fonctionnalites/mcp

MimikFlow automates the full B2B LinkedIn prospecting cycle: it finds prospects, sends invitations, writes the first message, follows up and books meetings into your calendar.

This repository is the public distribution manifest for the **MimikFlow remote MCP server**. It contains no application code: only the connector metadata required by MCP clients and directories.

## Connect

| | |
|---|---|
| **Server URL** | `https://mimikflow.com/api/mcp` |
| **Transport** | Streamable HTTP |
| **Authentication** | OAuth 2.1 (PKCE, S256), discovered automatically |
| **Documentation** | https://mimikflow.com/fonctionnalites/mcp (FR) - https://mimikflow.com/features/mcp (EN) |
| **Privacy policy** | https://mimikflow.com/privacy |
| **Support** | hello@mimikflow.com |

Add the bare URL as a custom connector in your MCP client. The client discovers OAuth and walks the standard flow; no secret to paste.

## What the connector does

It turns your AI assistant into a control tower for the machine you already run:

- **Monitor** the account overview, pipeline stats, campaigns and connected LinkedIn accounts.
- **Decide**: pending drafts, escalations, conversations waiting for a human reply.
- **Understand**: read prospect conversations, inspect won and lost threads.
- **Configure**: adjust targeting, campaign profile and pipeline settings.
- **Feed**: search prospects and add them to a campaign.
- **Schedule**: list meetings, snooze a lead, hand a thread back to the AI.

MimikFlow keeps prospecting on schedule. The assistant surfaces what needs a human decision. It never widens permissions, plan access or LinkedIn limits.

Works with any MCP client: Claude, ChatGPT, Cursor, Claude Code, Gemini CLI.

## Requirements

A MimikFlow account on the Pro or Agence plan (the free trial is Pro-level and works too).

## License

Proprietary. See https://mimikflow.com/terms
