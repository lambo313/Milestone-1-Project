# The Evolving Beauty Industry: Balancing Safety, Pricing, and Consumer Trust  

**By:** Kristine Zhou, Cedric Lambert, Yingying Sun  

---

## 📌 Overview  
This project explores how regulatory changes, ingredient transparency, and shifting consumer expectations impact the global beauty industry. Using large-scale datasets, we analyze how brands adapt their formulations, pricing strategies, and product lines in response to evolving definitions of **“clean beauty.”**  

Our focus:  
- How do brands maintain competitive pricing while meeting safety standards?  
- What role does ingredient transparency play in shaping consumer trust and loyalty?  
- Do product discontinuations or ingredient removals affect brand performance metrics such as ratings and prices?  

---

## 📂 Data Sources  

- **CDPH Product & Ingredient Dataset** (California Department of Public Health)  
  - 718,660+ observations (2009–2024) on cosmetic ingredients, product submissions, discontinuations, and removals.  
  - [CDPH Safe Cosmetics Program Search](https://cscpsearch.cdph.ca.gov/search/publicsearch)  

- **Top Beauty & Cosmetics Products Worldwide 2024 (Kaggle)**  
  - 15,000 observations on brand, price, ratings, and reviews.  
  - [Dataset Link](https://www.kaggle.com/datasets/waqi786/most-used-beauty-cosmetics-products-in-the-world)  

---

## ⚙️ Methods  

- **Data Wrangling:** Cleaning, merging, and aggregating two large datasets.  
- **Regression Analysis:** Examined how product reporting (2009–2024) influenced 2024 ratings and prices.  
- **Visualization:** Scatter plots to explore relationships between product counts, discontinuations, ingredient removals, and brand performance.  

---

## 📊 Key Findings  

### Impact on Ratings  
- R² = **0.0054** → Reported product counts have negligible effect on 2024 average ratings.  

### Impact on Pricing  
- R² = **0.0032** → Minimal relationship between reported products and average pricing in 2024.  

### Consumer Trust  
- Transparency and ingredient safety drive stronger consumer perceptions than raw product counts.  
- Surveys show:  
  - **60%** expect brands to disclose ingredient sources.  
  - **72%** want clear explanations of ingredient functions.  
  - **63%** value “clean beauty” as *extremely or very important* when selecting products.  

---

## 📉 Visualizations  

- **Average Rating vs. Product Reporting (2009–2024)**  
  - Marker size = number of ingredient removals  
  - Color intensity = discontinued product counts  

- **Average Price vs. Product Reporting (2009–2024)**  
  - Marker style = brand distinction  
  - Marker size = ingredient removals  
  - Color intensity = discontinued products  

Both plots confirm **weak explanatory power**, suggesting broader market/consumer dynamics shape ratings and pricing.  

---

## 🤝 Collaboration  

This project was characterized by strong teamwork and iterative feedback:  

- **Data Acquisition & Cleaning**  
- **Regression Analysis**  
- **Visualization Design**  
- **Interpretation & Reporting**  

**Cedric Lambert**: Oversaw data pipeline, conducted regression analyses, created scatter plots, and co-authored the analysis/code notebook.  

---

## 📚 References  

1. [Lignopure (2024) – Transparency in the Cosmetic Industry](https://www.lignopure.com/importance-of-transparency-in-the-cosmetic-industry)  
2. [Cosmetics Business (2024) – Clean Beauty Insights](https://cosmeticsbusiness.com/68-of-consumers-seek-clean-beauty-information-and)  
3. [Cleanhub (2023) – Clean Beauty Survey](https://www.cleanhub.com/clean-beauty-survey)  

---

✨ This project highlights how **safety regulations** and **consumer trust**, rather than product counts, are shaping the future of the beauty industry.  
