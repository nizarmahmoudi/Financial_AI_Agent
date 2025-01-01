# Financial_AI_Agent


## Description
The Financial AI Agent is a Python application that uses LLMs and tools to provide financial insights and web search capabilities. It includes:
- **Financial insights:** Analyze stocks, provide recommendations, display historical prices, and share company news.
- **Web search:** Search the web and include sources in responses.

## Features
- Summarize analyst recommendations.
- Provide the latest company news (e.g., for NVIDIA).
- Format responses in Markdown, using tables for better readability.

## Technologies
- **Programming Language:** Python
- **Libraries/Tools:** 
  - `phidata` for AI agent creation
  - `yfinance` for financial data
  - `duckduckgo-search` for web searches
  - `fastapi` and `uvicorn` for the API
  - `python-dotenv` for environment variable management

## Setup

### Prerequisites
- Python 3.8 or higher installed
- A valid API key for `phi.api`

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd financial_ai_agent
