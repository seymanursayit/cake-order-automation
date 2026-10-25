# Cake Order Quotation Automation

**Author:** Şeymanur Sayıt  
**Program:** GoIT AI Automation  
**Project Type:** n8n Workflow Automation

## Overview

An AI-powered email automation workflow built with n8n to process customer cake orders and generate personalized quotations.

## Workflow

1. **Gmail Trigger:** Detects incoming emails.
2. **AI Agent:** Analyzes emails and extracts cake order details.
3. **If Node:** Checks whether the email contains a cake order request.
4. **Google Docs:** Creates and updates the quotation document.
5. **Google Drive:** Shares the document.
6. **Gmail:** Sends the quotation link to the customer.

## Pricing

Each cake costs 1,000 TRY.

**Formula:** Total Price = Number of Cakes × 1,000 TRY

- 1 cake: 1,000 TRY
- 2 cakes: 2,000 TRY
- 3 cakes: 3,000 TRY

## Tools and Technologies

- n8n
- AI Agent
- OpenRouter Chat Model
- Gmail
- Google Docs
- Google Drive
- Structured Output Parser
- JSON Workflow Export

## Repository Files

- `cake_order_quotation_automation_workflow.json` — Exported n8n workflow.
- `cake_order_n8n.png` — Workflow overview screenshot.
- `Pasta Teklifi Şablonu.docx` — Quotation template.
- `Pasta Teklifi.docx` — Sample quotation.

## Setup Instructions

1. Import the JSON workflow into n8n.
2. Configure your own Gmail, Google Docs, and Google Drive credentials.
3. Verify the quotation template and document-sharing permissions.
4. Test the workflow with sample emails before enabling automatic processing.

## Deliverables

- **Workflow JSON:** [View workflow file](./cake_order_quotation_automation_workflow.json)
- **Workflow Screenshot:** [View workflow image](./cake_order_n8n.png)
- **Quotation Template:** [Open Google Docs Template](https://docs.google.com/document/d/1Vr0Zd99QvUxvVN62EqPKS6BaG5isQltUA8AOll0ffdE/edit?usp=sharing)
- **Sample Quotation:** [Open Generated Quotation](https://docs.google.com/document/d/1TTyyDQMkTadcUZFQSyiXiJMdChNqcU64hT0zMDfeaSo/edit?usp=sharing)

## Project Purpose

This project was developed as part of the GoIT AI Automation training program to demonstrate email processing, AI-based data extraction, document generation, and workflow automation.

**Security Note:** Credentials, API keys, and private customer information should never be shared publicly.
