<p align="center" float="left">
  <img alt="AutoSheet Logo" src="autosheet-github-profile.png" />
</p>

## Run an AI agent on any Google Sheet, via API.
Just send a prompt and a Google Sheets id. Automating spreadsheet work has never been that easy.

```sh
curl https://api.autosheet.com/v1/sheets/agents \
  --request POST \
  --header 'Content-Type: application/json' \
  --header "X-API-Key: $AUTOSHEET_API_KEY" \
  --data '{
    "prompt": "Score these leads against our scoring rules.",
    "document_id": "1mGKj92RmNEm_FeZudRs6ExBFMTdlvTWtwC38rhUMC0I"
  }'
```

and watch Autosheet work in your spreadsheet:

<p float="left">
  <img width="512" height="327" alt="Autosheet scoring leads in Google Sheets" src="https://github.com/user-attachments/assets/92fe4c44-daf6-42f9-a214-324651444851" />
</p>


## Links
- [Autosheet.com](https://autosheet.com/)
- [Docs](https://autosheet.com/docs/)
- [API reference](https://autosheet.com/docs/api/)
- [Support](https://autosheet.com/support/)
- [GPT for Work](https://gptforwork.com/)

<div align="center">
  <a href="https://www.youtube.com/@gptforwork" target="_blank">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" />
  </a>
</div>
