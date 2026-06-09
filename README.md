# AI-Powered-Recruitment-Automation-UiPath

## Overview

This project automates the recruitment process by evaluating candidate resumes against a job description using AI. The workflow extracts resume data, sends it to an AI model through OpenRouter API, scores candidates, shortlists suitable applicants, sends automated emails, and generates an Excel report.

## Features

* Resume PDF processing
* AI-based candidate evaluation
* Skill extraction and scoring
* Automatic shortlist/reject decision
* Duplicate candidate detection
* Automated email notifications
* Excel report generation
* Configurable interview details
* Threshold-based selection

## Technologies Used

* UiPath Studio
* OpenRouter API
* Meta Llama / Mistral AI Models
* Excel Automation
* Gmail Integration
* Regular Expressions

## Workflow

1. Read Job Description
2. Load Configuration Settings
3. Read Candidate Resumes
4. Extract Resume Text
5. Send Resume + JD to AI Model
6. Extract Candidate Score
7. Extract Candidate Email
8. Check Duplicate Candidates
9. Determine Candidate Status
10. Send Interview/Rejection Email
11. Store Results in Excel

## Configuration

The project uses a Config.xlsx file containing:

* API URL
* API Key
* Resume Folder
* Score Threshold
* Interview Date
* Interview Time
* Meeting Link

## Output

Generated Excel Report:

* Email
* Skills
* Score
* Status
* Interview Date
* Interview Time
* Meeting Link




