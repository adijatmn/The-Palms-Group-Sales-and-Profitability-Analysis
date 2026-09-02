# The-Palms-Group-Sales-and-Profitability-Analysis
A multi-page sales dashboard analyzing a full year of transactional data to uncover revenue drivers, regional performance, and product profitability for data-driven decision-making.

This project analyzes The Palms Group's 2014 sales performance across cities, regions, product categories, customers, and payment methods, with the goal of identifying where revenue is concentrated, which products and regions are underperforming, and what leadership could act on heading into the following year's planning cycle.

<img width="5156" height="7788" alt="The Palms Dashboard" src="https://github.com/user-attachments/assets/dc1e6fbc-bfa4-47a4-a271-e44947ab259b" />

---

## 📌 Business Problem

The Palms Group sells across multiple product categories (Beverages, Sauces, Dairy Products, Canned Meat, Jams & Preserves, and others) and multiple U.S. cities, but a full year of transactional data on its own doesn't tell leadership where performance is strong, where it's weak, or why.

**The core problem:** revenue, quantity, and customer data exist, but without consolidation they can't answer the questions that actually drive planning — *which cities and categories are carrying the business, which are underperforming relative to their size, and where is revenue concentrated in ways leadership may not have realized.*

**Why it matters:**
- Without a category-level view, marketing and stocking decisions risk treating all products as equally important when they clearly aren't
- Without a regional view, underperforming markets can go unaddressed for a full sales cycle
- Without a payment-method view, gaps in data capture (e.g. unrecorded "Blank" transactions) can quietly distort reporting accuracy

**Key stakeholders:** Senior leadership (this report was explicitly framed for a senior executive summit), regional sales leads, and category/product managers — each needing a different cut of the same underlying dataset.

---

## 🎯 Project Objective

This report was built to convert a year of raw sales transactions into a structured, decision-ready view for leadership. Specifically, it aims to:

- Identify which cities and regions generate the most (and least) revenue
- Determine which product categories drive volume versus which drive revenue per unit
- Surface top and bottom-performing salespeople and customers
- Track how sales evolved month-to-month across the year
- Understand purchasing behavior by payment method

### Business Questions Answered
1. Which cities and regions contribute the most to total revenue?
2. Which product categories sell the most units, and which generate the most revenue per unit?
3. Who are the top-performing salespeople, and how large is the gap to the lowest performer?
4. Which customers account for the largest share of revenue?
5. How does monthly sales performance trend across the year, and when are the peak and low points?
6. Which payment methods are most commonly used, and is there a data-quality gap worth flagging?

---
## 🛠️ Tools & Technologies

1. Microsoft Power BI
2. Power Query
3. DAX (Data Analysis Expressions)
4. Data Modeling

---

## 📈 Dashboard Preview

**Page 1 — Summary Notes**
An executive overview framing the report's purpose: a comprehensive evaluation of 2014 sales and profitability performance, incorporating pre-, in-, and post-analysis insights to support strategic discussion at the Q1 2015 senior executive summit.

<img width="1507" height="712" alt="PB 1" src="https://github.com/user-attachments/assets/74a07329-3c3c-4d79-bf48-e76fdb492b33" />

**Page 2 — Dashboard**
Core performance view: revenue trend by city and by region, quantity by product category, salesperson performance, product performance table, and revenue trend by customer.

<img width="1502" height="738" alt="PB 2" src="https://github.com/user-attachments/assets/3eba06ff-4c8e-45b2-b642-b2cca024e26f" />

**Page 3 — Succession**
A drill-down layer: a decomposition tree breaking revenue down by city and category, a product revenue/quantity/average-unit-price table, payment method trends over the year, and the monthly sales trend report.

<img width="1503" height="736" alt="PB 3" src="https://github.com/user-attachments/assets/fa60455a-8115-4480-840a-43ca3cfb15ae" />

---

## 📊 Key KPIs

| KPI | Value |
|---|---|
| **Total Revenue** | $435,036.16 |
| **Total Orders** | 369 |
| **Top Category** | Beverages |
| **Top Sales Personnel** | Nancy Freehafer ($104,252.34) |
| **Regional Lead (City)** | New York ($67,180.50–$67,189.50) |
| **Peak Month** | December |

