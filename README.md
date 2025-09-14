# FitBuzz — Trend Analysis of Wearable Health Devices

FitBuzz is a web-based platform that analyzes market trends, usage patterns, and public sentiment around wearable health devices (smartwatches, fitness bands, etc.) with a focus on the Indian market. The project integrates data collection, ML-driven sentiment & trend analysis, and interactive visualizations to help researchers, product teams, and consumers make data-driven decisions.


## Project Overview
FitBuzz collects and analyzes user reviews, marketplace data, and device telemetry (where available) from multiple sources to provide:

- **Usage analysis** across demographics (age, gender, location, occupation)  
- **Market-level trend detection** (brand adoption, growth signals)  
- **Sentiment analysis** on reviews and social media mentions  
- **Interactive dashboards** to explore and compare brands/models  

## Key Features
- **Sentiment Analysis** (rule-based + ML/BERT options)  
- **Trend Detection** and time-series summaries (brand-level & category-level)  
- **Demographic Segmentation** for targeted insights  
- **Comparative Brand Dashboard** with ratings, sentiment distribution, and adoption curves  
- **Exportable Reports**: PDF/CSV summaries for stakeholders  
- **Scalable Data Pipeline** design (collector → preprocess → store → analyze → visualize)  


## Architecture & Tech Stack

### Frontend
- React + Vite  
- Tailwind CSS / Material UI  
- Recharts / D3.js for visualizations  

### Backend & APIs
- Flask / FastAPI  
- REST APIs serving processed analytics  

### Data & Schema
**Data Sources (examples):**
- Survey Responses
- E-commerce product reviews (publicly available pages / scraped datasets)  
- Social media mentions (Twitter/X, public forums)  
- Public/academic datasets on wearables  
  
