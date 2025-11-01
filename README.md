# n8n-API-data-analysis-workflow

Overview

This workflow retrieves data from an external API, processes it, formats the output, and sends the final report by email. It runs automatically on a defined schedule and does not require manual triggering once activated.

Workflow Steps

Schedule Trigger – Sets when the workflow runs (e.g., daily).

HTTP Request – Retrieves data from the target API.

Code Node (Extraction) – Filters and restructures the raw response.

Code Node (Formatting) – Builds the final report message.

Send Email – Delivers the formatted output to the configured recipient.

Import Instructions

In n8n, go to Workflows → Import from File

Upload the provided .json file

Add your API and email credentials

Activate the workflow

Requirements

n8n instance (self-hosted or cloud)

Valid API endpoint

SMTP credentials for email delivery
