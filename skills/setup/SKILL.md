---
name: setup
description: Connect Mobile Joe after plugin installation, verify access and choose an app for subsequent content work. Use when setting up the plugin or troubleshooting a missing app in the connection.
---

Use the Mobile Joe plugin's `list_apps` tool to check the current connection.
Follow pagination when more apps are available. Reuse an existing authenticated
connection rather than adding a second MCP server.

If authentication is required, guide the developer through the client's Connect
or Reconnect flow. They sign in on the Mobile Joe website and choose the apps
and access levels to grant. Keep credentials in that sign-in flow; do not ask
for passwords or tokens in chat. Use the existing connection UI rather than
editing local MCP configuration.

Choose the app the developer named if it is available. If their intended app is
unclear, show the available app titles and ask which one they want to work on.
If an app is missing, explain that the connection only sees apps selected during
consent. Help them reconnect with the intended account and app selection; do
not request broader access than their task needs.

Finish by confirming the selected app and suggesting a first inspection of its
FAQs or feature plans. Setup itself does not create, edit or publish content.
