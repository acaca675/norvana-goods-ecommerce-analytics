# Norvana Goods — E-Commerce Growth & Marketing Analytics

> **End-to-end e-commerce analytics case study built in Microsoft Excel, connecting revenue, marketing efficiency, customer funnel performance, SEO opportunities, product profitability, and business decisions.**

![Executive Dashboard](screenshots/executive-dashboard.png)

---

## Project Overview

**Norvana Goods** is a fictional Direct-to-Consumer (D2C) e-commerce brand created as a **Data Analyst portfolio case study**.

The business sells apparel, footwear, accessories, home goods, electronics, beauty, fitness, and kids' products through its own online store.

This project analyzes performance from **August 2025 to July 2026** across:

* Sales & revenue performance
* Marketing channels and campaigns
* Customer conversion funnel
* SEO performance
* Product and category economics
* Gross and contribution profitability

The objective is not simply to report KPIs, but to answer a more practical business question:

> **Where is performance being lost, what is driving the gap, and where should the business prioritize its next actions?**

---

# Business Questions

The analysis is structured around five core business questions:

| Area              | Business Question                                                                                   |
| ----------------- | --------------------------------------------------------------------------------------------------- |
| **Growth**        | Which channels and campaigns are driving profitable revenue?                                        |
| **Conversion**    | Where is the largest funnel drop-off, and how can it be improved?                                   |
| **SEO**           | Which search opportunities remain untapped?                                                         |
| **Profitability** | Which products and categories generate sustainable profit?                                          |
| **Target**        | Is the business on track to meet its revenue target, and where should the next budget be allocated? |

---

# Executive Dashboard

The final output is a **single Executive Dashboard** designed to provide management with a consolidated view of:

* Revenue and target performance
* Marketing spend and ROAS
* Gross Profit and Contribution Profit
* Funnel conversion
* SEO opportunities
* Product performance
* Profitability
* Key findings and recommended actions

The dashboard is designed around three questions:

### 1. What happened?

Identify changes in revenue, efficiency, conversion, and profitability.

### 2. Why did it happen?

Drill into channels, campaigns, funnel stages, SEO queries, products, and categories to identify the underlying drivers.

### 3. Where should the business act?

Translate analytical findings into budget, campaign, funnel, SEO, and product decisions.

**Analytical flow:**

`Performance → Driver → Diagnosis → Action`

---

# 🔎 Key Findings — July 2026

## 01. Revenue Under Pressure

Revenue reached approximately **Rp2.79B**, down **1.8% vs. the previous period** and **12.7% below the Rp3.2B target**.

The decline was primarily associated with weaker **Google / CPC** performance.

**Business implication:** The revenue gap requires channel-level diagnosis and more disciplined budget allocation rather than simply increasing total marketing spend.

---

## 02. Marketing Efficiency Gap

Overall ROAS was **2.07x**, compared with an estimated **1.86x break-even ROAS**.

Two campaigns illustrate the opportunity:

| Campaign                          |      ROAS | Decision Signal  |
| --------------------------------- | --------: | ---------------- |
| **Remarketing – Cart Abandoners** | **6.94x** | Scale Candidate  |
| **Non-Brand Search – Home**       | **0.38x** | Below Break-even |

**Business implication:** Reduce or restructure inefficient spend while protecting and scaling campaigns that generate stronger economic returns.

---

## 03. Funnel Bottleneck

The largest funnel leakage occurred between **Engaged Sessions and Add to Cart**, with a **95.4% drop-off**.

**Business implication:** Acquisition alone is not the only constraint. Improving product-page merchandising, pricing visibility, product information, and CTA effectiveness could recover conversion potential.

---

## 04. SEO Opportunity

The analysis identified:

* **5 high-impression / low-CTR queries** representing title and meta-description opportunities.
* **13 queries ranking well but generating zero conversions**, indicating potential landing-page or search-intent alignment issues.

**Business implication:** SEO improvement should focus not only on rankings, but also on turning existing search visibility into qualified traffic and conversions.

---

