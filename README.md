# AI-HR-Automation-Workflow
# AI Powered: AI HR Recruitment & Centralized Dashboard Automation

## Overview

This project demonstrates an AI-powered HR Recruitment Automation System designed to streamline candidate screening, recruitment tracking, interview management, and workforce analytics.

The solution leverages Artificial Intelligence and workflow automation to reduce manual recruitment effort, improve hiring efficiency, and provide centralized visibility into recruitment operations through an executive dashboard.

## Technologies Used

- n8n
- OpenAI GPT
- Google Forms
- Google Sheets
- Google Drive
- Supabase
- Trello
- Gmail
- Telegram
- Looker Studio

## Key Features

- Automated candidate intake via Google Forms
- AI-powered CV analysis and candidate scoring
- Automated candidate shortlisting
- Recruitment pipeline management with Trello
- Interview scheduling notifications via Gmail
- HR alerts through Telegram
- Centralized candidate database in Supabase
- Recruitment analytics dashboard using Looker Studio

## Workflow Architecture

## Workflow in n8n


```text
Google Form Submission
          ↓
Google Sheets Trigger
          ↓
CV Retrieval from Google Drive
          ↓
OpenAI CV Analysis
          ↓
Candidate Scoring
          ↓
Supabase Storage
          ↓
Trello Recruitment Pipeline
          ↓
Gmail Notifications
          ↓
Telegram Alerts
          ↓
Google Sheets Reporting
          ↓
Looker Studio Dashboard

