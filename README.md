# Curveseries-AI-Development
Curveseries AI Development

```mermaid
graph TD
    Data[Data Agent] -->|JODI/EIA| TA[Technical Agent]
    Data -->|ICE Futures| FA[Fundamental Agent]
    Data -->|News/Social| SA[Sentiment Agent]
    TA --> RM[Risk Manager]
    FA --> RM
    SA --> RM
    RM --> Chatbot[AI Chatbot]
    Chatbot --> User[Stakeholders]
