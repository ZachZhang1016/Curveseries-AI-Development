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
