![Autosheet](autosheet-github-profile.png)

Autosheet gives your AI assistant or your own code a Google Sheets specialist. Connect your assistant through Autosheet MCP, or call the Autosheet API from your code. Then send a prompt and a Google Sheets URL: the agent reads the spreadsheet, plans the work, makes the changes and checks the result.

## Get started

**From an AI assistant (MCP).** In ChatGPT or Claude, add Autosheet from its [ChatGPT plugin page](https://chatgpt.com/plugins/plugin_asdk_app_6aa196d5c8488191a3de00c74c9534ac) or the [Claude connector directory](https://claude.ai/directory/autosheet), then sign in with Google when prompted. In other MCP clients that support streamable HTTP with OAuth, add this server URL and complete the Google sign-in in your browser:

```text
https://mcp.autosheet.com/mcp
```

Setup steps for each client are on [autosheet.com/mcp](https://autosheet.com/mcp), and the [autosheet-mcp](https://github.com/run-autosheet/autosheet-mcp) repository documents the server.

**From code (REST API).** The [Autosheet API](https://autosheet.com/docs/api) runs the same agent over HTTP, with webhooks and an OpenAPI specification. Create an API key in the [dashboard](https://dashboard.autosheet.com/login). The API is in preview and may change.

Both need an Autosheet account, which you sign in to with Google. Autosheet can then work on any spreadsheet that Google account can edit. New accounts start with free credits.

## Example prompts

Send one of these with your Google Sheets URL:

- Summarize this spreadsheet and flag anything that looks off.
- Fill in the CEO, headcount and recent news for every company in column A.
- For each product, write a 50-word description and translate it into French.
- Score every lead against the rules in the Scoring rules tab.

The agent also writes and fixes formulas, cleans and formats tables, and builds charts and pivot tables.

## In Excel and Google Sheets

To use Autosheet from inside Excel or Google Sheets, install the [Excel add-in](https://autosheet.com/gpt-for-excel) or the [Google Sheets add-on](https://autosheet.com/gpt-for-sheets). The Google Sheets add-on runs the same agent as Autosheet MCP and the API, which work with Google Sheets only.

Autosheet, formerly GPT for Work, is built by [Talarian](https://talarian.io).

## Links

[Website](https://autosheet.com/) · [MCP setup](https://autosheet.com/mcp) · [API reference](https://autosheet.com/docs/api) · [Dashboard](https://dashboard.autosheet.com/login) · [Support](https://support.autosheet.com/hc/en-us/requests/new) · [YouTube](https://www.youtube.com/channel/UCa5AHL5_ugfRdFuK3I3stDw)
