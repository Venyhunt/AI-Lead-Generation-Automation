 AI-Powered Lead Generation & Outreach Workflow
Overview

This project demonstrates a scalable AI-powered lead generation and personalized outreach automation built using n8n.

The workflow automates:

Lead ingestion via Apify

Domain validation and extraction

Website scraping

AI-generated business summarization

Multi-step personalized email sequence generation

Error logging and execution tracking

API cost comparison and scalability analysis

 Architecture Overview

Describe the phases clearly:

Lead Ingestion (Apify API)

Domain Extraction & Validation

Website Scraping & AI Summarization

Personalized 3-Step Email Sequence Generation

Error Logging & Status Tracking

Cost & Model Comparison Analysis

 Technologies Used

n8n (Workflow Automation)

Apify API (Lead scraping)

OpenAI GPT-3.5 Turbo (Production email generation)

Google Gemini 2.5 Flash (Development comparison)

Google Sheets API (Data storage & logs)

 Model Comparison

Summarize:

Gemini used during development

Hit 20 request/day free-tier cap

Switched to GPT-3.5 Turbo for scalability

GPT required fewer tokens and produced more stable JSON

 Cost Efficiency

Estimated cost for 100 leads:

Under $1 total API cost

Demonstrates high scalability and efficient token usage.

 Error Handling Features

Skips invalid domains

Logs scraping failures

Captures AI JSON parsing errors

Continues execution without crashing

 Files Included

n8n workflow export (.json)

API Pricing & Justification document

Model comparison sheet

Excel execution results

 Future Improvements

Batch processing & rate limiting

Queue-based architecture

CRM integration

Deployment to n8n cloud

Webhook trigger endpoint
