# Marketing Campaign Analysis (Entry-Level Portfolio)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Zeenat101/marketing-campaign-analysis/blob/main/Practice_Project_Campaign_Analysis.ipynb)

Turn raw channel data into **actions** (budget shifts + funnel fixes) with Python in Colab.  
**Dataset:** synthetic, ~1,200 sessions over ~90 days.

## TL;DR (30-sec skim)
- **$3.27 CPA** (TikTok remarketing) → **shift** budget from Instagram (**$5.91 CPA**).
- **89.9% drop** at Product→Cart → **add** above-the-fold CTA + early shipping/returns + social proof.
- **~13–14 extra conversions** per **$100** reallocated (TikTok vs Instagram) — small-scale estimate.

<p align="center">
  <img src="outputs/figures/cpa_by_channel.png" alt="Top 10 channels by lowest CPA" width="600"><br>
  <em>Top 10 channels by lowest CPA</em>
</p>

## What’s inside
- `Practice_Project_Campaign_Analysis.ipynb` — full, runnable analysis notebook  
- `outputs/channel_summary.csv` — KPIs by source/medium/campaign  
- `outputs/funnel_summary.csv` — funnel counts by stage  
- `outputs/figures/cpa_by_channel.png`, `outputs/figures/conversion_rate_by_channel.png` — charts  
- **Brief (PDF):** [View / Download](./insight-brief-campaign-performance.pdf)

## Key findings
- **$3.27 CPA** on TikTok / paid_social / remarketing — **shift** small budget from Instagram (**$5.91 CPA**); monitor frequency & incremental lift over **1–2 weeks**.
- **89.9% drop** at **Product → Cart** — **add** primary CTA above the fold; **show** shipping/returns early; **add** reviews/trust badges.
- **11.1% CR** on **Google CPC (newsletter)** — **expand** keyword/ad-copy; **test** landing-page alignment.
- **$3.80 CPA** on **Google Brand Search (spring_sale)** — **maintain** spend; **test** fresh creatives/copy for scalable volume.

## Run it (Colab)
1. Open the notebook via the badge above.  
2. **Runtime → Run all.**  
3. Results are written to `outputs/`.

## Requirements
- pandas
- numpy
- matplotlib

## Data & definitions
- **Qualified session:** ≥2 pages or add-to-cart  
- **CPA:** total cost ÷ purchases  
- **Note:** synthetic data; this project demonstrates workflow + communication.

## Next steps
- A/B test product-page CTA + shipping/returns messaging to reduce Product→Cart drop.  
- Simplify checkout (wallets, fewer fields) to reduce Checkout→Purchase drop.  
- Add a simple weekly pipeline to refresh the KPIs + brief.

## License
This project is licensed under the [MIT License](./LICENSE) — feel free to reuse with attribution.

---

*Made in Python (pandas, matplotlib) on Google Colab.*
