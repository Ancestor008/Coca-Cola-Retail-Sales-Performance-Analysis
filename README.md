# 🧾 Retailer Sales Analysis Dashboard: A Behavioural Investigation of Consumer Demand, Brand Preference, and Seasonal Decision Patterns

> *"Markets are not driven by numbers alone — they are driven by the decisions of millions of people responding to brands, environments, and moments."*

---

## 📋 Table of Contents

1. [Executive Summary](#-executive-summary)
2. [Project Preview](#-project-preview)
3. [Background](#-background)
4. [Statement of Problem](#-statement-of-problem)
5. [Research Questions](#-research-questions)
6. [Key Metrics & KPIs](#-key-metrics--kpis)
7. [Methodology](#-methodology)
8. [Results & Findings](#-results--findings)
9. [Discussion](#-discussion)
10. [Recommendations](#-recommendations)
11. [Limitations](#-limitations)
12. [Conclusion](#-conclusion)
13. [Dashboard Usage](#-dashboard-usage)
14. [How to Reproduce the Analysis](#-how-to-reproduce-the-analysis)
15. [Connect With Me](#-connect-with-me)

---

## 📌 Executive Summary

This project investigates the commercial and behavioural dynamics underlying **9,648 Coca-Cola retailer transactions** across the United States, spanning 2022–2023. Using an Excel-based interactive dashboard, it examines how consumer purchasing behaviour — shaped by brand loyalty, seasonal demand cycles, and retailer channel concentration — translates into measurable sales and profitability outcomes.

The core behavioural question is: **What patterns of consumer preference, seasonal demand, and retailer dependence drive revenue concentration in a large-scale retail distribution network?**

Drawing on sales, profitability, regional, and temporal data, this analysis reveals a **296% year-on-year growth** in total sales (from $2.42M in 2022 to $9.59M in 2023), a highly profitable operating margin of **42.3%**, and a notable concentration of both brand preference and retailer dependence that introduces structural risk into the distribution model.

These findings have direct implications for **channel strategy**, **portfolio diversification**, **behavioural segmentation**, and the role of seasonal consumer psychology in demand planning.

---

## 🖥️ Project Preview

### Dashboard Screenshot

<img width="1147" height="732" alt="Retailer dashboard " src="https://github.com/user-attachments/assets/f89824b4-8ca6-4df3-9368-032e33954d3c" />


---

### Analytical Workflow

```
┌──────────────────────────────────────────────────────────────────────────┐
│                        ANALYTICAL WORKFLOW                               │
│                                                                          │
│  [Data Preparation]  →  [KPI Computation]  →  [Pivot Analysis]          │
│         ↓                      ↓                      ↓                 │
│  Clean & validate      Calculate margins       Brand, retailer,         │
│  9,648 records         sales, profitability    region breakdowns        │
│         ↓                      ↓                      ↓                 │
│  [Dashboard Build]   →  [Interactive Filtering] →  [Insight Generation] │
│  Charts, tables        Slicers by year/region   Behavioural patterns    │
└──────────────────────────────────────────────────────────────────────────┘
```

> 📁 **See `Retailer Project.xlsx`** for the full interactive dashboard with slicer-based filtering, pivot table analysis, and KPI visualisations.

---

## 📚 Background

### Consumer Behaviour as the Engine of Commercial Outcomes

Retail sales data is not merely a ledger of transactions — it is a compressed record of millions of individual consumer decisions. Each unit sold represents a choice made under conditions of habit, environmental cue, brand perception, and situational context. To interpret retail performance analytically without reference to the behavioural forces that generate it is to misread the signal.

The field of **behavioural economics** offers a powerful lens for interpreting commercial data. Rather than assuming that consumers behave as rational utility-maximisers, it documents the systematic ways in which cognitive shortcuts, emotional responses, and environmental architecture shape purchase decisions (Thaler & Sunstein, 2008).

> Thaler, R. H., & Sunstein, C. R. (2008). *Nudge: Improving decisions about health, wealth, and happiness*. Yale University Press.

---

### Brand Loyalty, Familiarity, and the Mere Exposure Effect

One of the most reliable findings in consumer psychology is that **familiarity breeds preference**. Zajonc's (1968) mere exposure effect demonstrates that repeated exposure to a stimulus — a brand name, a logo, a product — increases liking for that stimulus, independent of product quality. This helps explain why flagship brands like Coca-Cola and Dasani consistently capture the largest shares of consumer wallet even in highly competitive beverage markets.

> Zajonc, R. B. (1968). Attitudinal effects of mere exposure. *Journal of Personality and Social Psychology, 9*(2, Pt.2), 1–27. [https://doi.org/10.1037/h0025848](https://doi.org/10.1037/h0025848)

Brand loyalty in FMCG (fast-moving consumer goods) markets is further reinforced by **habit formation** — the neurological process by which repeated choices become automatic and resistant to disruption (Wood & Neal, 2009). Consumers who habitually purchase Coca-Cola products are less likely to engage in deliberate comparison shopping, producing sticky demand that underpins consistent revenue even across changing economic conditions.

> Wood, W., & Neal, D. T. (2009). The habitual consumer. *Journal of Consumer Psychology, 19*(4), 579–592. [https://doi.org/10.1016/j.jcps.2009.08.003](https://doi.org/10.1016/j.jcps.2009.08.003)

---

### Seasonal Demand and Situated Consumer Choice

Consumer demand for beverages is not uniform across time — it is deeply **situated**, responding to ambient temperature, social occasion, and seasonal norms. Hirschman and Holbrook (1982) documented the role of **hedonic consumption** — the experiential, emotion-driven dimension of purchasing — in shaping demand patterns for products associated with pleasure and social context.

> Hirschman, E. C., & Holbrook, M. B. (1982). Hedonic consumption: Emerging concepts, methods and propositions. *Journal of Marketing, 46*(3), 92–101. [https://doi.org/10.1177/002224298204600314](https://doi.org/10.1177/002224298204600314)

Cold beverages are a canonical hedonic product: demand peaks in warmer months (Q2–Q3) driven by temperature, outdoor activity, and social consumption occasions — patterns visible in this dataset's quarterly revenue trajectory.

---

### Retailer Concentration and Channel Dependency

The behavioural economics of **B2B distribution** is less studied than B2C consumer psychology, but concentration risk in retail channels follows analogous dynamics. When a disproportionate share of revenue flows through a small number of retail partners, the organisation faces a **structural vulnerability** analogous to the over-reliance cognitive bias — where decision-makers become over-dependent on a small number of trusted signals (Kahneman, 2011).

> Kahneman, D. (2011). *Thinking, fast and slow*. Farrar, Straus and Giroux.

The 80/20 principle (Pareto, 1896, as applied in business strategy) predicts that a small proportion of retailers will contribute a disproportionate share of revenues. This dataset provides an opportunity to quantify how extreme this concentration is in practice and assess the strategic risk it implies.

---

### Regional Distribution and Geographic Demand Heterogeneity

Consumer demand is not uniformly distributed across geography. **Population density**, **retail infrastructure maturity**, **regional income levels**, and **culturally specific consumption norms** all shape the geographic distribution of sales. The concentration of revenue in New York, California, Florida, and Texas — states with the largest populations and most mature retail ecosystems — reflects both demographic scale and the strategic prioritisation of high-density markets.

Arnett et al. (2003) document how brand relationship quality varies by regional context, suggesting that geographic segmentation is not only a logistics question but a behavioural one.

> Arnett, D. B., German, S. D., & Hunt, S. D. (2003). The identity salience model of relationship marketing success: The case of nonprofit marketing. *Journal of Marketing, 67*(2), 89–105. [https://doi.org/10.1509/jmkg.67.2.89.18614](https://doi.org/10.1509/jmkg.67.2.89.18614)

---

## ❗ Statement of Problem

Despite generating substantial revenue, many retail distribution networks operate without a clear behavioural understanding of what drives the patterns they observe. Growth is celebrated; the structural dependencies and behavioural mechanisms that underlie it are rarely interrogated.

**This project addresses the following problem:**

> *What do the sales and profitability patterns across brands, retailers, regions, and time periods reveal about the consumer behavioural forces and structural commercial risks that define this retail network's performance — and what decisions do those insights demand?*

This matters because:
- **Unexplained growth** is commercially dangerous: without understanding what is driving performance, organisations cannot reliably sustain it.
- **Concentration risk** — whether in brands, retailers, or regions — creates fragility that only becomes visible when a relationship or trend breaks.
- **Seasonal demand patterns** represent either a planning opportunity or a planning failure, depending on whether the organisation anticipates them or responds to them reactively.

Understanding these dynamics through a behavioural and analytical lens converts raw commercial data into **strategic intelligence**.

---

## 🔎 Research Questions

1. **What is the magnitude and character of year-on-year sales growth, and what structural factors likely explain it?**
2. **Which beverage brands dominate consumer preference, and what does the distribution of brand performance reveal about loyalty and portfolio risk?**
3. **How concentrated is revenue across retailers, and what are the strategic implications of that concentration?**
4. **What seasonal patterns are visible in quarterly sales and margin data, and how do they reflect underlying consumer demand psychology?**
5. **Which geographic markets drive the highest revenue contribution, and where does untapped distribution potential lie?**

---

## 📊 Key Metrics & KPIs

| Metric | Definition | Behavioural / Strategic Relevance |
|---|---|---|
| **Total Sales ($)** | Aggregate revenue across all transactions | Primary indicator of commercial traction and market demand |
| **Units Sold** | Total product units sold | Volume indicator; separates revenue driven by price vs. demand |
| **Average Price per Unit ($)** | Mean transaction price | Pricing power and sensitivity to consumer price anchoring |
| **Total Operating Profit ($)** | Revenue minus operating costs | Efficiency of translating consumer demand into financial value |
| **Operating Profit Margin (%)** | Operating profit as % of sales | Structural health; resilience of profitability model |
| **YoY Sales Variance** | Year-on-year change in sales by brand/retailer | Growth trajectory; identifies acceleration and deceleration signals |
| **Quarterly Sales Distribution** | Sales by Q1–Q4 | Seasonal demand rhythm; planning anchor for inventory and marketing |
| **Brand Concentration Ratio** | % of sales from top 3 brands | Portfolio risk indicator; brand dependency assessment |
| **Retailer Concentration Ratio** | % of sales from top 3 retailers | Channel dependency and relationship risk |
| **Regional Sales Distribution** | Sales by state/region | Geographic demand heterogeneity; expansion opportunity mapping |

---

## 🔬 Methodology

### Research Design

This project employs an **observational, exploratory analytical design** — appropriate when the goal is to describe and understand patterns in existing commercial data rather than to manipulate variables experimentally. The analysis combines **descriptive statistics**, **temporal trend analysis**, **categorical segmentation**, and **KPI modelling** to extract behavioural and strategic insight from transactional records.

The analytical posture is fundamentally interpretive: the goal is not merely to report what the numbers are, but to explain *what human and structural behaviours generated them* and *what they imply for future decision-making*.

---

### Dataset

| Parameter | Detail |
|---|---|
| **Total Records** | 9,648 retailer transaction profiles |
| **Time Period** | 2022–2023 |
| **Variables** | 12 fields per record |
| **Geographic Coverage** | Multiple U.S. regions and states |
| **Data Fields** | Retailer · Retailer ID · Invoice Date · Region · State · City · Beverage Brand · Price per Unit · Units Sold · Total Sales · Operating Profit · Operating Margin |

The dataset provides a rich cross-section of commercial activity, enabling simultaneous analysis across **time** (quarterly, annual), **product** (brand), **channel** (retailer), and **geography** (region, state, city).

---

### Tools Used

| Tool | Application |
|---|---|
| **Microsoft Excel** | Primary analytical and visualisation environment |
| **Pivot Tables** | Dimensional aggregation across brand, retailer, region, and time |
| **Pivot Charts** | Visual representation of sales and profitability trends |
| **Dynamic Formulas** | KPI computation (margins, variances, growth rates) |
| **Conditional Formatting** | Visual encoding of performance thresholds and anomalies |
| **Slicers** | Interactive filtering by year and region for exploratory navigation |

Excel was selected as the primary tool for its accessibility, auditability, and suitability for business stakeholder communication — the dashboard is designed to be usable by non-technical decision-makers without requiring programming knowledge.

---

### Analytical Approach

**Step 1 — Data Preparation**
Records were reviewed for completeness, consistency, and accuracy. Date fields were formatted for temporal aggregation; categorical fields (brand, retailer, region) were standardised; computed fields (operating margin) were validated against raw components.

**Step 2 — KPI Computation**
Core performance indicators were derived:

```
Operating Profit Margin = Operating Profit / Total Sales × 100
YoY Sales Variance      = (2023 Sales - 2022 Sales) / 2022 Sales × 100
Retailer Concentration  = Top 3 Retailer Sales / Total Sales × 100
```

**Step 3 — Dimensional Analysis**
Pivot tables were constructed to segment sales and profitability across:
- **Beverage Brand** (2022 vs. 2023 comparison + variance)
- **Retailer** (2022 vs. 2023 comparison + variance)
- **Quarter** (Q1–Q4 sales trajectory and margin trend)
- **State / Region** (geographic contribution analysis)

**Step 4 — Dashboard Development**
An interactive Excel dashboard was built integrating:
- KPI summary tiles
- Brand performance comparison charts
- Retailer contribution analysis
- Quarterly sales and margin trend visualisations
- Slicer-based filtering for year and region

**Step 5 — Behavioural and Strategic Interpretation**
Quantitative findings were interpreted through the lens of consumer psychology, channel strategy, and behavioural economics to generate actionable insight beyond the descriptive statistics.

---

### Ethical Considerations

This analysis uses **aggregated commercial transaction data** with no personally identifiable information. No individual consumer data is present in the dataset. All findings are interpreted at the aggregate level and are intended to inform strategic decision-making, not to target or profile individual customers. Responsible use of sales analytics requires that insights about consumer behaviour patterns not be weaponised for manipulative pricing or exploitative targeting strategies (Thaler & Sunstein, 2008).

---

## 📈 Results & Findings

### 1. Overall Sales Performance: Explosive Year-on-Year Growth

| Metric | 2022 | 2023 | Change |
|---|---|---|---|
| Total Sales | $2.42M | $9.59M | **+296%** |
| Operating Profit | — | $4.72M | — |
| Operating Profit Margin | 40.0% | 43.0% | **+3 pp** |
| Average Price per Unit | — | — | — |

A **296% increase in total sales** between 2022 and 2023 is extraordinary by any commercial benchmark. This growth trajectory suggests one or more of the following: successful retail network expansion, increased consumer demand, improved distribution coverage, or more effective brand activation — likely a combination.

The simultaneous **improvement in operating margin** (40% → 43%) indicates that growth was not purchased at the cost of profitability — a key indicator of **sustainable commercial performance** rather than volume-driven dilution.

---

### 2. Brand Performance: Concentration Around Flagship Products

| Beverage Brand | 2023 Sales | % of Total 2023 Sales |
|---|---|---|
| Coca-Cola | $2.27M | ~23.7% |
| Dasani Water | $1.92M | ~20.0% |
| Diet Coke | $1.63M | ~17.0% |
| **Top 3 Combined** | **~$5.82M** | **~60.7%** |
| FizzyCo | $2.26M (from $161K in 2022) | — |

- **Coca-Cola, Dasani Water, and Diet Coke collectively account for approximately 60% of total 2023 revenue**, confirming H₁ and reflecting the dominance of high-familiarity, habitually purchased brands.
- **FizzyCo** grew from $161K (2022) to $2.26M (2023) — a **1,303% increase** — the fastest-growing brand in the portfolio. This likely reflects new retail partnerships, expanded distribution, or a successful launch campaign.

---

### 3. Retailer Contribution: High Concentration Risk

| Retailer | Total Sales | % of Total |
|---|---|---|
| West Soda | $3.24M | ~27% |
| BevCo | — | — |
| FizzyCo | — | — |
| **Top 3 Combined** | — | **>70%** |

- **West Soda alone accounts for ~27% of total sales**, making it the single most commercially critical relationship in the network.
- The **top 3 retailers contribute over 70% of total revenue**, confirming H₃ and signalling a significant channel concentration risk.

---

### 4. Seasonal & Quarterly Trends: Mid-Year Demand Peak

| Quarter | 2023 Sales | QoQ Change |
|---|---|---|
| Q1 | $1.88M | — |
| Q2 | $2.38M | +$0.50M (+26.6%) |
| Q3 | $2.81M | +$0.43M (+18.1%) |
| Q4 | $2.53M | −$0.28M (−10.0%) |

- **Q3 represents the revenue peak** at $2.81M, consistent with H₂ and the expected seasonal demand pattern for cold beverages.
- The **Q4 dip ($2.53M)** likely reflects post-peak seasonal contraction and is a predictable pattern that can be planned for.
- **Operating margin improved from 0.40 (2022) to 0.43 (2023)**, suggesting increasing cost efficiency alongside volume growth.

---

### 5. Regional & State Distribution: Coastal and Urban Concentration

| Rank | State | Approximate Sales |
|---|---|---|
| 1 | New York | $867K |
| 2 | California | $858K |
| 3 | Florida | $782K |
| 4 | Texas | $661K |
| 5 | South Carolina | $359K |
| **Top 5 Combined** | | **~$3.53M (~30% of total)** |

- The **top 5 states account for approximately 30% of total sales**, consistent with H₄.
- Revenue is heavily concentrated in **high-population coastal and sunbelt markets**.
- The **long tail of smaller states** (many contributing <$300K) represents a significant **untapped distribution opportunity**.

---

## 💬 Discussion

### Interpreting Growth Through a Behavioural Lens

The 296% year-on-year growth documented in this analysis is striking — but the more analytically important question is not *how much* growth occurred, but *what sustained it*. The simultaneous improvement in operating margin alongside volume growth suggests that demand was genuine and structurally supported, not artificially inflated by unsustainable discounting or temporary promotional activity.

From a consumer psychology perspective, this growth trajectory likely reflects **network effects in retail adoption**: as distribution coverage expanded into new retailers and regions, familiar Coca-Cola brands benefited from **brand recognition spillover** — new consumers encountering familiar brands in new retail contexts and defaulting to habitual preference patterns (Wood & Neal, 2009).

---

### Brand Concentration as a Behavioural Phenomenon

The dominance of Coca-Cola, Dasani, and Diet Coke — accounting for ~60% of total revenue — is not simply a market share statistic. It is a **behavioural fingerprint**: evidence that consumer choice in this product category is heavily governed by familiarity, habit, and the cognitive ease of selecting a known brand over an unfamiliar one (Kahneman, 2011).

This has a dual implication. On one hand, it validates the commercial power of brand equity investment — decades of consumer exposure have created demand structures that are highly resilient. On the other hand, it signals that **newer or less familiar brands in the portfolio are operating in the cognitive shadow of the flagship brands** — their growth requires either stronger distribution push or marketing investment sufficient to break through habitual default selection.

The dramatic growth of FizzyCo (+1,303%) suggests that with sufficient distribution momentum, newer brands can overcome this cognitive inertia — but the data also shows that they remain far from closing the gap with established players.

---

### Retailer Concentration: Strategic Dependency as a Structural Bias

The finding that the top three retailers account for over 70% of total revenue is analytically equivalent to an **over-reliance cognitive pattern** at the organisational level. Just as individuals make decisions that are disproportionately influenced by a small number of trusted sources (Kahneman, 2011), commercial organisations can become structurally dependent on a small number of high-performing channel partners — benefiting from efficiency in the short term, but accumulating fragility over time.

The risk is concrete: **the loss or strategic underperformance of West Soda alone** — which contributes ~27% of total revenue — would represent a catastrophic short-term commercial shock. Diversification of the retailer base is therefore not merely a strategic preference but a **risk management imperative**.

---

### Seasonal Patterns: Behavioural Demand Rhythms

The Q2–Q3 peak in beverage sales is one of the most predictable patterns in consumer behaviour research. Cold beverages are **context-triggered purchases** — their consumption is elevated by ambient temperature, social occasions (barbecues, outdoor events, sporting activity), and the association between summer and refreshment that is deeply embedded in cultural consumption norms.

For product and marketing teams, this seasonal rhythm is a planning anchor: **inventory, promotional investment, and retailer push activities should be concentrated in Q1–Q2** to maximise the capture of the rising Q3 demand curve, with a managed wind-down strategy for Q4 to protect margins during the seasonal contraction.

---

## 🔧 Recommendations

**1. Diversify the retailer base to reduce concentration risk**
The current dependency on three retailers for >70% of revenue creates a structurally fragile distribution model. A targeted retailer expansion programme — identifying and onboarding mid-sized regional retailers across currently underserved states — would reduce concentration risk and open new revenue channels. Target: reduce top-3 retailer share from >70% to <50% over 24 months.

**2. Invest in the brand long tail to reduce portfolio concentration**
The current 60% revenue concentration in three brands is commercially understandable but strategically limiting. Portfolio health requires that emerging brands (particularly the high-growth FizzyCo) are given sufficient distribution and marketing support to build their own habit-formation loops among new consumer segments (Wood & Neal, 2009).

**3. Build a seasonal demand playbook**
The Q3 peak is predictable and should be planned for. Develop a formal seasonal demand calendar with differentiated inventory, promotional, and distribution strategies by quarter:
- **Q1–Q2**: Ramp inventory and retailer push ahead of peak demand
- **Q3**: Maximise availability and visibility at point of sale
- **Q4**: Manage margin-protective wind-down; begin planning for next cycle

**4. Prioritise geographic expansion into underserved markets**
The long tail of states contributing <$300K represents a genuine expansion frontier. A phased geographic entry strategy — beginning with states that have high population density but low current sales penetration — would broaden the revenue base and reduce geographic concentration risk.

**5. Instrument the data to enable behavioural segmentation**
The current dataset enables strong descriptive analysis but lacks the consumer-level granularity needed for behavioural segmentation. Where data collection infrastructure allows, capturing consumer demographics, purchase frequency, basket composition, and channel preference would enable the kind of **behavioural micro-segmentation** that transforms commercial data into product and marketing intelligence (Ariely, 2008).

> Ariely, D. (2008). *Predictably irrational: The hidden forces that shape our decisions*. HarperCollins.

---

## ⚠️ Limitations

| Limitation | Detail |
|---|---|
| **Aggregated data** | Records represent retailer-level transactions, not individual consumer purchases. Behavioural interpretation is inferred from commercial patterns, not directly observed consumer behaviour. |
| **No causal identification** | The observational design cannot establish causality. The 296% growth could reflect distribution expansion, market trend, brand investment, or macroeconomic factors — or all of these simultaneously. |
| **Two-year window** | With only two years of data, it is difficult to distinguish genuine trend from noise, or to assess whether the 2022 baseline was atypically low. |
| **Missing consumer demographics** | The dataset contains no consumer-level demographic, psychographic, or preference data, limiting the depth of behavioural interpretation possible. |
| **Regional coverage gaps** | Not all U.S. states are equally represented, making national generalisations cautious. |
| **No competitive context** | Sales data is presented in isolation, without benchmarking against market share or competitor performance, limiting strategic interpretation. |

---

## 🏁 Conclusion

This analysis demonstrates that behind every commercial performance number lies a pattern of human decision-making: the habitual purchase of familiar brands, the seasonal rhythms of situated consumption, the organisational dependency on trusted retail partners, and the geographic clustering of demand around established consumer markets.

The **296% year-on-year growth** documented here represents genuine commercial momentum — but it also masks structural dependencies and concentration risks that, if unaddressed, could constrain long-term resilience. **Brand concentration** around three flagship products, **retailer concentration** in three channel partners, and **geographic concentration** in coastal metro markets are all commercially logical in the short term but structurally fragile over time.

The strategic imperative is clear: **diversify without disrupting**. Protect the habitual loyalty that drives flagship brand revenue, while systematically building the retailer breadth, geographic reach, and emerging brand strength needed to insulate performance against structural shocks.

For behavioural researchers and analysts, this dataset is a reminder that **commercial data is behavioural data** — and that reading it well requires not just mathematical fluency, but a grounded understanding of the psychological and contextual forces that generate it.

---

## 🧭 Dashboard Usage

1. **Download** `Retailer Project.xlsx` and open in Microsoft Excel (Office 365 or Excel 2019+ recommended).
2. **Use the year slicer** to toggle between 2022 and 2023 data, or view both simultaneously.
3. **Use the region slicer** to filter all visuals by geographic region.
4. **Explore the KPI tiles** at the top of the dashboard for headline performance metrics.
5. **Navigate the brand and retailer charts** to compare year-on-year performance and identify variance drivers.
6. **Review the quarterly trend chart** to understand seasonal demand patterns and margin trajectory.

![Retail Vid](https://github.com/user-attachments/assets/d0e3ac19-bcc8-41f3-8777-fee74795c3b8)


---

## ▶️ How to Reproduce the Analysis

### Requirements
- Microsoft Excel 2019+ or Office 365

### Steps

```
1. Download Retailer Project.xlsx from this repository
2. Open the file in Excel
3. Navigate to the Dashboard tab
4. Use the slicers (Year, Region) to filter the view
5. All pivot tables and charts will update dynamically
```

**To explore the underlying data:**
- Navigate to the raw data tab to view the 9,648 transaction records
- Pivot tables are linked to the raw data and can be refreshed or modified
- All KPI formulas are documented with inline comments

---

## 🤝 Connect With Me

I am a **Behavioral Researcher** focused on judgment and decision-making under uncertainty, user psychology, and the cognitive and structural forces that shape human behaviour in digital and commercial environments.

My work spans **behavioral science**, **product analytics**, and **applied UX research** — translating evidence-based research thinking into insights that inform product design, channel strategy, and human-centred decision systems.

---

| | |
|---|---|
| 💼 **LinkedIn** | [linkedin.com/in/oayomide](https://www.linkedin.com/in/oayomide) |
| 📧 **Email** | [ojoayomide008@gmail.com](mailto:ojoayomide008@gmail.com) |
| 🎓 **Research Focus** | Judgment & Decision Making · Behavioral Analytics · Consumer Psychology |
| 📍 **Open to** | UX Research · Experimental Analytics · Product Science · Behavioral Finance |

---

> *"Every transaction is a decision. Every decision is a behaviour. Every behaviour has a cause worth understanding."*

---