## 05. Product Profitability

**Electronics Accessories** was the highest-revenue category at approximately **Rp362.7M**.

The product analysis identified **12 of 31 products** within the **High Revenue / High Margin** quadrant.

**Business implication:** These products represent stronger candidates for protection, promotion, and further commercial investment.

---

# Business Recommendations

Based on the analysis, the recommended priorities are:

### 1. Reallocate Marketing Spend

Reduce or restructure **below-break-even campaigns**, particularly Non-Brand Search – Home.

Shift investment toward stronger-return opportunities such as **Remarketing – Cart Abandoners**.

### 2. Improve Add-to-Cart Conversion

Investigate the largest funnel bottleneck through:

* Product-page merchandising
* Pricing visibility
* Product information
* CTA effectiveness

### 3. Convert SEO Visibility into Revenue

Prioritize:

* High-impression / low-CTR queries
* High-ranking / zero-conversion queries
* Landing-page and search-intent alignment

### 4. Protect High-Value Products

Prioritize products combining:

**High Revenue + High Margin**

when planning promotions, merchandising, and marketing support.

### 5. Close the Revenue Target Gap

The target gap should be addressed through **better channel efficiency and conversion improvement**, rather than relying solely on additional acquisition spend.

---

# Analytical Framework

The project connects commercial performance with the drivers behind it:

```text
SALES
   ↓
MARKETING
   ↓
FUNNEL
   ↓
SEO
   ↓
PRODUCT
   ↓
PROFITABILITY
   ↓
EXECUTIVE DECISION
```

Each layer answers a different analytical question:

| Layer             | Focus                                                             |
| ----------------- | ----------------------------------------------------------------- |
| **Sales**         | What happened to revenue and target performance?                  |
| **Marketing**     | Which channels and campaigns are driving or diluting growth?      |
| **Funnel**        | Where are customers being lost before purchase?                   |
| **SEO**           | Where are the untapped organic growth opportunities?              |
| **Product**       | Which categories and products are driving commercial performance? |
| **Profitability** | Which revenue streams create sustainable economic value?          |

This framework moves the analysis from:

> **What happened → Why it happened → What should we do?**

---

# ⚙️ Data & Analytical Workflow

The workbook follows an end-to-end analytical workflow:

```text
RAW DATA
   ↓
DATA QA
   ↓
CALCULATION ENGINE
   ↓
ANALYTICAL METRICS
   ↓
EXECUTIVE DASHBOARD
   ↓
BUSINESS DECISIONS
```

### 01 — Raw Data

Five source datasets simulate a realistic e-commerce analytics environment:

* GA4
* Google Ads
* SEO / Search Console-style data
* E-commerce transactions
* Product catalog

### 02 — Data QA

A dedicated QA layer performs automated data-integrity and cross-source checks using:

**PASS / CHECK / FAIL**

The purpose is to validate data quality and reconciliation before results reach the dashboard.

### 03 — Calculation Engine

The `CALCULATIONS` sheet acts as the central formula engine.

Core metrics include:

* Revenue
* Orders
* AOV
* Marketing Spend
* ROAS
* Break-even ROAS
* Gross Profit
* Gross Margin
* Contribution Profit
* Contribution Margin
* Conversion Rate
* CPA
* CPC
* Target & Variance

### 04 — Analytical Metrics

Detailed analytical tables support:

* Channel performance
* Campaign performance
* SEO query analysis
* Product profitability
* Monthly trends

### 05 — Executive Dashboard

The analytical outputs are consolidated into one management-oriented dashboard.

### 06 — Business Decisions

The final layer translates findings into:

* Budget signals
* Campaign actions
* Funnel improvements
* SEO opportunities
* Product priorities

---

# Key Metrics

