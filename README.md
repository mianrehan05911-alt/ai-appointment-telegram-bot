# 🤖 Telegram Appointment Booking Automation (n8n)

## 📌 Overview
This project is an end-to-end automation system built using **n8n** that connects Telegram with Google Sheets, Google Calendar, and Gmail.

It automates the complete appointment booking process — from user interaction to scheduling and confirmation — without any manual work.

---

## ⚙️ What This System Does

- Receives booking requests from Telegram
- Collects user details through chat
- Stores data in Google Sheets
- Checks and creates events in Google Calendar
- Sends confirmation emails via Gmail

---

## 🔧 Tools & Technologies

- n8n (Workflow Automation)
- Telegram Bot API
- Google Sheets API
- Google Calendar API
- Gmail API

---

## 🔄 Workflow Summary

1. User sends message on Telegram bot  
2. Bot collects required information (name, email, date, reason)  
3. Data is processed inside n8n workflow  
4. Information is stored in Google Sheets  
5. Appointment is created in Google Calendar  
6. Confirmation email is sent to client and doctor  

---

## 📂 Repository Structure

workflow.json → Exported n8n workflow  
README.md → Project documentation  
telegram-booking-flow-1.png → Telegram chat flow (part 1)  
telegram-booking-flow-2.png → Telegram chat flow (part 2)  
google-sheets-log.png → Stored booking data  
google-calendar-event.png → Created calendar event  
confirmation-email-for-client.png → Email sent to client  
confirmation-email-for-doctor.png → Email sent to doctor  

---

## 🖼️ Screenshots Note

Screenshots are uploaded individually in the repository root and show
the complete working flow of the automation system.

---

## 🎯 Purpose of Project

- Learn real-world workflow automation using n8n  
- Integrate multiple APIs into one system  
- Build portfolio-ready automation projects  
- Simulate production-level booking system  

---

## 📌 Key Highlights

- Fully automated appointment booking system  
- No manual intervention required after setup  
- Multi-step Telegram conversational flow  
- Real-time calendar conflict handling  
- Automated email notifications  

---

## 🚀 How to Use

1. Import `workflow.json` into n8n  
2. Connect credentials:
   - Telegram Bot
   - Google Sheets
   - Google Calendar
   - Gmail  
3. Activate workflow  
4. Start chatting with Telegram bot  

---

## 🏁 Conclusion

This project demonstrates a real-world automation pipeline where multiple services
are connected into a single intelligent workflow using n8n.

It is designed as a portfolio project to showcase automation, API integration,
and workflow engineering skills.
