# CRM Sales Oppurtunities

## Table of Contents

- [CRM Sales Oppurtunities](#crm-Sales-Oppurtunities)
  - [Table of Contents](#table-of-contents)
  - [Project Background](#project-background)
  - [Executive Summary](#executive-summary)
  - [Insights Deep-Dive](#insights-deep-dive)
    - [Regional Performance](#regional-performance)
    - [Deal Types](#deal-types)
    - [Managers \& Agents](#managers--agents)
    - [Industry & Product Performance](#industry--product-performance)
    - [Time Trends](#time-trends)
  - [Recommendations](#recommendations)
    - [Regional Strategy](#regional-strategy)
    - [Deal Management](#deal-management)
    - [Talent Development & Sales Training](#talent-development--sales-training)
    - [Industry & Product Focus](#industry--product-focus)
    - [Sales Operations](#sales-operations)
  - [Clarifying Questions, Assumptions, and Caveats](#clarifying-questions-assumptions-and-caveats)
    - [Questions for Stakeholders](#questions-for-stakeholders)
    - [Assumptions and Limitations](#assumptions-and-limitations)
  - [Detailed Reports](#detailed-reports)

---

## Project Background

For the Maven Sales Challenge, I took the role of a BI Developer, a company focused on selling computer hardware to enterprises. Using CRM data from October 2016 to December 2017, I developed an interactive Tableau dashboard that gave sales managers clear visibility into pipeline performance. The dashboard visualizes opportunities, win rates, revenue gaps, and sales cycles, while uncovering trends by region, industry, and product to support data-driven decisions.

---

## Executive Summary

An analysis of 8,800 sales opportunities worth $20.9 million showed conversions of $10.0 million with a pipeline conversion rate of 47.8%. The United States accounted for over 70% of revenue and was the leading pillar, while Brazil and the Philippines performed weakly. The Central region saw the highest number of closes but with low transaction values, while the East closed fewer deals but with higher values. Discounts dominated but eroded margins, while markup transactions strengthened profitability. Rocco Neubert's team stood out with a 52.1% win rate and the highest revenue per transaction ($2,837). Retail and Technology were the main drivers in industry, while within the product line, the GTX series, particularly the GTX Pro and GTX Plus Pro, accounted for nearly all revenue. The sales cycle also improved significantly, dropping from 130 days in 2016 to less than 11 days in 2017.

<p align="center">
  <img src="https://raw.githubusercontent.com/frdz-salman/CRM-Sales-Oppurtunities/refs/heads/main/visualization/ERD.webp" alt="Sales Trends" width="900">
</p>

<p align="center">CRM Analysis Dataset ERD
</p>

---

## Insights Deep-Dive

### Regional Performance

- Central closed the most deals (1,629) but with the lowest average revenue ($2,054).
- East achieved fewer closings (1,171) but the highest average revenue ($2,639).
- West delivered strong volume (1,438) with moderate revenue ($2,482), dragged down by Korea.
- U.S. contributed over 70% of total revenue, making it the backbone market.

<p align="center">
  <img src="https://raw.githubusercontent.com/frdz-salman/CRM-Sales-Oppurtunities/refs/heads/main/visualization/region.webp" alt="Sales Trends" width="1400">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/frdz-salman/CRM-Sales-Oppurtunities/refs/heads/main/visualization/states.webp" alt="Annual Trends" width="1400">
</p>

### Deal Types

- Discount deals dominate but reduced margins by −$408K.
- Markup deals added +$390K in revenue, strengthening profitability.
- No Deal represented 2,089 missed opportunities.

<p align="center">
  <img src="https://raw.githubusercontent.com/frdz-salman/CRM-Sales-Oppurtunities/refs/heads/main/visualization/discount_markup.webp" alt="Sales Trends" width="700">
</p>

### Managers & Agents

- Rocco Neubert achieved the highest win rate (52.1%) and avg. revenue per deal ($2,837).
  - Reed Clapper was the top agent with a 65.4% win rate.
- Melvin Marxen handled the largest pipeline (1,929 opps) but with the lowest win rate (45.7%).
- Darcel Schlecht (747) & Vicki Laflamme (451) excelled in prospecting with large deal volumes.
- Several agents experienced negative revenue gaps, indicating margin loss at closing.

<p align="center">
  <img src="https://raw.githubusercontent.com/frdz-salman/CRM-Sales-Oppurtunities/refs/heads/main/visualization/metrics.webp" alt="Sales Trends" width="1400">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/frdz-salman/CRM-Sales-Oppurtunities/refs/heads/main/visualization/sales.webp" alt="Annual Trends" width="1400">
</p>

### Industry & Product Performance

- Retail ($1.87M) and Technology ($1.51M) were the top-performing industries.
- Software & Telecommunications underperformed with negative deal gaps.
- GTX Series generated ~70% of revenue ($7.3M), led by GTX Pro & GTX Plus Pro.
- GTK 500 had few opportunities but very high deal value, suitable for a niche market.

<p align="center">
  <img src="https://raw.githubusercontent.com/frdz-salman/CRM-Sales-Oppurtunities/refs/heads/main/visualization/sector.webp" alt="Sales Trends" width="1400">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/frdz-salman/CRM-Sales-Oppurtunities/refs/heads/main/visualization/product.webp" alt="Annual Trends" width="1400">
</p>

### Time Trends

- Sales cycle improved dramatically from 130 days (2016) to under 11 days (2017).
- Revenue remained stable despite fluctuating win rates, supported by high-value deals.

<p align="center">
  <img src="https://raw.githubusercontent.com/frdz-salman/CRM-Sales-Oppurtunities/refs/heads/main/visualization/deal_days.webp" alt="Sales Trends" width="1400">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/frdz-salman/CRM-Sales-Oppurtunities/refs/heads/main/visualization/trend.webp" alt="Annual Trends" width="1400">
</p>

---

## Recommendations

### Regional Strategy

- Strengthen Central Region: Focus on improving deal quality by targeting higher-value accounts.
- Expand East Region: Sustain the high-value strategy while growing the pipeline to reduce dependency on fewer large deals.
- Optimize Weak Markets: Apply localized go-to-market strategies in Korea and the Philippines to improve performance.

### Deal Management

- Enforce Discount Controls: Apply stricter discount guidelines to prevent unnecessary margin erosion and ensure pricing discipline.
- Strengthen Price Negotiation: Train sales teams to defend the Initial Price by emphasizing product value, ROI, and total cost of ownership instead of conceding during negotiations.
- Close Deal Gap: Implement structured coaching programs to help agents align final Deal Value closer to the Initial Price.

### Talent Development & Sales Training

- Leverage Top Performers: Use high achievers like Reed Clappe, Donn Cantrell, and Garret Kinder as trainers and mentors to replicate best practices.
- Strategic Account Allocation: Assign experienced salespeople to enterprise deals where pricing justification and negotiation skills are most critical.
- Certification & Skill Tracking: Introduce structured training modules, internal certifications, and progress tracking to ensure consistent sales excellence across the team.

### Industry & Product Focus

- Promote GTX Series: Focus campaigns on GTX Pro and GTX Plus Pro as flagship products driving the majority of revenue.
- Revitalize Weak Sectors: Reevaluate Employment, Services, and Telecommunications with adjusted positioning and enterprise-focused engagement.
- Position Premium Products: Highlight GTK 500 as a niche, high-value offering for select clients.

### Sales Operations

- Shorten Sales Cycle: Streamline processes and strengthen pre-sales support to close deals faster without lowering prices.

---

## Clarifying Questions, Assumptions, and Caveats

### Questions for Stakeholders

1. Should GTX remain the primary series focus, or should we diversify product investments (e.g., GTK 500 niche market)?
2. Should we allocate more resources to strengthen underperforming regions (e.g., Korea, Philippines), or focus on scaling high-revenue markets (e.g., US, Korea)?
3. Are there any plans to implement a stricter discount policy or revise the current deal pricing framework?
4. What KPIs will be prioritized in upcoming quarters: win rate, average revenue per deal, or total pipeline growth?

### Assumptions and Limitations

- The data only represents the sales cycle for the last quarter of 2016 to 2017.
- Conversion rates and deal gap metrics assume accuracy of CRM data without reporting biases.
- Digital Adoption: The assumption that digital investment will increase online sales may not hold true if customer preference remains skewed towards physical stores.

---

## Detailed Reports

- **Dataset Overview**: [cleaned_crm_analysis.csv](https://drive.google.com/file/d/1wOp2TZif-Xg-SuJlrOAs6p2X_0gN2i1r/view)
- **Github Repo**: [README.md](https://github.com/frdz-salman/CRM-Sales-Oppurtunities.git)
- **Jupyter Notebook**: [crm_analysis.ipynb](https://github.com/frdz-salman/CRM-Sales-Oppurtunities/blob/main/exploration/crm_analysis.ipynb)
- **Tableau Dashboard**: [CRM Analysis Dashboard](https://public.tableau.com/app/profile/faridz.salman.al.parissy/viz/CRMAnalysis_17568031782260/Dashboard)

---
