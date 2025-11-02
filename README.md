# TaskMail-Bot-
Turns tasks from Google Sheets into ready-to-send Gmail drafts using AI.



### 2. Configure Credentials
Before executing, make sure you have connected:
- Google Sheets OAuth2 API
- Google Gemini (PaLM) API
- Gmail OAuth2 API

You can create or select these under:
`n8n → Settings → Credentials`

### 3. Update Spreadsheet and Sheet Names
In the Google Sheets nodes:
- Replace the document ID with your own spreadsheet ID.
- Update sheet names (Sheet1, Sheet2) if they differ.

---

## Running the Workflow
1. Open the workflow in n8n.
2. Click **Execute Workflow**.
3. Check:
 - Generated email in your Gmail drafts.
 - New row appended in your Sheet2.

---

## File Structure

