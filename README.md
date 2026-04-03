# Healthcare Access in India: A District-Level Analysis
### Where the gaps are, why they persist, and where intervention has the highest ROI
*Analysis based on NFHS-5 (2019–21) district data across 706 districts and 36 states/UTs*

---

## THE SITUATION

India's national health access indicators mask a profound internal divide. This analysis of 706 districts across all 36 states and union territories reveals a **65-point gap** between the highest-performing state (Goa, 84.4) and the lowest (Bihar, 19.7) on a composite health access index spanning maternal care, child nutrition, vaccination coverage, insurance penetration, and NCD burden. The gap is not merely financial — it is structural.

---

## WHAT THE DATA SHOWS

- **The South-North divide is stark but not the whole story.** Goa, Kerala, Lakshadweep, Puducherry and Tamil Nadu occupy the top 5. Bihar, Jharkhand and Uttar Pradesh occupy the bottom 3 — but Gujarat and Maharashtra, two of India's wealthiest states, also underperform their predicted scores by 3.5 and 1.7 points respectively, suggesting that economic growth alone does not translate into health access.

- **Household infrastructure, not clinical capacity, is the primary driver.** A Random Forest model across 12 health indicators identifies **clean fuel access** as the single strongest predictor of health outcomes — above vaccination rates, institutional births, or insurance coverage. Stunting emerges as the second strongest driver, indicating that the health access gap is being set in the first 1,000 days of life, well before most interventions reach children.

- **Eight states are underperforming their predicted scores given available inputs.** Bihar (-5.9 gap), Jharkhand (-3.7), Gujarat (-3.5) and Uttar Pradesh (-3.3) score materially below what their socioeconomic and infrastructure inputs would predict. These are not simply poor states — they are states where systemic inefficiencies are suppressing outcomes that resources should be able to deliver.

- **The insurance protection gap compounds every other vulnerability.** States at the bottom of the index also show the lowest health insurance penetration, meaning out-of-pocket costs function as a second barrier after physical access — households that do reach a facility face financial catastrophe.

---

## THE INSIGHT

The dominant narrative around India's health access deficit frames it as a funding and infrastructure problem — more clinics, more doctors, more beds. This analysis challenges that framing. **The strongest predictors of health access are household-level determinants** (clean cooking fuel, early childhood nutrition) that sit upstream of the health system entirely. States like Gujarat and Maharashtra — with comparatively strong GDP and infrastructure — still underperform their predicted scores, indicating that **channelling resources without addressing systemic inefficiencies in delivery produces diminishing returns.**

The implication is that marginal investment in clinical capacity in underperforming states will have lower ROI than interventions targeting household energy access, early childhood nutrition programmes, and community-level health worker deployment.

---

## RECOMMENDATIONS

**1. Prioritise Bihar, Jharkhand and Uttar Pradesh for system-design reform, not just funding.**
These three states have the largest absolute gaps and the largest deviation from predicted performance. Additional funding without structural reform — in health worker accountability, last-mile delivery, and community health infrastructure — will not close the gap. A targeted diagnostic of *why* delivery is inefficient in these states is the necessary first step.

**2. Reframe Gujarat and Maharashtra as efficiency, not poverty, problems.**
These are not low-income states. Their underperformance relative to predicted scores signals process and governance failures in health delivery — making them strong candidates for data-driven operational improvement initiatives that consulting and health-tech firms can meaningfully support.

**3. Direct upstream investment toward clean fuel and early childhood nutrition.**
Given that clean fuel access and stunting are the two strongest predictors of composite health access, programmes that accelerate LPG/clean energy adoption and scale community nutrition interventions in the bottom-10 districts will have compounding downstream effects on maternal health, vaccination uptake, and long-term NCD burden — at lower cost than equivalent clinical investment.

---

## METHODOLOGY
Data: NFHS-5 (2019–21), 706 districts, 36 states/UTs. Composite Health Access Score built from 12 indicators normalised to 0–100 and equally weighted. Underperformance gap calculated as actual minus predicted score using a Random Forest Regressor (100 estimators). All analysis conducted in Python (pandas, scikit-learn, plotly).

---

## YOUR README — paste this into GitHub

```
## Healthcare Access in India — A Business Analyst Perspective

**Business question:** Where are India's healthcare access gaps most severe,
what is driving them, and where does strategic intervention have the highest ROI?

## Key findings
- 65-point gap between best (Goa, 84.4) and worst (Bihar, 19.7) performing states
- Clean fuel access — not clinical capacity — is the strongest predictor of health outcomes
- Bihar, Jharkhand, Gujarat and Uttar Pradesh underperform their predicted scores,
  signalling systemic inefficiency rather than pure resource constraints

## Recommendation
Prioritise system-design reform over funding in bottom-3 states.
Treat Gujarat and Maharashtra as efficiency problems, not poverty problems.

## Dashboard
[Tableau Public link — add after publishing]

## Data source
NFHS-5 (2019-21) via Kaggle / data.gov.in

## Tools
Python (pandas, scikit-learn, plotly) | Tableau Public
```
