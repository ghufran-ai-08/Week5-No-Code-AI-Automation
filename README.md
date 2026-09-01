# AI Customer Support Automation

## Week 5 — No-Code AI Automation

### Neuro Five Solutions | Generative AI & Prompt Engineering Internship

This project demonstrates a no-code AI automation workflow that
connects a real customer-support form submission to Google Gemini
and Gmail.

The automation automatically processes customer requests, uses AI
to categorize and summarize them, drafts a support response, and
delivers the result by email.

---

# Workflow

```text
Customer submits Google Form
             ↓
      Google Sheets
             ↓
       Make Trigger
             ↓
        Google Gemini
             ↓
   AI Support Analysis
             ↓
           Gmail
             ↓
     Email Delivered


# AI Processing

Gemini performs four tasks:

Categorizes the customer issue
Determines urgency
Summarizes the request
Drafts a professional support response
Trigger

The workflow is triggered when a new response row appears in the
Google Sheets spreadsheet connected to the Google Form.

# Final Action

After Gemini processes the request, the AI-generated analysis is
passed to Gmail.

Gmail then sends the result as an email.

# Test Scenarios

The workflow was tested using three separate customer-support
requests:

Test 1 — Technical

An application crashes when a customer attempts to upload a PDF.

Test 2 — Billing

A customer reports being charged twice for the same subscription.

Test 3 — Delivery

A customer reports that an expected delivery has not arrived.

All three tests were processed through the complete automation.

Technologies
Google Forms
Google Sheets
Make
Google Gemini
Gmail
Prompt Engineering
No-Code AI Automation
Key Learning

This project demonstrates how Generative AI can be connected to a
real business workflow using no-code automation.

The key architecture is:

Trigger → AI Processing → Action

The project shows how an organization could automate repetitive
support workflows while keeping the AI processing step separate
from the trigger and final communication stages.

# Project Structure

Week5-No-Code-AI-Automation/
│
├── docs/
│   └── test-results.md
│
├── screenshots/
│
├── video/
│
├── README.md
├── workflow.md
└── .gitignore

# Security

API credentials and private authentication information are not stored
in this repository.

The Make connection handles the required service credentials.


Author

Muhammad Ghufran

Generative AI & Prompt Engineering Intern

Neuro Five Solutions