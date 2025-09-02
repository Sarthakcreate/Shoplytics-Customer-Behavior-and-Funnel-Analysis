# 🛍️ E-Commerce Customer Behavior Analysis  

## 📖 Project Overview  
This project analyzes customer purchase behaviors and conversion funnels using an e-commerce dataset containing **4.1 million+ user events**.  
The goal is to uncover insights on customer churn, repeat purchases, conversion rates, and personalized recommendations.  

Key aspects:  
- **SQL + Python** workflow for data exploration and analysis  
- **Customer funnel visualization** (View → Add to Cart → Purchase)  
- **Hypothesis testing** on product recommendations and repeat purchases  
- **User-level behavior analysis** for personalization  

---

## ⚙️ Steps & Workflow  

### 1. Data Exploration  
- Cleaned and aggregated raw event data (views, add-to-cart, purchases).  
- Validated total purchase records (**391,055**) vs earlier benchmarks.  

### 2. Funnel Analysis  
- Created a **conversion funnel**:  
  - Views → Add to Cart → Purchases  
- Visualized with Plotly funnel chart to identify major drop-off stages.  

### 3. Hypothesis Testing  
- **H1**: Website recommended products may not align with user preferences.  
  - Compared **Top 100 viewed vs. Top 100 purchased products** → only limited overlap.  
- **H2**: Low repeat purchase rate indicates potential dissatisfaction.  
  - Only **42.2% of users purchased 2+ times**.  
  - Product-level repeat rate: ~42%.  

### 4. Time-based Analysis  
- Identified **most active hours** and **most active days** for user engagement.  
- Peak browsing at **8–10 PM** with highest purchase activity.  

### 5. Customer Behavior Case Study  
- Deep-dived into **top customer (User ID: 601469771)**.  
- Purchases spread across multiple products → but **category-level preferences** were visible.  
- Recommendation system opportunity: **category-based personalization**.  

---

## 📊 Visualizations  
- Conversion Funnel Chart  
- Active Users per Day 
- Active Users per Hour 
- Repeat Purchase Distribution  

---

## 💡 Insights  
1. **Major churn at "Add to Cart" → Purchase stage** → checkout optimization needed.  
2. **Low repeat purchase rate** (42%) suggests product/service gaps.  
3. **Top-viewed vs. top-purchased products mismatch** indicates recommendation inefficiency.  
4. **Personalization by category** can improve customer retention.  

---

## 🛠️ Tech Stack  
- **SQL** → data aggregation  
- **Python (Pandas, NumPy)** → analysis  
- **Plotly, Matplotlib, Seaborn** → visualizations  
- **Jupyter Notebook** for exploration  

---

## 🚀 Next Steps  
- Build a **category-level recommendation system**  
- Predict churn probability per user  
- A/B test different checkout flows  
---
