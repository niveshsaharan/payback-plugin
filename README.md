# OweJar

OweJar (formerly Payback) tracks who owes whom, splits expenses, and records settlements from your AI assistant.

Website: https://owejar.com/

Hosted MCP endpoint: https://owejar.com/mcp

Sign in using OAuth and choose the permissions you want to grant. The server records ledger events and never transfers money. Changes use the corresponding preparation and confirmation workflow.

[Connection guide](https://owejar.com/help/connect-ai-assistant) · [Privacy](https://owejar.com/privacy) · [Terms](https://owejar.com/terms) · [Support](https://owejar.com/support)

Existing Payback connections remain supported during the domain transition. New installations use OweJar. The repository URL is retained so existing directory links continue working.

This repository contains only the public connector package and onboarding instructions. The hosted server runs at the endpoint above.

The internal plugin and MCP connection identifier remains `payback` so existing installations can update. The display name and service URLs are OweJar.
