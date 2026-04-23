🎬 Exploratory Data Analysis of IMDb Movies
📄 Report

The full analysis, including charts and detailed interpretations, is available here:
[View Full Report](https://docs.google.com/document/d/1bOiOmOASPUupjEOw2PrMGFQw8kxMucXiFz4qGZy6KFo/edit?usp=sharing)

📌 Overview

This project performs exploratory data analysis (EDA) on an IMDb movie dataset to identify patterns and relationships in movie ratings. The analysis focuses on understanding how different factors—such as genre, duration, popularity, directors, and critic scores, relate to audience ratings.

The goal is to move beyond basic statistics and extract meaningful, real-world insights through structured analysis and interpretation.

🎯 Objectives
• Analyze how genre influences IMDb ratings
• Examine whether movie duration affects ratings
• Explore the relationship between number of votes and ratings
• Identify top and bottom performing directors
• Compare IMDb ratings vs Metascores (critics vs audience)

📊 Dataset
- Source: IMDb dataset (via Kaggle)
- Size: 1000 movies × 11 features
- Key Variables:
- Movie Name
- Genre
- Duration
- IMDb Rating
- Metascore
- Votes
- Director
- Gross Earnings

🛠️ Tools & Techniques
- Google Sheets
	- Data cleaning & transformation
	- Pivot tables
	- Data aggregation
- Data Visualization
	- Bar charts
	- Scatter plots with trendlines
- Statistical Analysis
	- Correlation interpretation using R² (coefficient of determination)
	
🔍 Key Questions
1. Which genres have the highest average IMDb rating?
2. Are longer movies rated higher?
3. Is there a relationship between number of votes and ratings?
4. Which directors consistently achieve higher ratings?
5. Do IMDb ratings and Metascores align?

💡 Key Insights
- Genre has minimal impact on ratings
→ Most genres have similar average IMDb scores (≈7.9–8.1)
- Movie duration is not a strong factor
→ Weak relationship between runtime and ratings (R² ≈ 0.075)
- Popularity has a slight influence
→ Movies with more votes tend to have slightly higher ratings, but the relationship is weak (R² ≈ 0.241)
- Directors show limited variation
→ Even top and bottom directors maintain relatively high ratings, suggesting dataset bias toward well-rated films
- Critics and audiences often disagree
→ Weak relationship between IMDb ratings and Metascores (R² ≈ 0.066), reflecting different evaluation criteria

🧠 Key Takeaway

Movie ratings cannot be explained by a single measurable factor. Instead, they are influenced by a combination of subjective and qualitative elements, such as storytelling, execution, and audience perception.

⚠️ Limitations
Dataset consists mostly of highly rated/popular films, limiting variability
Missing factors such as:
- Budget
- Marketing
- Release timing
- Audience demographics
- Results may not generalize to all movies


📁 Project Structure
Movie-Rating-Data-Project--Exploratory-Data-Analysis-EDA/
│
├── analysis/      # Charts and working files
├── data/          # Raw dataset
├── report/        # Final report (PDF/Docs)
└── README.md

🚀 Skills Demonstrated
- Exploratory Data Analysis (EDA)
- Data Cleaning & Transformation
- Data Visualization
- Analytical Thinking
- Interpreting Statistical Relationships
- Communicating Data Insights

✨ Author Note

This project focuses on developing a structured approach to analyzing data going beyond surface-level observations to understand why patterns exist and what they imply in real-world contexts.
