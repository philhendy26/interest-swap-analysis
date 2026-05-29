# interest-swap-analysis

Interest Rate Swap Analysis: Fictitious Project

Project Name: Thames Valley Solar Farm Expansion

Description: A £250 million renewable energy project to expand a solar farm in Berkshire, UK. 

Construction begins in Q3 2026 and lasts 18 months. 

The project will be financed with a mix of equity and floating-rate debt tied to SONIA + 1.50% margin.

Objective: Analyze the use of Interest Rate Swaps (IRS) to hedge interest rate risk using 2Y, 5Y, and 10Y tenors, based on current UK market rates (as of May 29, 2026).

Current Market Rates (May 29, 2026)

TenorGilt YieldSONIA Swap Rate (Fixed)Spread (Swap vs Gilt)2-Year4.30%4.18%+12 bps5-Year4.25%4.17%-8 bps10-Year4.78%4.44%-34 bps
Bank of England Base Rate: 3.75% (held steady with potential upside risks due to geopolitical energy price pressures).

Swap Strategy for the Project

The company plans to draw £180 million in floating-rate debt (SONIA + 150 bps). Without hedging, debt cost floats with SONIA. They want to pay fixed via swaps to lock in predictable costs for better budgeting and investor confidence.
Three Swap Scenarios

Short-term hedge (2Y Swap) – Matches early construction phase
Medium-term hedge (5Y Swap) – Covers full construction + early operations
Long-term hedge (10Y Swap) – Full project life cycle protection


## Sample Output

2Y Swap locks in ~4.18% fixed → All-in debt cost ≈ 5.68%
5Y Swap locks in ~4.17% fixed → All-in ≈ 5.67%
10Y Swap locks in 4.44% fixed → All-in ≈ 5.94%

Key Insights & Recommendation
Curve Shape: Mildly humped. The 5-year swap rate is the lowest, suggesting the market expects moderate BoE easing in the medium term followed by normalization.
Risk Analysis:

Floating Rate Risk: High — SONIA could rise to 5%+ if energy inflation persists.
Swap Break Costs: Highest on 10Y if rates fall sharply.
Basis Risk: SONIA vs Gilt spread is currently tight.

Best Strategy for Thames Valley Solar Farm:

Enter a 5-Year SONIA Swap (Pay Fixed 4.17%) on £180m notional.
Rationale: Best balance of cost (lowest fixed rate) and hedge horizon. Covers construction + first few years of revenue stabilization. Saves ~£1.2m+ annually vs unhedged if SONIA rises.

Sensitivity:

If BoE cuts rates by 50bps in 2026 → 5Y swap becomes expensive (mark-to-market loss).
If rates rise → Significant savings vs floating debt.


























Assumed Notional: £180 million
Payment Frequency: Semi-annual (standard for GBP swaps)
Day Count: ACT/365
