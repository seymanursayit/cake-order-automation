# Cake Order Quotation Automation

## Overview
An AI-powered email automation workflow built with n8n to process customer cake orders and generate personalized quotations.

## Workflow
1. Gmail Trigger detects incoming emails.
2. AI Agent analyzes emails and extracts cake order details.
3. If node checks whether the email contains a cake order request.
4. Google Docs creates and updates the quotation document.
5. Google Drive shares the document.
6. Gmail sends the quotation link to the customer.

## Pricing
Each cake costs 1,000 TRY.

**Formula:** Total Price = Number of Cakes × 1,000 TRY

- 1 cake: 1,000 TRY
- 2 cakes: 2,000 TRY
- 3 cakes: 3,000 TRY

## Tools
- n8n
- AI Agent
- OpenRouter
- Gmail
- Google Docs
- Google Drive

## Files
- `cake_order_quotation_automation_workflow.json` — Exported workflow.

## Setup
1. Import the JSON workflow into n8n.
2. Configure your own Google and Gmail credentials.
3. Verify the quotation template and sharing permissions.
4. Test the workflow with sample emails.

## Project Purpose
Created as part of the GoIT AI Automation training program.

**Note:** Credentials and API keys should never be shared publicly.**


## Deliverables

- **Workflow JSON:** `cake_order_quotation_automation_workflow.json`
- **Quotation Template:** [Open Google Docs Template](https://docs.google.com/document/d/1Vr0Zd99QvUxvVN62EqPKS6BaG5isQltUA8AOll0ffdE/edit?usp=sharing)
- **Sample Quotation:** [Open Generated Quotation](https://docs.google.com/document/d/1TTyyDQMkTadcUZFQSyiXiJMdChNqcU64hT0zMDfeaSo/edit?usp=sharing)
- **Workflow Screenshot:** `cake_order_n8n.png`
