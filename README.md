# CEO Financial Command Center

Interactive executive financial dashboard for a global PC & Printer manufacturer, built with **Streamlit** and **Plotly**.

## Local Development

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
streamlit run app.py
```

## Deploy to Streamlit Cloud

1. Push this repo to GitHub
2. Go to [share.streamlit.io](https://share.streamlit.io)
3. Connect your GitHub repo
4. Set **Main file path** to `app.py`
5. Deploy

The app will be available at `https://<your-app>.streamlit.app`

## Features

- 4 KPI cards (Revenue, Gross Margin, FCF, Cash Conversion Cycle)
- Revenue & Margin trend line chart
- Personal Systems volume vs. value scatter plot
- Printing segment revenue mix (stacked bar)
- FX impact waterfall bridge
- Geographic profitability heatmap
- Top 5 DIO inventory drag table
- Dynamic executive narrative with alert flags
- Sidebar filters: Region, Fiscal Year, Business Segment, Currency View
