# AGENTIC_AI: Financial and Web Search AI Agent

## Description
AGENTIC_AI is an advanced Python application leveraging AI models and tools to provide:
- **Financial Insights:** Analyze stock prices, summarize analyst recommendations, display company news, and offer historical financial data.
- **Web Search Capabilities:** Perform web searches using DuckDuckGo and present results with sources.

This project uses the **Groq** AI models for advanced analysis and interactive experiences.

## Features
- Summarize analyst recommendations.
- Provide the latest company news (e.g., NVIDIA, Apple).
- Format responses using Markdown with tables for clarity.
- Perform web searches and include sources in the responses.

## Technologies
- **Programming Language:** Python
- **Libraries/Tools:** 
  - `phidata` for AI agent creation
  - `yfinance` for financial data
  - `duckduckgo-search` for web searches
  - `fastapi` and `uvicorn` for the API
  - `python-dotenv` for environment variable management
  - `groq` for leveraging advanced Groq models

## Setup

### Prerequisites
- Python 3.8 or higher installed.
- Valid API keys for `phi.api` and `groq` API.

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd AGENTIC_AI
