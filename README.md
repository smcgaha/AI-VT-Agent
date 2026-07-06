# 🛡️ AI-VT-Agent

**VirusTotal Threat Intelligence Agent** built with Azure AI Foundry + MCP.

A secure web application that lets you chat with an AI agent powered by Azure AI Foundry and VirusTotal for real-time threat intelligence on IPs, domains, URLs, and file hashes.

## Features

- Chat with AI Agent
- File upload + automatic hash scanning (SHA-256)
- Persistent Azure AI Foundry Agent
- Docker support
- Ready for Azure Container Apps with Azure AD authentication

## Quick Start

```bash
cp .env.example .env
# Fill in your Azure and MCP details
pip install -r requirements.txt
streamlit run app.py
