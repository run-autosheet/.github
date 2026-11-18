![Autosheet](autosheet-github-profile.png)

Autosheet is an AI agent for Microsoft Excel and Google Sheets. This organization holds its two public projects:

- [autosheet-mcp](https://github.com/run-autosheet/autosheet-mcp): the documentation of Autosheet MCP, the hosted server that lets ChatGPT, Claude and other AI clients work in Google Sheets, and the Autosheet plugin for Claude, Claude Code, ChatGPT and Codex.
- [AutosheetBench](https://github.com/run-autosheet/AutosheetBench): AutosheetBench, our public benchmark of AI products in Excel and Google Sheets.

## Autosheet MCP and API

Autosheet gives your AI assistant or your own code a Google Sheets specialist. Connect your assistant through Autosheet MCP, or call the Autosheet API from your code. Then send a prompt and a Google Sheets URL: the agent reads the spreadsheet, plans the work, makes the changes and checks the result.

### Get started

**From an AI assistant (MCP).** In ChatGPT or Claude, add Autosheet from its [ChatGPT plugin page](https://chatgpt.com/plugins/plugin_asdk_app_6aa196d5c8488191a3de00c74c9534ac) or the [Claude connector directory](https://claude.ai/directory/autosheet), then sign in with Google when prompted. In other MCP clients that support streamable HTTP with OAuth, add this server URL and complete the Google sign-in in your browser:

```text
https://mcp.autosheet.com/mcp
```

Setup steps for each client are on [autosheet.com/mcp](https://autosheet.com/mcp), and the [autosheet-mcp](https://github.com/run-autosheet/autosheet-mcp) repository documents the server.

**From code (REST API).** The [Autosheet API](https://autosheet.com/docs/api) runs the same agent over HTTP, with webhooks and an OpenAPI specification. Create an API key in the [dashboard](https://dashboard.autosheet.com/login). The API is in preview and may change.

Both need an Autosheet account, which you sign in to with Google. Autosheet can then work on any spreadsheet that Google account can edit. New accounts start with free credits.

### Example prompts

Send one of these with your Google Sheets URL:

- Summarize this spreadsheet and flag anything that looks off.
- Fill in the CEO, headcount and recent news for every company in column A.
- For each product, write a 50-word description and translate it into French.
- Score every lead against the rules in the Scoring rules tab.

The agent also writes and fixes formulas, cleans and formats tables, and builds charts and pivot tables.

### In Excel and Google Sheets

To use Autosheet from inside Excel or Google Sheets, install the [Excel add-in](https://autosheet.com/gpt-for-excel) or the [Google Sheets add-on](https://autosheet.com/gpt-for-sheets). The Google Sheets add-on runs the same agent as Autosheet MCP and the API, which work with Google Sheets only.

## AutosheetBench

AutosheetBench evaluates real AI products on realistic spreadsheet tasks, in Excel and Google Sheets. It has 187 tasks. Each one has a starting workbook, the exact prompts to send, and an automatic check or a rubric that scores the result pass or fail.

- [Results](https://autosheet.com/benchmark): the score, time and cost of every product and model we tested, with each task's prompt and outputs.
- [Code](https://github.com/run-autosheet/AutosheetBench): the tasks, the scorer and the macOS runner we used in Excel.
- [Dataset](https://huggingface.co/datasets/autosheet/AutosheetBench): the tasks and every result on Hugging Face, with the output workbooks, transcripts and recordings of the runs.

The code is licensed under Apache-2.0. The tasks and the scores are licensed under CC BY 4.0. What the tested products produced (answers, workbooks, screenshots and recordings) is not covered.

Autosheet, formerly GPT for Work, is built by [Talarian](https://talarian.io).

## Links

[Website](https://autosheet.com/) · [Benchmark](https://autosheet.com/benchmark) · [MCP setup](https://autosheet.com/mcp) · [API reference](https://autosheet.com/docs/api) · [Dashboard](https://dashboard.autosheet.com/login) · [Support](https://support.autosheet.com/hc/en-us/requests/new) · [YouTube](https://www.youtube.com/channel/UCa5AHL5_ugfRdFuK3I3stDw)
