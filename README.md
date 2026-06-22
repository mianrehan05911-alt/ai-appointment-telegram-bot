🤖 Telegram → Google Sheets → Google Calendar → Gmail Automation (n8n)
📌 Project Overview

This project demonstrates an end-to-end automation workflow built using n8n that integrates Telegram, Google Sheets, Google Calendar, and Gmail.

The workflow automatically:

Receives messages from Telegram
Stores structured data in Google Sheets
Creates events in Google Calendar
Sends confirmation emails via Gmail

This project is created for learning, practice, and portfolio purposes, showcasing real-world automation use cases.

🔧 Tools & Technologies Used
n8n – Workflow automation platform
Telegram Bot API – Incoming user messages
Google Sheets API – Data storage
Google Calendar API – Event scheduling
Gmail API – Email notifications
⚙️ Workflow Explanation
Telegram Trigger
A Telegram bot listens for incoming messages from users.
Data Processing in n8n
Messages are parsed and required fields are extracted.
Google Sheets Integration
Data is stored as a new row for each request.
Google Calendar Integration
Calendar events are created automatically using extracted data.
Gmail Notification
A confirmation email is sent to the user.
📂 Repository Structure
├── workflow.json          # Exported n8n workflow
├── README.md              # Project documentation
├── telegram_chat.png      # Telegram interaction screenshot
├── n8n_workflow.png       # n8n workflow canvas screenshot
├── google_sheets.png      # Google Sheets data screenshot
├── google_calendar.png    # Google Calendar event screenshot
└── gmail_sent.png         # Gmail confirmation email screenshot
🖼️ Screenshots Upload Note (Important)

Due to an upload issue, screenshots were not placed inside a single screenshots/ folder.

Current screenshot status:
Screenshots are uploaded individually in the root directory
Each screenshot is clearly named to indicate its purpose
No screenshot data is missing
Reason:
Screenshots were added after the initial JSON upload
They were uploaded one by one instead of inside a folder

This does not affect the functionality of the workflow.
The workflow.json file remains the primary functional asset.

🚀 How to Use This Workflow
Download or clone this repository
Import workflow.json into your n8n instance
Configure credentials:
Telegram Bot
Google Sheets
Google Calendar
Gmail
Activate the workflow
Send a test message via Telegram
🎯 Project Purpose
Learn and practice automation with n8n
Understand API-based integrations
Build a practical automation portfolio
📌 Notes
Credentials are not included for security reasons
Screenshots are provided only for demonstration
Workflow can be extended with validation or AI agents
✅ Conclusion

This automation shows how multiple services can be connected into a single, efficient workflow using n8n.
Even with screenshots uploaded individually, the project remains complete, functional, and well-documented.

