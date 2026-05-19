🏏 CricketPulse AI
Where Cricket Meets Intelligence
> *An AI-powered analytics platform combining 17 years of IPL performance data with real-time news sentiment analysis — proposed to BCCI for data-driven franchise management and strategic decision making.*
---
📌 Business Problem Statement
BCCI and IPL franchises make multi-crore decisions — player auctions, media rights deals, sponsorship valuations — largely based on historical intuition rather than real-time data intelligence.
CricketPulse AI bridges this gap by connecting on-field performance data with off-field media sentiment to surface insights that drive smarter business decisions.
---
🎯 Project Overview
Detail	Info
Type	BA + AI Portfolio Project
Proposed To	Board of Control for Cricket in India (BCCI)
Data	1,095 IPL matches
Tools	Python
Duration	5 Weeks (Build in Public)
---
🚀 Key Insights Discovered
🏆 Performance Insights
Mumbai Indians lead all-time wins (144) but CSK projected wins without ban = 168 — surpassing MI as IPL's greatest franchise
Toss winning has virtually zero impact on match outcome (50.6% win rate) — contradicting conventional wisdom
Gujarat Titans have the highest win rate (62.22%) but near-zero media coverage — biggest untapped PR opportunity in IPL
Powerplay generates 29.7% of all runs in only 6 overs — highest runs-per-over phase = peak advertising value
🎙️ Sentiment Insights
89.9% of IPL news is positive or neutral — most brand-safe sports property for sponsors
Delhi Capitals face -0.88 sentiment despite 52.75% win rate — brand crisis threatening sponsorship renewals
International outlets cover IPL more positively (0.25 avg) than Indian outlets (0.04-0.09) — stronger global brand perception
Zero correlation between performance and sentiment — brand management matters more than winning
🏏 Player Insights
AB de Villiers leads Player of Match awards (25) despite ranking 7th in runs — highest impact per run scored
Context-adjusted analysis reveals finishers face half the balls of openers yet maintain equal strike rates — raw comparisons are misleading
AD Russell — 164.22 strike rate in 14.57 balls per innings — highest impact-per-ball in IPL history
---
📊 Dashboard Preview
Page	Content
📈 IPL Overview	Team wins, toss analysis, season trends
🏏 Player Analysis	Top batsmen, bowlers, role-based metrics
🤖 Sentiment Analysis	Real-time news sentiment by source and team
💛 CSK Special	Complete franchise analysis + ban impact
---
🛠️ Tech Stack
Purpose	Tool
Data Analysis	Python (pandas, numpy)
Visualization	matplotlib, seaborn
Sentiment Analysis	TextBlob, NewsAPI
Dashboard	Power BI (DAX)
Notebook	Jupyter Notebook
Documentation	Business Requirements Document (BRD)
---
📂 Project Structure
```
CricketPulse-AI/
│
├── README.md
├── requirements.txt
│
├── notebooks/
│   ├── 01_Data_Exploration.ipynb
│   ├── 02_Cricket_Analysis.ipynb
│   ├── 03_News_Sentiment_Analysis.ipynb
│   └── 04_Combined_Analysis.ipynb
│
├── data/
│   ├── matches_cleaned.csv
│   ├── deliveries_cleaned.csv
│   ├── cricket_news_sentiment.csv
│   └── batting_comparison.csv
│
├── reports/
│   ├── [16 analysis charts]
│   ├── BRD-CricketPulse-AI-BCCI.pdf
│   └── CricketPulse-AI-Dashboard.pdf
│
└── dashboard/
    └── CricketPulse-AI-Dashboard.pbix
```
---
⚙️ How To Run
Prerequisites
```bash
pip install pandas numpy matplotlib seaborn textblob newsapi-python requests
```
Steps
Clone the repository
```bash
git clone https://github.com/Shrutikpandey/CricketPulse-AI.git
```
Navigate to notebooks folder and open Jupyter
```bash
jupyter notebook
```
Run notebooks in order:
`01_Data_Exploration.ipynb`
`02_Cricket_Analysis.ipynb`
`03_News_Sentiment_Analysis.ipynb` (requires NewsAPI key)
`04_Combined_Analysis.ipynb`
Add your NewsAPI key in `03_News_Sentiment_Analysis.ipynb`:
```python
API_KEY = "YOUR_API_KEY_HERE"
```
---
📋 BA Artifacts Produced
✅ Business Requirements Document (BRD)
✅ Stakeholder Analysis
✅ As-Is / To-Be Process Mapping
✅ Gap Analysis
✅ Functional & Non-Functional Requirements
✅ Risk Analysis
✅ Business Recommendations with Success Metrics
✅ Power BI Interactive Dashboard
---
💡 Key BA Skills Demonstrated
Requirements Elicitation — Translated raw data findings into structured business requirements
Stakeholder Analysis — Mapped BCCI, franchise owners, broadcasters, and sponsors
Gap Analysis — Identified current vs desired state across 5 decision areas
Data Storytelling — Converted 260,920 delivery records into boardroom-ready insights
Prioritized Recommendations — Ranked actions by business impact and feasibility
Risk Analysis — Identified 5 key risks with mitigation strategies
---
📣 Build In Public Journey
This project was built and shared publicly on LinkedIn over 5 weeks:
Week	Post	Milestone
Week 1	Project Launch	Problem statement defined
Week 2	IPL Insights	Cricket analysis complete
Week 3	AI Sentiment	News analysis complete
Week 4	Dashboard	Power BI complete
Week 5	BRD + Full Reveal	Project complete
---
⚠️ Data Note
Raw deliveries data not included due to file size (260,920 rows). Cleaned CSV files are provided. Original data available at Kaggle IPL Dataset.
Note: Rebranded franchises (Delhi, Punjab, Hyderabad, RCB) consolidated under current team names for franchise-level analysis.
---
👤 About
Shruti Kumari Pandey | Aspiring Business Analyst | Mumbai
📧 shrutipaandey@gmail.com
🔗 LinkedIn
🐙 GitHub
---
This project was built as part of a BA portfolio to demonstrate end-to-end business analysis skills — from raw data to boardroom-ready recommendations.
