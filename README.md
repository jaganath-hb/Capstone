Team GenFlux

PROJECT 5 — Product Review “Sentiment & Action” Dashboard
Problem Statement
Organizations receive large volumes of product reviews (e-commerce, app stores, surveys). It's 
difficult to extract key issues, root causes, and actionable product improvements manually.
Goal Statement
Build an intelligent dashboard that clusters sentiment, identifies common themes, surfaces top 
customer pain points, and auto-suggests product improvements.
Core Features (Mandatory)
• Scrape or ingest product reviews (CSV or API)
• Review embeddings + sentiment classifier
• Theme clustering (LLM + vector clustering)
• Agent that proposes product improvements
• Dashboard (Streamlit/Flask/PowerBI-like)
• Observability: sentiment drift, topic distribution metrics
• Deploy via Azure App Service
• Guardrails: ignore "Spam" or "Bot" reviews that could skew the analytical data.
Stretch Features (Optional)
• Multi-language sentiment analysis
• Summaries by geography or customer-type segmentation
• Trend analysis (monthly/weekly)
• RAG over product manuals + known issues list
Implementation Guidance
• Use embeddings to group similar complaints
• LLM agent suggests improvements using prompts referencing cluster summaries
• Add App Insights to monitor sentiment distribution over time
