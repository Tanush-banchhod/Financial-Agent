# Agentic AI Project: Financial AI Assistant 🤖  

This project demonstrates the implementation of Agentic AI using Phidata, where multiple agents work autonomously to achieve specific business outcomes.  

## Features  
- **Web Search Agent**: Searches the web for information using DuckDuckGo and Groq's Llama model.  
- **Finance AI Agent**: Fetches financial data like stock prices, analyst recommendations, company news, and fundamentals using YFinanceTools.  

## How It Works  
1. **Web Search Agent** gathers relevant insights from the web.  
2. **Finance AI Agent** collects and formats financial data in tables.  
3. Both agents collaborate to provide actionable insights autonomously.  

## Installation  

1. Clone the repository:  
   ```bash
     git clone https://github.com/Tanush-banchhod/agentic-ai-project.git
     cd Financial-Agent
    ```
2. Create a virtual environment:
   ```bash
      python -m venv venv
      source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```   
3. Install dependencies: 
   ```bash
      pip install -r requirements.txt
    ```
4. Set up your environment variables:
   - Create a .env file in the root directory with your PHI_API_KEY and GROQ_API_KEY.
     
5. Run the application:
   ```bash
      python financial_agent.py
    ```







   
