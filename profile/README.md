![Autosheet](autosheet-github-profile.png)

Autosheet is an AI agent for Google Sheets that your AI assistant or your own code can call. Send it a prompt and a Google Sheets URL, and it reads the spreadsheet, plans the work, makes the changes and checks the result.

## Get started

**From an AI assistant (MCP).** Add Autosheet as a remote MCP server in a client that supports streamable HTTP with OAuth, then sign in with Google when prompted:

```text
https://mcp.autosheet.com/mcp
```

In Claude and ChatGPT, you can also add it from the [Claude connector directory](https://claude.ai/directory/autosheet) or from its [ChatGPT plugin page](https://chatgpt.com/plugins/plugin_asdk_app_6aa196d5c8488191a3de00c74c9534ac). Setup steps for other clients are on [autosheet.com/mcp](https://autosheet.com/mcp), and the server is documented in [autosheet-mcp](https://github.com/run-autosheet/autosheet-mcp).

**From code (REST API).** The [Autosheet API](https://autosheet.com/docs/api) runs the same agent over HTTP, with webhooks and an OpenAPI specification. Create an API key in the [dashboard](https://dashboard.autosheet.com/login). The API is in preview and may change.

Both require an Autosheet account, which you sign in to with Google. New accounts start with free credits.

You need edit access to the spreadsheet through the Google account you connect.

## What to ask it

Send a prompt with your Google Sheets URL, for example:

- Summarize this spreadsheet and flag anything that looks off.
- Fill in the CEO, headcount and a fit score for every company in column A.
- For each product, write a 50-word description and translate it into French.
- Append these new orders to the master sheet and refresh the totals tab.

It also writes and fixes formulas, cleans and formats tables, and builds charts and pivot tables.

## Part of Autosheet

Autosheet, formerly GPT for Work, is AI for Excel and Google Sheets from [Talarian](https://talarian.io). The agent you reach here also powers the [Google Sheets add-on](https://autosheet.com/gpt-for-sheets). MCP and the API work with Google Sheets only; in Excel, use the [Excel add-in](https://autosheet.com/gpt-for-excel).

## Links

[Website](https://autosheet.com/) · [MCP setup](https://autosheet.com/mcp) · [API reference](https://autosheet.com/docs/api) · [Dashboard](https://dashboard.autosheet.com/login) · [Support](https://support.autosheet.com/hc/en-us/requests/new) · [YouTube](https://www.youtube.com/channel/UCa5AHL5_ugfRdFuK3I3stDw)
