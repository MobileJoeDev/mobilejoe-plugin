# Mobile Joe plugin

Manage the content of your [Mobile Joe](https://www.mobilejoe.dev) apps from your AI agent: maintain FAQs and their translations, curate feature plans and update app settings.

Connect your existing Mobile Joe account and choose which apps and permissions to share. The agent inspects stored content, prepares drafts and publishes only when you ask. Changes to published content are visible to app users immediately. The plugin does not manage alerts, create apps or change subscriptions.

The plugin connects to the Mobile Joe MCP server at `https://app.mobilejoe.dev/mcp` and signs you in with OAuth. It includes a setup skill that checks the connection and helps you choose an app.

## Install

### Claude Code

```bash
claude plugin install mobile-joe --marketplace MobileJoeDev/mobilejoe-plugin
```

Then run `/mcp`, select the Mobile Joe server and authenticate.

### Codex

```bash
codex plugin marketplace add MobileJoeDev/mobilejoe-plugin
codex plugin add mobile-joe@mobilejoe
```

### ChatGPT and Claude

Add Mobile Joe from the app directory, or add `https://app.mobilejoe.dev/mcp` as a custom connector.

### Cursor

Clone this repository into `~/.cursor/plugins/local/mobile-joe`, then run **Developer: Reload Window**.

## Try it

- "Show my apps and their FAQs, including stored translations."
- "Draft a FAQ for CSV export with German and French translations. Show me the result before publishing."
- "Check my feature plans for overlapping proposals and suggest what to improve."

## Documentation and support

- Documentation: https://docs.mobilejoe.dev/mcp/
- Support: hey@mobilejoe.dev
- Privacy: https://www.mobilejoe.dev/legal/privacy
- Terms: https://www.mobilejoe.dev/legal/terms

## Feedback

This repository contains the released plugin. Please send questions, bug reports and ideas to hey@mobilejoe.dev instead of opening issues or pull requests here.

## License

MIT
