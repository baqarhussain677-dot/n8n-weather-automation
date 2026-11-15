# Daily Karachi Weather Email Automation (n8n)

A simple n8n automation I built to get Karachi's live weather update straight in my inbox every morning at 8:00 AM (PKT) using the Gmail API.

---

## How It Works
```text
[Schedule Trigger (8:00 AM PKT)] ──▶ [HTTP Request (wttr.in API)] ──▶ [Gmail Node (OAuth2)]
