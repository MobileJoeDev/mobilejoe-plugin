<h3 align="center">🦫 Mobile app toolkit for indies and small teams</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Claude-supported-blueviolet.svg" alt="Claude supported">
  <img src="https://img.shields.io/badge/Codex%20%26%20ChatGPT-supported-blue.svg" alt="Codex and ChatGPT supported">
  <img src="https://img.shields.io/badge/Cursor-supported-black.svg" alt="Cursor supported">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-lightgrey.svg" alt="MIT License"></a>
</p>

[Mobile Joe](https://mobilejoe.dev) gives indie developers and small teams native tools for their mobile apps. This plugin lets your AI agent manage their content, so you can spend more time on what makes your app unique:

- **Feature plans**: Turn user requests into curated plans in your own words, find overlaps, and merge duplicates.
- **FAQs**: Draft answers, translate them into your users' languages, and publish them without an app release.
- **App settings**: Keep your app's title, website, and deep link up to date.
- …and more coming soon.

You choose which apps the agent can access and what it can do. It prepares drafts and publishes only when you ask.

[Sign up](https://mobilejoe.dev/#pricing) to get started.

## Features

| Feature | What your agent can do |
| --- | --- |
| Feature plans with votes and statuses | Read, find overlaps, draft, merge, set statuses |
| FAQs with translations | Read, draft, translate, reorder, publish, archive |
| App settings | Change title, website, and deep link URL |

Requires a Mobile Joe account and Claude, Claude Code, Codex, ChatGPT, or Cursor. The plugin connects to the Mobile Joe MCP server at `https://app.mobilejoe.dev/mcp` with OAuth and includes a setup skill.

## Installation

Install the plugin in Claude Code:

```bash
claude plugin install mobile-joe --marketplace MobileJoeDev/mobilejoe-plugin
```

Or in Codex:

```bash
codex plugin marketplace add MobileJoeDev/mobilejoe-plugin
codex plugin add mobile-joe@mobilejoe
```

In Claude and ChatGPT, add Mobile Joe from the app directory or add `https://app.mobilejoe.dev/mcp` as a custom connector. In Cursor, clone this repository into `~/.cursor/plugins/local/mobile-joe` and run **Developer: Reload Window**.

## Quick start

Connect once: In Claude Code, run `/mcp` and authenticate the Mobile Joe server. In Cursor, open **Cursor Settings → Tools & MCP** and click **Authenticate** next to **mobile_joe**. Other agents ask you to connect on first use. Sign in to Mobile Joe, select your apps, and choose an access level. Then ask your agent:

```text
Show my apps and their FAQs, including stored translations.
```

New FAQs and feature plans stay drafts until you ask the agent to publish them. Changes to published content are visible to app users immediately. Review or revoke access anytime under **Account → Connections** in the dashboard.

## Documentation

Access levels, FAQs, feature plans, and reconnecting are covered in the [Mobile Joe documentation](https://docs.mobilejoe.dev/mcp/). Questions and feedback go to [hey@mobilejoe.dev](mailto:hey@mobilejoe.dev); this repository only contains releases. See our [privacy policy](https://www.mobilejoe.dev/legal/privacy) and [terms](https://www.mobilejoe.dev/legal/terms).
