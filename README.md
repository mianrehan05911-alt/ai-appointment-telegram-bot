# AI Appointment Booking System – Telegram Bot

## Overview
This project is a fully automated Telegram-based appointment booking system
built using n8n. The system handles the complete booking lifecycle — from
user interaction to calendar scheduling — with zero manual intervention.

It is designed to eliminate delays, double bookings, and repetitive manual
coordination by automating conversations, availability checks, confirmations,
and notifications.

---

## Problem
Manual appointment booking typically involves:
- Back-and-forth messaging
- Human errors in scheduling
- Double bookings
- Delayed confirmations

These issues waste time for both service providers and clients.

---

## Solution
An automation-first approach using n8n and Telegram that:
- Collects user details step by step via chat
- Checks real-time availability in Google Calendar
- Suggests alternative time slots if a slot is unavailable
- Creates confirmed calendar events automatically
- Logs appointment data into Google Sheets
- Sends confirmation emails to both client and service provider

All actions occur automatically after initial setup.

---

## Tools & Integrations
- **n8n** – Workflow orchestration
- **Telegram Bot API** – User interaction
- **Google Calendar API** – Availability checks & event creation
- **Google Sheets API** – Appointment logging
- **Email Automation** – Confirmation notifications
- **REST APIs & Webhooks**

---

## Workflow Logic
1. User initiates booking through Telegram
2. Bot collects required information:
   - Name
   - Email
   - Preferred date and time
   - Reason for appointment
3. System checks Google Calendar availability
4. If the slot is busy, alternative slots are suggested
5. Upon confirmation:
   - Calendar event is created
   - Appointment is logged in Google Sheets
   - Confirmation emails are sent to both client and doctor

---

## Key Engineering Challenges
- Designing a multi-step conversational flow without losing context
- Handling calendar conflicts and suggesting alternatives
- Ensuring complete and valid user data collection
- Coordinating multiple API integrations in a single workflow

---

## Proof of Work
This system was tested using real Telegram conversations.

The `screenshots/` folder contains anonymized proof showing:
- Multi-step Telegram booking conversations
- Google Sheets appointment logs
- Google Calendar event creation
- Automated confirmation emails sent to both client and doctor

All personal data has been anonymized for privacy.

---

## Project Status
✔ Fully implemented  
✔ Tested with real users  
✔ Ready for reuse and extension  

---

## Author
**Muhammad Rehan**  
Automation Engineer (n8n) & AI Agent Builder.

