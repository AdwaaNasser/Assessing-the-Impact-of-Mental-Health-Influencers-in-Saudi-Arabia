# Assessing-the-Impact-of-Mental-Health-Influencers-in-Saudi-Arabia

Project Overview

This data science project investigates how mental health influencers’ content relates to public engagement on social media in Saudi Arabia. It analyzes content published on YouTube and TikTok to identify the topics, creator characteristics, and content features associated with audience interaction.

Objectives

* Analyze engagement patterns across different mental health content themes.
* Identify factors associated with views, likes, comments, and shares.
* Compare audience engagement between YouTube and TikTok.
* Explore popular mental health topics and their engagement rates.
* Build regression models to predict content engagement rates.

Data Sources

The project uses publicly available social media data collected through API-based methods.

* YouTube: Video titles, descriptions, views, likes, comments, channel information, and video duration.
* TikTok: Video descriptions, views, likes, comments, shares, creator information, and publication dates.
* Secondary Dataset: User-level information about social media usage, screen time, sleep, physical activity, mood, stress, and anxiety.

The collected data includes Arabic and English content related to mental health in the Saudi context.

Tools and Technologies

* Python
* Pandas and NumPy
* Matplotlib and Seaborn
* Scikit-learn
* YouTube Data API v3
* RapidAPI
* Google Colab
* Statistical analysis and data visualization

Methodology

1. Data Collection: Retrieve public YouTube and TikTok content using API-based methods.
2. Data Cleaning: Remove duplicates, handle missing values, standardize data formats, and clean Arabic text.
3. Feature Engineering: Calculate engagement rates, categorize content topics, classify influencer tiers, and extract temporal features.
4. Exploratory Data Analysis (EDA): Examine engagement distributions, correlations, content themes, and platform differences.
5. Statistical Analysis: Apply Spearman correlation and the Mann–Whitney U test.
6. Predictive Modeling: Compare a baseline regression model, Linear Regression, and Random Forest Regressor.

Key Findings

* TikTok demonstrated higher engagement efficiency despite having fewer records than YouTube.
* YouTube contributed a larger volume of collected content.
* Views and likes showed a strong positive correlation.
* Self-development content achieved the highest median engagement rate among the analyzed themes.
* Random Forest Regressor outperformed the other evaluated models.

Model Performance

Model	R² Score	RMSE
Random Forest Regressor	0.738	1.589
Linear Regression	0.021	3.068
Dummy Regressor	-0.001	3.102

The Random Forest model achieved an R² score of approximately 0.74 on the evaluated test set.

Limitations

* Engagement metrics do not directly measure mental health awareness or psychological outcomes.
* The collected content may not represent all social media users in Saudi Arabia.
* The secondary dataset measures user well-being separately and does not directly establish the effect of influencer content.
* Platform data availability and API limitations may affect comparisons.

Future Improvements

* Apply Arabic Natural Language Processing techniques to better understand Saudi dialects.
* Improve cross-platform influencer identification.
* Explore additional predictive models and feature-selection techniques.
* Investigate video transcripts and visual features for deeper content analysis.



