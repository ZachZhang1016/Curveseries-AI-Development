# Curveseries-AI-Development
Curveseries AI Development

```mermaid
graph TD
    MD[Market Data Analyst] --> TA[Technical Analyst]
    MD --> FA[Fundamentals Analyst]
    MD --> SA[Sentiment Analyst]
    TA --> RM[Risk Manager]
    FA --> RM
    SA --> RM
    RM --> PM[Portfolio Manager]
    PM --> Decision[Final Decision]

Agent Descriptions
Market Data Agent

Gathers historical price data from yfinance
Collects financial metrics and statements
Preprocesses data for other agents
Technical Analyst

Analyzes price trends and patterns
Calculates technical indicators
Generates technical trading signals
Fundamentals Analyst

Evaluates company financial health
Analyzes growth metrics
Provides fundamental analysis signals
Sentiment Analyst

Fetches news from AlphaVantage
Analyzes news sentiment using Gemini
Generates sentiment-based signals
Risk Manager

Integrates signals from all analysts
Evaluates potential risks
Sets position limits
Provides risk-adjusted recommendations
Portfolio Manager

Makes final trading decisions
Manages position sizing
Balances risk and reward
Generates executable orders
Workflow
Market Data Agent collects all necessary data
Three analysts (Technical, Fundamental, Sentiment) work in parallel
Risk Manager combines and evaluates all signals
Portfolio Manager makes the final decision
