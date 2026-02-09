# Udemy n8n AI Agents

A comprehensive collection of n8n workflows demonstrating various AI agent implementations and automation patterns.

## Overview

This repository contains multiple n8n workflows showcasing different approaches to building AI-powered agents for tasks like email management, data processing, sentiment analysis, web scraping, and more.

## Workflows

### Email & Communication Agents
- **Email sending agent.json** - Automated email sending capabilities
- **Email Summary Agent.json** - AI-powered email summarization
- **Emails agent.json** - Email management and processing agent
- **Mails agent pinecone.json** - Email agent with Pinecone vector database integration
- **Mails to pinecone.json** - Email to Pinecone data pipeline
- **Filtering emails and auto-replying.json** - Email filtering and auto-response system
- **Send emails.json** - Email sending workflow

### RAG (Retrieval-Augmented Generation) Systems
- **RAG bot with pinecone.json** - RAG bot with Pinecone vector store
- **Company bot with RAG and leads recording.json** - Company bot with RAG and lead tracking
- **Workflow builder with RAG.json** - Dynamic workflow builder with RAG capabilities
- **Load data from drive to pinecone.json** - Data ingestion pipeline to Pinecone
- **Company google drive to pinecone.json** - Google Drive to Pinecone integration

### Specialized Agents
- **Calendar agent.json** - Calendar management and scheduling agent
- **Contact agent.json** - Contact management agent
- **Sentiment analysis.json** - Sentiment analysis workflow
- **Flowise :: Stock agent.json** - Stock information agent via Flowise integration

### Telegram Bots
- **Telegram bot.json** - Basic Telegram bot
- **Telegram bot 2.json** - Advanced Telegram bot
- **Telegram megabot.json** - Feature-rich Telegram bot
- **Telegram subworkflow search.json** - Telegram bot with subworkflow search capabilities

### Data Integration
- **Airtable.json** - Airtable integration workflow
- **Airtable to mail.json** - Airtable to email pipeline
- **Airtable to txt.json** - Airtable to text file export
- **Google sheets.json** - Google Sheets integration

### Web & Data Processing
- **Scrape HTML to markdown.json** - HTML scraping and markdown conversion

### Model-specific Workflows
- **Ollama.json** - Local model integration (Ollama)
- **MCP Claude desktop.json** - Model Context Protocol with Claude Desktop
- **MCP client.json** - MCP client implementation

### Other
- **LKD.json** - Linkedin workflow
- **Error trigger.json** - Error handling and trigger workflow

## Getting Started

1. Import the desired workflow JSON files into your n8n instance
2. Configure API keys and credentials as needed (Airtable, Gmail, Telegram, Pinecone, etc.)
3. Customize workflows based on your requirements
4. Deploy and activate workflows

## Prerequisites

- n8n instance (self-hosted or cloud)
- API credentials for integrated services (Gmail, Airtable, Pinecone, Telegram, etc.)
- For LLM features: Access to Claude, GPT, or local models (Ollama)

## Key Features

- **Email Automation** - Process, summarize, and respond to emails automatically
- **RAG Integration** - Vector database-based retrieval and generation workflows
- **Multi-platform Support** - Telegram, Google Sheets, Airtable integration
- **Agents** - Calendar, contact, and sentiment analysis agents
- **Data Pipelines** - Ingestion from Google Drive, Airtable, and other sources
- **Flexible Deployment** - Local or cloud-based models via Ollama/Flowise