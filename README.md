# Curveseries-AI-Development
Curveseries AI Development

graph TD
    MD[Market Data Agent] --> TA[Technical Analyst]
    MD --> FA[Fundamentals Analyst]
    MD --> SA[Sentiment Analyst]
    TA --> RM[Risk Manager]
    FA --> RM
    SA --> RM
    RM --> PM[Portfolio Manager]
    PM --> Decision[Final Decision]
