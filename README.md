# Newsletter Automation with n8n

Automate newsletter delivery using **n8n**: fetch subscribers, prepare content, and send emails automatically.

## Features
- Scheduled newsletter sending
- Fetch subscriber data from Google Sheets
- Personalized HTML emails via SMTP

## Tools
- **n8n** – Workflow automation
- **Google Sheets** – Subscriber data
- **SMTP** – Email sending
- **HTML Editor** – Newsletter design

## Workflow
1. **Trigger** – Schedule workflow (e.g., every Monday 9 AM)
2. **Get Subscribers** – Read names & emails from Google Sheets
3. **Prepare Content** – Set HTML content and personalize
4. **Send Emails** – SMTP sends email to each subscriber

## Example Configuration
- **Google Sheets Node**: Range `A2:B`
- **Set Node**:  
```json
{
  "title": "Weekly Tech Newsletter",
  "message": "Welcome to our weekly update! Stay tuned for tech news!"
}
