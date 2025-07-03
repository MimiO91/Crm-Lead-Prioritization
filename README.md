# Lead Scoring CRM Dashboard

This project simulates how a CRM or account manager can use Python to score and prioritize leads. The scoring model is based on key factors like engagement, recency, deal size, and lifecycle stage. It is fully transparent, customizable, and meant to help teams decide who to contact next—and why.

## 🔍 Key Features

- Weighted lead scoring (engagement, deal size, activity, lifecycle stage)
- Next-best-action suggestions (e.g., Call, Email, Nurture)
- Segment summaries by lifecycle and region
- Interactive filtering (via ipywidgets)
- Business-ready visualizations (Plotly)
- Funnel drop-off chart to identify conversion bottlenecks

## 📊 Sample Insights

- SQLs score highest, but MQLs show strong potential in some regions
- Regions like Île-de-France and PACA lead in average quality
- Funnel view shows volume drop-off from MQL → SQL stage
- Territory-specific rankings help regional sales planning

## 📁 File Structure

```
lead-scoring-crm-dashboard/
│
├── Lead_Scoring_CRM_Colab_Notebook.ipynb
├── data/
│   └── leads_dataset.csv
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

## 🚀 How to Use

1. Open the notebook in Google Colab or locally
2. Upload your own CRM-style dataset if needed
3. Run all cells to score leads and explore insights
4. Customize scoring logic to match your sales strategy

## 📎 Open in Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1KuXIzjJct5sdK3t62nd6JGTVgvFW0BWP)
