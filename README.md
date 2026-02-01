

![n8n](https://img.shields.io/badge/n8n-workflow-0EA5E9)
![license](https://img.shields.io/badge/license-MIT-green)
![status](https://img.shields.io/badge/status-ready-brightgreen)

# Monitor Google Maps Reviews with GPT-4o Sentiment Analysis & Telegram RAG Agent using Pinecone

Advanced n8n automation for Monitor Google Maps Reviews with GPT-4o Sentiment Analysis & Telegram RAG Agent using Pinecone.

## Overview
- Category: Market Research, AI RAG
- Complexity: advanced
- Source: n8n workflow template export

## What This Automation Does
Automate Google Maps review management with AI sentiment analysis, Telegram notifications, and Pinecone integration. Boost your brand reputation today!

## Included Files
- `workflow.json`

## Setup
1. Import `workflow.json` into n8n.
2. Configure required credentials for the services used in the workflow nodes.
3. Update any environment variables or static values inside nodes (API keys, URLs, IDs).
4. Run a test execution and then activate the workflow.

## Tech Stack

- `@n8n/n8n-nodes-langchain.agent`
- `@n8n/n8n-nodes-langchain.documentDefaultDataLoader`
- `@n8n/n8n-nodes-langchain.embeddingsOpenAi`
- `@n8n/n8n-nodes-langchain.lmChatOpenAi`
- `@n8n/n8n-nodes-langchain.outputParserStructured`
- `@n8n/n8n-nodes-langchain.vectorStorePinecone`
- `n8n-nodes-base.aggregate`
- `n8n-nodes-base.googleSheets`
- `n8n-nodes-base.httpRequest`
- `n8n-nodes-base.manualTrigger`
- `n8n-nodes-base.scheduleTrigger`
- `n8n-nodes-base.set`
- `n8n-nodes-base.splitInBatches`
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.telegram`
- `n8n-nodes-base.telegramTrigger`
- `n8n-nodes-base.wait`

## Author

Murtaza Baig

## License
MIT License. See `LICENSE`.