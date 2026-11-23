# AI agent-Unread Email Summariser

## Project Overview
Built an AI-powered Gmail automation workflow using n8n that automatically fetches the latest 5 unread emails, generates individual AI summaries, combines them, and sends the consolidated summary to Gmail.

## Technologies Used
- n8n – Workflow automation
- Gmail API – Fetching and sending emails
- OpenAI GPT-5-mini – AI-powered email summarisation
- Google OAuth 2.0 – Gmail authentication

## Workflow Architecture

1. Manual Trigger – Starts workflow execution.
2. Get Unread Emails – Fetches the latest 5 unread emails from Gmail.
3. Summarise Email – AI Agent generates a one-line summary of each email.
4. OpenAI Chat Model – Provides AI language model capabilities.
5. Combine Summaries – Aggregates individual email summaries.
6. Send Summary Email – Sends all summaries together to Gmail.

## Key Features
- Automatically identifies unread emails.
- Processes up to 5 emails per execution.
- Generates summaries within 20 words per email.
- Combines multiple summaries into one email.
- Reduces manual email-reading effort.

## Project Files
- `Unread Email Summariser.json` – Exported n8n workflow.
- `screenshots/` – Workflow canvas and execution screenshots.

## Execution Result
Successfully executed the n8n workflow and received the consolidated email summary in Gmail.

## Learning Outcomes
- Gmail API and OAuth integration.
- n8n workflow automation.
- AI Agent configuration.
- OpenAI model integration.
- Data aggregation and email automation.

## Author
Diwakar V

## Project Type
Week 4 – Day 1 | AI Agent Automation Project
