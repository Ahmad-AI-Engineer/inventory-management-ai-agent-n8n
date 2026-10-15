# Inventory Management AI Agent

## Overview

This project is an n8n-based AI agent for inventory management and sales logging.

The agent uses a conversational interface to read inventory information, update stock levels, and record completed sales in Google Sheets.

## Business Purpose

The goal of this project is to provide a lightweight AI-assisted inventory management system for small teams and businesses.

Instead of manually checking stock quantities or recording sales, users can interact with the AI agent using natural language.

The agent then performs the required inventory or sales operation using connected Google Sheets tools.

## Workflow File

```text
workflows/inventory-management-ai-agent.json

Main Workflow

User Message
     ↓
n8n Chat Trigger
     ↓
AI Agent
     ↓
Mistral Cloud Chat Model
     ↓
Inventory / Sales Decision
     ↓
Google Sheets Tools
     ↓
Inventory Update or Sales Log
     ↓
Response to Users