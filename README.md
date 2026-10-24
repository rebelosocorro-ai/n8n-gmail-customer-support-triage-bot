# n8n-gmail-customer-support-triage-bot
An AI-powered customer support automation built with n8n, Gmail, OpenAI and Google Sheets. Uses a Gmail Trigger to process incoming emails, an AI Agent with memory to assist with triage, and integrations to record information and send email responses.


# AI Customer Support Triage Bot — Gmail Automation with n8n

## Project Overview

The **AI Customer Support Triage Bot** is an AI-powered email automation workflow built with **n8n, Gmail, OpenAI and Google Sheets**.

This project upgrades a chat-triggered customer support bot to use a **Gmail Trigger**, enabling the workflow to listen for incoming emails and initiate the AI-powered support process automatically.

The AI Agent uses an OpenAI Chat Model and Simple Memory, with Google Sheets and Gmail integrations to support information recording and email communication.

## Project Objectives

- Automate the intake of customer support emails.
- Use an AI Agent to process incoming email content according to its configured instructions.
- Maintain conversational context using Simple Memory.
- Record relevant information in Google Sheets.
- Enable email communication through Gmail.
- Demonstrate practical AI agent development and workflow automation using n8n.

## Workflow Architecture

The workflow follows this general sequence:

1. **Gmail Trigger:** Detects incoming emails according to the configured trigger settings.
2. **AI Agent:** Processes the incoming email using the configured instructions.
3. **OpenAI Chat Model:** Provides the language model capabilities for the AI Agent.
4. **Simple Memory:** Supports conversational context.
5. **Google Sheets Tool:** Appends relevant information to a spreadsheet.
6. **Gmail Tool:** Sends email messages through the connected Gmail account.

The AI Agent coordinates the connected model, memory and tools according to the workflow configuration.

## Technology Stack

- **n8n** — Workflow automation and orchestration
- **Gmail** — Incoming email trigger and outgoing email communication
- **OpenAI Chat Model** — AI-powered text processing
- **Simple Memory** — Context retention
- **Google Sheets** — Information recording and tracking

## Key Features

- Email-triggered automation
- AI Agent integration
- Connected language model and memory
- Google Sheets integration
- Gmail messaging integration
- Automated workflow execution
- Integration of multiple services into a single workflow

## How to Set Up

### Prerequisites

Before running this workflow, you will need:

- An n8n account or local n8n installation
- A Gmail account and the required Gmail credentials
- An OpenAI API account and API key
- A Google Sheets document
- Appropriate permissions for the connected Google services

### Installation Steps

1. Clone or download this repository.
2. Open your n8n instance.
3. Import the workflow JSON file, if included in the repository.
4. Configure the Gmail Trigger and connect the appropriate Gmail account.
5. Configure the OpenAI Chat Model with valid credentials.
6. Configure Simple Memory.
7. Connect the Google Sheets Tool to your spreadsheet.
8. Configure the Gmail Tool for outgoing email communication.
9. Review the AI Agent instructions and ensure they match your intended customer support process.
10. Test the workflow using a new email sent from a separate email account.
11. Review the execution history and verify that the expected actions occur.
12. Publish the workflow and confirm that it processes incoming emails automatically.

**Note:** The workflow must be configured with valid credentials and service permissions before it can run successfully.

## Testing

The workflow can be tested by sending a new email to the Gmail account connected to the Gmail Trigger.

Check the following:

- The incoming email triggers a workflow execution.
- The AI Agent processes the email.
- The connected tools perform their configured actions.
- Relevant information is recorded in Google Sheets.
- Email communication works as intended.
- The workflow execution completes without errors.

Actual results depend on the workflow configuration, AI Agent instructions and connected service permissions.

## Security and Privacy

- Never upload API keys, passwords, OAuth tokens or other credentials to GitHub.
- Do not include customer emails or personal information in public examples.
- Review exported n8n workflow JSON files before publishing them.
- Use appropriate permissions for Gmail and Google Sheets.
- Test email automation with non-sensitive messages before using it in a live environment.

## Learning Outcomes

This project demonstrates practical experience with:

- AI agent development
- No-code and low-code automation
- Event-driven workflow design
- Email automation
- Large Language Model integration
- Memory and tool integration
- Google Workspace integrations
- Workflow testing and troubleshooting
- Building practical AI solutions for business processes

## Future Improvements

Potential enhancements include:

- Email categorisation and priority assignment
- Urgency and sentiment detection
- Escalation of complex enquiries to human support staff
- Improved error handling and execution monitoring
- Customer support reporting dashboards
- Response approval before sending emails
- Integration with a customer relationship management system

These are potential future enhancements and are not necessarily implemented in the current workflow.

## Author

**Socorro Rebelo**

Data Scientist | Microsoft IT Support Specialist | Generative AI Specialist

This project is part of my practical learning and development in AI automation, AI agents and business process automation.

---

*Built with n8n, Gmail, OpenAI and Google Sheets.*
