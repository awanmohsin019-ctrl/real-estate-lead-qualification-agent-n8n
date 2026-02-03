Real Estate Lead Qualification Agent (n8n + AI)

This repository contains an AI-assisted email automation workflow designed for real estate businesses that receive frequent property inquiries.

The workflow reads incoming inquiry emails, analyzes intent using AI, classifies the lead, and responds appropriately while preserving full control over communication flow.

The focus of this project is practical automation — designed to reflect how real estate agencies and consultants manage inbound leads in real operational environments.

Problem Context

Real estate teams often receive large volumes of inquiries related to:

Property purchases

Rental availability

General property information

Manually reviewing and responding to these emails slows response times and increases the risk of missing high-intent leads.

Solution Overview

This workflow automates the early-stage lead handling process by:

Monitoring incoming inquiry emails

Normalizing and preserving email metadata

Logging inquiries for record-keeping

Using AI to classify lead intent and urgency

Routing leads using conditional logic

Sending professional responses only where appropriate

AI is used selectively for classification and response drafting, while all workflow logic remains transparent and controllable.

Tools & Technologies

n8n – Workflow automation

Google Gemini – AI-powered text analysis and response drafting

Gmail – Email intake and responses

Google Sheets – Lead logging and audit trail

Workflow Design Principles

Clear separation between data handling and AI logic

Explicit field normalization to avoid undefined states

Defensive handling of AI outputs

Simple, maintainable routing logic

Intended Use Cases

Real estate agencies

Property consultants

Independent brokers

Lead management teams

This project represents a production-style approach to AI-assisted automation rather than a demo or experimental workflow.