---

## 🔍 Key Findings

**1. Revenue is heavily concentrated in a single region**
- *What happened:* The North region generated 32.56% of total revenue ($141.66K), well ahead of East (24.89%), South (21.57%), and West (20.98%).
- *Why it matters:* Nearly a third of the business rides on one region's performance.
- *Potential impact:* If North underperforms in a future period, the overall business would feel it disproportionately — worth monitoring as a concentration risk, not just a strength.

**2. Category performance splits between volume drivers and price drivers**
- *What happened:* Beverages led on both revenue ($75,486) and volume (1,641 units, average unit price $46), while Jams & Preserves had the highest average unit price of all categories ($81) but the lowest volume (511 units).
- *Why it matters:* These are two different kinds of "good performer" — one wins by moving volume, the other by commanding price — and they likely need different marketing or stocking strategies.
- *Potential impact:* Treating Jams & Preserves as a premium, lower-volume line rather than trying to scale its volume like Beverages could better match strategy to how it actually sells.

**3. Sales performance among salespeople is highly uneven**
- *What happened:* Nancy Freehafer's sales ($104,252.34) were more than double the fourth-ranked performer, Mariya Sergienko ($42,370.88), and roughly six times the lowest performer, Jan Kotas ($16,351).
- *Why it matters:* A gap this large between top and bottom performers suggests either a large skill/technique gap or an uneven territory/account assignment — worth distinguishing between the two.
- *Potential impact:* If the gap is technique-driven, pairing top and bottom performers for mentoring could lift overall team performance; if it's territory-driven, reassigning accounts might be the more effective lever.

**4. Sales are strongly seasonal, not steady across the year**
- *What happened:* Monthly revenue swung from a low of $20K (February) to a high of $67K (December), with a secondary peak in June ($56K).
- *Why it matters:* Flat, non-seasonal planning around this business would risk under-resourcing for December and over-resourcing for February.
- *Potential impact:* Aligning staffing, inventory, and promotional spend with this demonstrated seasonal pattern could reduce both missed sales during peaks and wasted spend during troughs.

**5. A notable share of transactions have no recorded payment method**
- *What happened:* "Blank" payment method entries were common enough to appear as their own category in the payment trend chart, alongside Cash, Check, and Credit Card.
- *Why it matters:* This is very likely a data capture gap rather than a genuine "no payment method" category, which slightly understates the true picture of how customers actually pay.
- *Potential impact:* Tightening data entry requirements at the point of sale would improve the reliability of every future payment-method analysis built on this data.

---

## 💼 Business Impact

This report was built to address a specific gap: leadership had a full year of transactional data but no consolidated, decision-ready view of it ahead of a strategic summit. With this report in place, a leadership team would be positioned to:

- **Prioritize with evidence** — directing category and regional attention toward Beverages and the North region, which the data shows are already carrying a disproportionate share of performance
- **Plan around real seasonality** — aligning staffing and inventory with the demonstrated December peak and February trough, rather than flat, non-seasonal planning
- **Address performance variance** — using the salesperson performance gap as a starting point for a mentoring or territory-review conversation
- **Improve future reporting accuracy** — flagging the "Blank" payment method gap as a data-quality fix ahead of the next reporting cycle

> 📌 In short: this report turns a year of historical transactions into a starting point for the following year's regional, category, and staffing decisions, rather than leaving that data as an unreviewed export.

---

## 🚀 Recommendations

| Recommendation | Why It Matters |
|---|---|
| **Investigate why the North region so significantly outperforms** | Understanding the driver (market size vs. execution) determines whether it's replicable elsewhere |
| **Treat Jams & Preserves as a premium line, not a volume line** | Matches strategy to how the category actually performs, rather than judging it against Beverages-style volume targets |
| **Review the gap between top and bottom-performing salespeople** | Determines whether mentoring, training, or territory reassignment is the right lever |
| **Plan inventory and staffing around the demonstrated seasonal pattern** | Reduces the risk of under-resourcing December and over-resourcing February |
| **Fix payment-method data capture at the point of sale** | Improves the reliability of every future analysis that depends on this field |

