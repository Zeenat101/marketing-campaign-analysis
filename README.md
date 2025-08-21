# Marketing Campaign Analysis (Entry-Level Portfolio)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/Zeenat101/marketing-campaign-analysis/blob/main/Project_1_Campaign_Analysis.ipynb)

**Goal:** Turn raw channel data into actions (budget shifts + funnel fixes).  
**Dataset:** Synthetic, 1,200 sessions over ~90 days.  
**Tools:** Python (pandas, matplotlib) in Google Colab.

## TL;DR
- **Best paid channel by CPA:** TikTok / paid_social / remarketing — **CPA $3.27**, CR ≈ 10%.  
- **Biggest funnel leak:** Product → Cart ≈ **89.9%** drop.  
- **Impact estimate:** Shift $100 from Instagram paid social (CPA $5.91) to TikTok remarketing (CPA $3.27) → **~13–14 extra conversions** (small-scale assumption).

## Files
- `Project_1_Campaign_Analysis.ipynb` — full analysis notebook  
- `outputs/channel_summary.csv` — KPIs by source/medium/campaign  
- `outputs/funnel_summary.csv` — funnel counts by stage  
- `outputs/figures/cpa_by_channel.png`, `outputs/figures/conversion_rate_by_channel.png` — charts  
- **Brief (PDF):** [View / Download](./Campaign_Performance_Brief.pdf)

## Run it
Open in Colab (badge above) → **Runtime → Run all**. Results appear in `outputs/`.
