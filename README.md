## 📌 Project Context

This project explores the relationship between trader behavior and overall market sentiment in the Bitcoin cryptocurrency market. The primary focus is on how traders’ performance — such as profitability (PnL), trade volume, and risk exposure — aligns with or diverges from shifts in market psychology as captured by the **Bitcoin Fear & Greed Index**.

The **Fear & Greed Index** is a widely used market sentiment indicator that suggests the dominant mood in the crypto market at a given time. It aggregates multiple market signals — including price volatility, trading volume, social media sentiment, market dominance, and search trends — and outputs a value on a scale from 0 to 100. Lower values indicate *fear* (pessimism and risk aversion), while higher values indicate *greed* (optimism and increased risk‑taking). :contentReference[oaicite:0]{index=0}

The objective of this analysis is to integrate two datasets:
1. **Historical Trader Data from Hyperliquid** — individual trade records including account, execution price, trade size, side (buy/sell), closed profit/loss (PnL), leverage, timestamps, and other trade details.
2. **Bitcoin Market Sentiment Data** — daily sentiment classifications based on the Fear & Greed Index, which encapsulate market mood into categories such as “Fear” and “Greed.”

By merging these datasets on common dates, this project aims to uncover patterns and insights surrounding trader behavior under different sentiment regimes. For example, do traders perform better when the market is greedy compared to fearful? Does higher trading activity and higher leverage align with optimistic markets? These insights are intended to help inform smarter trading strategies in a Web3 context.

This analysis was performed using Python data science libraries (Pandas, Matplotlib, Seaborn) in **Google Colab**, and all code, visual outputs, and narrative summaries are included in this repository to enable reproducibility and clear interpretation of results.
