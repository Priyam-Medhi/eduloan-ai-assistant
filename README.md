# EduLoan AI Assistant

An AI-powered workflow automation system built using n8n to simplify the education loan application process for students.

## Problem Statement

Students often face delays in education loan processing due to incomplete documentation and repeated visits to banks. The process is time-consuming and lacks transparency.

## Solution

EduLoan AI Assistant automates document verification and application tracking by:

* Collecting student information through Google Forms
* Verifying uploaded documents
* Identifying missing paperwork
* Sending automated email notifications
* Maintaining a real-time dashboard

## Workflow Architecture

```text
Google Form
      ↓
Google Sheets Trigger
      ↓
Document Verification Engine
      ↓
 ┌─────────────┴─────────────┐
 ↓                           ↓
Send Status Email      Update Dashboard
```

## Features

* Automated document verification
* Missing document detection
* Email notifications
* Dashboard tracking
* Real-time application status updates

## Technologies Used

* n8n
* Google Forms
* Google Sheets
* Gmail
* JavaScript

## Installation

1. Clone the repository.
2. Import `workflow/EduLoan_AI_Assistant.json` into n8n.
3. Configure Google Sheets and Gmail credentials.
4. Run the workflow.

## Future Improvements

* OCR-based document extraction
* AI-powered loan eligibility estimation
* WhatsApp notifications
* Bank portal integration
* Student chatbot support

## Author

Priyam Medhi
B.Tech, Electronics and Communication Engineering
NIT Silchar

