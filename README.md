📌 Lead Scoring Automation (n8n)
🚀 Overview

This project is an automated lead processing and scoring system built using n8n.

It receives incoming lead data via webhook, assigns a priority score based on business rules, stores the lead in Google Sheets, and triggers conditional email notifications.

🧠 Business Logic

Each lead is scored based on:

Budget > 200,000 → +50 points

Location = Dhaka → +20 points

Priority Rules:

Score ≥ 60 → High Priority

Score < 60 → Normal

🔄 Workflow Architecture

Webhook → Data Cleaning → Lead Scoring → Google Sheets Storage → Conditional Branching → Email Notification / Follow-up

High Priority Leads:

Immediate email notification to sales

Normal Leads:

Wait 10 minutes

Automated follow-up email sent to lead

🛠 Tech Stack

n8n

Gmail Node

Google Sheets Node

Webhook Trigger

Conditional IF Logic

Wait/Delay Node

📂 Files

workflow/lead-scoring-workflow.json → Exported n8n workflow

screenshots/ → Workflow and node configuration previews

docs/architecture.md → Technical breakdown of system design

🎯 Purpose

This project demonstrates:

Automation architecture design

Conditional logic implementation

Data processing and scoring

Workflow branching

Automated follow-up systems

Ahsan Karim
Cosmic IT
