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


## Agent Descriptions

1. **Market Data Agent**

   - Gathers historical price data from yfinance
   - Collects financial metrics and statements
   - Preprocesses data for other agents

2. **Technical Analyst**

   - Analyzes price trends and patterns
   - Calculates technical indicators
   - Generates technical trading signals

3. **Fundamentals Analyst**

   - Evaluates company financial health
   - Analyzes growth metrics
   - Provides fundamental analysis signals

4. **Sentiment Analyst**

   - Fetches news from AlphaVantage
   - Analyzes news sentiment using Gemini
   - Generates sentiment-based signals

5. **Risk Manager**

   - Integrates signals from all analysts
   - Evaluates potential risks
   - Sets position limits
   - Provides risk-adjusted recommendations

6. **Portfolio Manager**
   - Makes final trading decisions
   - Manages position sizing
   - Balances risk and reward
   - Generates executable orders

### Workflow

1. Market Data Agent collects all necessary data
2. Three analysts (Technical, Fundamental, Sentiment) work in parallel
3. Risk Manager combines and evaluates all signals
4. Portfolio Manager makes the final decision
