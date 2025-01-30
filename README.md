# Stocks Analysis AI Agents

This is a web application built with **Streamlit**, **Plotly**, and **YFinance** to analyze stock data using AI agents. The app provides real-time stock data, historical price charts, and financial insights for various stocks. It uses AI agents to search the web for relevant information and provide financial insights.

## Features

- **Stock Price and Financial Data**: Fetches real-time stock data including current price, forward P/E ratio, and recommendations.
- **Stock Price Movement Chart**: Displays a candlestick chart showing the historical price movement of a stock over the past year.
- **Company Overview**: Provides a summary of the company’s business.
- **AI Agents**: 
  - Web Search Agent: Searches the web for additional information on stocks.
  - Financial AI Agent: Analyzes stock data and provides financial insights.
  - Stock Market Agent: Integrates both agents to offer stock market analysis.

## Technologies Used

- **Streamlit**: For building the web interface.
- **Plotly**: For interactive visualizations (candlestick chart).
- **YFinance**: For fetching stock data from Yahoo Finance.
- **PHI (Groq)**: For leveraging AI agents to provide advanced analysis and search capabilities.
- **Python-dotenv**: For loading environment variables such as API keys.

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/stocks-analysis-ai-agents.git
   cd stocks-analysis-ai-agents
   ```
2.Install the required dependencies:

```bash
pip install -r requirements.txt
```
Set up environment variables by creating a .env file in the root directory with the following content:

GROQ_API_KEY=your_groq_api_key_here

Run the application:

```bash
streamlit run app.py
```
Usage

- Open the web app in your browser.

- Enter the company name (e.g., APPLE, TCS) in the input field.

- Click Analyze to get real-time stock data and insights.

- View the stock price chart, financial data, and company overview.

- Common Stock Symbols

- You can enter one of the following stock names:

NVIDIA: NVDA

APPLE: AAPL

GOOGLE: GOOGL

MICROSOFT: MSFT

TESLA: TSLA

AMAZON: AMZN

META: META

NETFLIX: NFLX

TCS: TCS.NS

RELIANCE: RELIANCE.NS

INFOSYS: INFY.NS

WIPRO: WIPRO.NS

HDFC: HDFCBANK.NS

TATAMOTORS: TATAMOTORS.NS

ICICIBANK: ICICIBANK.NS

SBIN: SBIN.NS

## Contributing

- Feel free to fork the repository and submit issues or pull requests for any improvements.

## License

- This project is licensed under the MIT License - see the LICENSE file for details.

- This `README.md` covers everything related to the project including features, technologies, installation steps, usage instructions, and contribution guidelines.
