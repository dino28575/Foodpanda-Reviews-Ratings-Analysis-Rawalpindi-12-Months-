# 📊 Foodpanda Rawalpindi Ratings Analysis

This project analyzes Foodpanda customer reviews and restaurant ratings in Rawalpindi, Pakistan, using the Google Data Analytics methodology (Ask, Prepare, Process, Analyze, Share). The goal was to identify the best-performing food vendors and food categories over the past year.

🔄 **Update [July 2025]:**
An earlier version of this project noted that "Healthy Food" was the highest-rated category. Upon further review, this was based on only one review and does not represent a reliable average. A revised analysis now excludes categories with fewer than 5 entries to ensure statistical significance. Thanks to this refinement, Dessert , Pulao and Pakistani food categories now appear as top performers based on meaningful sample sizes.


## 📁 Dataset

- Source: [Kaggle – BwandoWando](https://doi.org/10.34740/kaggle/ds/4683556)
- Files used:
  - `pk_rawalpindi_restos.csv`
  - `pk_rawalpindi_review.csv`

## 🧠 Questions Asked

- Which restaurants have the highest customer satisfaction?
- What food categories are most loved in Rawalpindi?
- Do 5-star reviews correlate with review volume?
- Which vendors consistently appear in both ratings and review comments?

## 🛠 Tools Used

- Google BigQuery (SQL filtering)
- Google Sheets (cleaning, pivot tables, charts)
- PDF Reporting
- Manual review-matching

## 🧼 Process

- Removed irrelevant columns
- Converted review text fields into structured insights
- Split timestamps into date/time
- Filtered for 5-star reviews only
- Merged datasets via Store ID

## 📊 Key Findings

- 🥇 **Anna Ka Khana** had the highest average rating (4.8⭐) and over 1000 reviews.
- 🥗 **Desert,Pulao and Pakistani** category showed the highest average satisfaction (avg ~4.6⭐).
- 🍽️ Repeated top performers included *Haute Cuisine*,*Foodies kitchen*, *Zaiqedaar by Chef Ayesha*, *Pinch of Spices*, and *Home Made Bites*.

## ✅ Outcome

This project demonstrated descriptive and diagnostic analysis, data cleaning, SQL filtering, and stakeholder reporting.  
It follows the complete Google Data Analytics workflow and is portfolio-ready.

### 📬 Contact

Made with ❤️ by Sahib Dino
If you'd like to discuss this project or similar work, feel free to reach out:  
📧 sahib28575@gmail.com
