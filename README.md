# 🎬 Pixar Films Analysis (1995–2024)

**Entertainment Analytics | Power BI Dashboard | Maven Analytics Challenge**

---

## Project Background
Pixar Animation Studios is a leading animation film studio operating in the entertainment industry since the mid‑1990s. Known for combining storytelling with cutting‑edge animation, Pixar follows a high‑investment, high‑return business model where films are produced with substantial budgets and monetized primarily through global box office revenue, followed by merchandising and licensing.

From the perspective of a data analyst conducting an external analytical project, the goal of this analysis is to evaluate how Pixar’s creative decisions (originals vs. sequels, themes, genres) and financial investments translate into commercial success, critical reception, and awards recognition over time. Key business metrics analyzed include production budget, box office revenue, profitability, critic ratings, and awards.

Insights and recommendations are provided across the following key areas:

* **Category 1:** Box Office & Profitability Performance
* **Category 2:** Budget Efficiency & ROI
* **Category 3:** Critical Reception & Awards
* **Category 4:** Originals vs. Sequels & Trends Over Time

The cleaned dataset and transformation logic are embedded within the Power BI model.

An interactive Power BI dashboard used to explore Pixar’s performance trends is included in this repository.

---

## Data Structure & Initial Checks

The dataset consists of a single primary table containing **28 Pixar films released between 1995 and 2024**, with a total of **22 attributes**. Each row represents one Pixar film.

### Table: Pixar_Films

Key fields include:

* Film Title
* Release Year
* Genre
* Original / Sequel Flag
* Production Budget
* Box Office Revenue
* Profitability Metrics
* IMDb / Critic Ratings
* Awards & Nominations

### Initial Data Checks

* Standardized column names into human‑readable formats
* Verified correct data types (budgets and revenues as numeric, ratings as decimals)
* Checked for missing or null values (none found)
* Validated year ranges and consistency across financial and rating fields

---

## Executive Summary

### Overview of Findings

Pixar’s long‑term success is driven by a mix of strong brand equity and strategic use of sequels, though high budgets do not consistently guarantee high returns. Sequels generally outperform originals financially, while critical acclaim and awards recognition do not always align with box office success. Over time, Pixar films have evolved toward more mature themes, reflected in changing genres and audience ratings.

*(Primary dashboard visuals highlight overall box office trends, profitability distribution, and performance over time.)*

---

## Insights Deep Dive

### Category 1: Box Office & Profitability Performance

**Main Insight 1:** A small subset of films contributes disproportionately to total box office revenue, with titles like *Toy Story 3* and *Finding Dory* leading overall earnings.

**Main Insight 2:** Median box office revenue is significantly lower than peak performers, indicating a right‑skewed revenue distribution.

**Main Insight 3:** Some lower‑budget films achieved strong profitability, highlighting efficient production strategies.

**Main Insight 4:** Recent releases show strong opening performance, reflecting sustained audience demand for the Pixar brand.

*(Visualization: Top Box Office Performers & Profit Distribution)*

---

### Category 2: Budget Efficiency & ROI

**Main Insight 1:** There is a weak correlation between production budget and box office revenue, suggesting diminishing returns at higher budget levels.

**Main Insight 2:** Several mid‑budget films outperform higher‑budget counterparts in ROI.

**Main Insight 3:** Budget inflation over time has not resulted in proportional revenue growth.

**Main Insight 4:** Financial risk increases significantly for high‑budget projects without franchise backing.

*(Visualization: Budget vs. Earnings Scatter Plot)*

---

### Category 3: Critical Reception & Awards

**Main Insight 1:** Award‑winning films are not always the highest‑rated by critics.

**Main Insight 2:** Critic ratings cluster within a relatively narrow band, indicating consistent quality across Pixar releases.

**Main Insight 3:** Films with strong emotional or innovative storytelling tend to receive higher awards recognition.

**Main Insight 4:** Critical acclaim does not guarantee commercial dominance.

*(Visualization: Ratings vs. Awards Analysis)*

---

### Category 4: Originals vs. Sequels & Trends Over Time

**Main Insight 1:** Sequels generally outperform originals in box office revenue.

**Main Insight 2:** Originals often receive slightly higher critical ratings than sequels.

**Main Insight 3:** Pixar’s themes have matured over time, reflected in genre diversity and rating patterns.

**Main Insight 4:** Franchise films provide revenue stability, while originals drive creative experimentation.

*(Visualization: Sequels vs. Originals Comparison & Time Trends)*

---

## Recommendations

Based on the analysis, the following recommendations are proposed as hypothetical insights that could inform decision-making for studios with similar bus

* **Revenue Stability:** Continue leveraging sequels for predictable box office performance, especially during high‑investment cycles.
* **Creative Balance:** Maintain a steady pipeline of original films to support long‑term brand strength and awards recognition.
* **Budget Strategy:** Apply tighter budget controls for non‑franchise films to maximize ROI.
* **Awards Strategy:** Invest in storytelling and innovation for select projects aimed at critical and awards success.
* **Portfolio Optimization:** Use data‑driven performance benchmarks to guide green‑lighting decisions.

---

## Assumptions & Caveats

* The analysis assumes reported budgets and box office figures are accurate and inflation‑adjustment was not applied.
* All films are treated equally regardless of distribution strategy or release timing.
* Awards and ratings are assumed to be final and comparable across years.
* External factors such as marketing spend and competition were not included due to data limitations.

---

## Acknowledgements

* Dataset curated by **Eric Leung**
* Challenge hosted by **Maven Analytics**