| Metric                  | Definition                                     |
| ----------------------- | ---------------------------------------------- |
| **Revenue**             | Total transaction revenue from e-commerce data |
| **Gross Profit**        | Revenue − Product Cost                         |
| **Gross Margin**        | Gross Profit ÷ Revenue                         |
| **Marketing Spend**     | Total advertising spend across Google & Meta   |
| **Contribution Profit** | Gross Profit − Marketing Spend                 |
| **Contribution Margin** | Contribution Profit ÷ Revenue                  |
| **ROAS**                | Conversion Value ÷ Marketing Spend             |
| **Break-even ROAS**     | 1 ÷ Gross Margin                               |
| **AOV**                 | Revenue ÷ Orders                               |
| **Conversion Rate**     | Purchases ÷ Sessions                           |
| **CPA**                 | Marketing Spend ÷ Conversions                  |
| **CPC**                 | Marketing Spend ÷ Clicks                       |

---

# Workbook Structure

```text
Norvana_Goods_Executive_Dashboard.xlsx
│
├── DASHBOARD
├── DATA_QA
├── CALCULATIONS
│
├── Channel_Metrics
├── Campaign_Metrics
├── SEO_Query_Metrics
├── Product_Metrics
├── Monthly_Trend
│
├── GA4_DATA
├── GOOGLE_ADS_DATA
├── SEO_DATA
├── ECOMMERCE_DATA
└── PRODUCT_MASTER
```

| Layer               | Purpose                                      |
| ------------------- | -------------------------------------------- |
| `DASHBOARD`         | Single Executive Dashboard                   |
| `DATA_QA`           | Data quality and cross-source reconciliation |
| `CALCULATIONS`      | Central formula engine                       |
| `Channel_Metrics`   | Channel-level performance                    |
| `Campaign_Metrics`  | Campaign-level efficiency                    |
| `SEO_Query_Metrics` | SEO opportunity analysis                     |
| `Product_Metrics`   | Product and profitability analysis           |
| `Monthly_Trend`     | Monthly performance history                  |
| Raw data sheets     | Controlled source datasets                   |

---

# 🛠️ Tools & Skills Demonstrated

### Tools

* Microsoft Excel
* Excel Dashboarding
* Data Analysis
* Business Intelligence

### Excel Techniques

* `SUMIFS`
* `XLOOKUP`
* Conditional logic
* KPI calculations
* Variance analysis
* Period-over-period analysis
* Cross-source reconciliation
* Ranking and segmentation
* Dashboard visualization

### Analytical Skills

* Business problem framing
* Data quality validation
* Marketing performance analysis
* Funnel analysis
* SEO opportunity analysis
* Product profitability analysis
* Performance diagnosis
* Business recommendation
* Budget allocation analysis

---

# 📁 Project Files

### Interactive Excel Workbook

[**Download Norvana Goods Executive Dashboard**](dashboard/Norvana_Goods_Executive_Dashboard.xlsx)

### Dashboard Preview

[**View Executive Dashboard**](screenshots/executive-dashboard.png)

---

# 📌 Data & Methodology

All data in this project is **synthetic** and created specifically for portfolio purposes.

Norvana Goods is a fictional company.

The dataset is intentionally designed to simulate realistic e-commerce reporting conditions, including measurement differences and reconciliation gaps between commercial, analytics, advertising, and SEO data sources.

### Source of Truth

**E-commerce transaction data** is treated as the commercial source of truth for:

* Revenue
* Orders
* Profitability

**GA4** is primarily used for:

* User behavior
* Sessions
* Funnel analysis

**SEO data** is maintained as an independent Search Console-style dataset and is not expected to reconcile exactly with GA4 Organic data due to differences in measurement methodology and attribution.

All monetary values are presented in **Indonesian Rupiah (IDR)**.

---

# Portfolio Objective

This project was built to demonstrate an analytical approach that goes beyond dashboard creation.

The goal is to connect:

**Business Question → Data → QA → Calculation → Analysis → Insight → Recommendation**

The final deliverable is therefore not just a collection of charts, but a **decision-oriented analytical system** designed to help management understand performance, identify its drivers, and prioritize actions.

---

## Disclaimer

**Norvana Goods is a fictional brand created for portfolio purposes. All data, figures, and business scenarios are synthetic and do not represent a real company.**
