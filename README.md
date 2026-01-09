# 🎮 Steam Game Analysis: What Type of Game Should We Build Next?

**Role / Scenario:**  
You are a Data Analyst at a mid-sized game studio tasked with advising leadership on the next game to develop. The goal is to maximize engagement, revenue potential, and market fit using historical Steam data.

---

## 📝 1️⃣ Business Problem

**Objective:** Identify high-performing game genres and monetization models to inform the studio’s next title.  

**Constraints:** Budget is limited; cannot produce multiple AAA titles simultaneously. Must focus on genres and monetization with proven engagement and revenue potential.  

**Key Questions:**  
1. Which genres show the highest engagement?  
2. Free-to-Play vs Paid — which performs better?  
3. Does multiplayer outperform single-player?  
4. What genre + monetization combinations work best?  
5. Based on all insights, what type of game should the studio build next?  

---

## 🛠 2️⃣ Data & Tools

- **Data Source:**  
  Steam public dataset from Kaggle: [Steam Store Games Dataset](https://www.kaggle.com/datasets/nikdavis/steam-store-games)  

- **Tools Used:**  
  - **Excel:** Data cleaning, aggregation, pivot tables, feature engineering  
  - **Tableau:** Dashboard visualization  

**Rationale:** Excel provided transparency and precise calculations; Tableau made insights visually clear and interactive.  

---

## 📊 3️⃣ Analytical Approach

- **Data Cleaning:**  
  - Removed duplicates and incomplete entries  
  - Standardized genre names  
  - Exploded multi-value genre columns for accurate analysis  

- **Feature Engineering:**  
  - Created engagement metrics: Avg. playtime per user, peak concurrent users  
  - Derived monetization and multiplayer indicators  

- **Metrics Chosen:**  
  - Engagement = Avg. playtime  
  - Performance = User growth and revenue potential proxies  

**Workflow Overview:**  
- Raw Data → Cleaning → Feature Engineering → Pivot Tables → Tableau Dashboard → Insights

---

## 💡 4️⃣ Key Insights

| Question | Insight |
|----------|---------|
| **Top-Engagement Genres** | RPGs have the highest average playtime, followed by Adventure and Strategy games. |
| **Free-to-Play vs Paid** | Paid games generally have higher review scores but lower average playtime compared to Free-to-Play. |
| **Multiplayer vs Single-Player** | Single-player games have higher satisfaction (review scores), while multiplayer games drive longer play sessions. |
| **Best Genre + Monetization Combos** | Free RPGs and Paid RPGs show the highest playtime; Free Adventure and Paid Strategy are close second and third. |
| **Final Recommendation** | Build a **Paid, Single-Player RPG or Strategy game** to maximize player engagement and review sentiment. |

*Mini snapshot of pivot table example:*  
![Pivot Table Example](images/pivot_table_example.png)

---

## 🎯 5️⃣ Recommendation

- Focus on a **paid, single-player RPG or Strategy title**  
- Maximizes **review scores** (player satisfaction) and **average playtime** (engagement)  
- Aligns with trends observed in historical Steam data  

---

## ⚠️ 6️⃣ Limitations & Next Steps

**Limitations:**  
- Steam data may not reflect global trends outside Steam  
- Review scores and engagement are approximations and may not capture long-term retention  

**Next Steps:**  
- Collect player sentiment or review text data for deeper insight  
- Run A/B tests on early prototypes  
- Monitor engagement post-launch to refine strategy  

---

## 📊 7️⃣ Dashboard

![Steam Game Analysis Dashboard](dashboard/steam_dashboard_screenshot.png)  

Interactive version: [View Tableau Dashboard](https://public.tableau.com/app/profile/carlos.abrego/viz/SteamMarketAnalysisDashboard/Dashboard2#3)

---

## 📁 8️⃣ Excel Files & Workflow

| File | Description |
|------|-------------|
| `steam_analysis.xlsx` | Single annotated Excel workbook containing raw data (read-only), cleaned data, and pivot tables for analysis |

**Workflow Summary:** Excel → Tableau → Insights → Recommendations

---

**Explore the Excel workbook and dashboard to see the full analysis workflow.**

