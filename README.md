# DSA210 Term Project: Analyzing Instagram Influencer Engagement

## 1. Motivation

## 2. Research Questions and Hypotheses
### Main Research Question

How do follower count, engagement rate, posting activity, and audience interaction affect influencer popularity on Instagram?

---

### Sub-Questions

- Do influencers with more followers always receive higher average likes?
- Is engagement rate strongly related to influence score?
- Does posting activity increase audience interaction?
- Are there observable engagement differences between influencers from different countries?
- Can machine learning models predict influencer engagement using Instagram metrics?

---

### Hypotheses

H1: Influencers with higher follower counts tend to receive higher average likes.

H2: Higher engagement rates are associated with higher influence scores.

H3: Posting activity positively affects total engagement.

H4: Engagement per follower differs among influencers from different countries.

H5: Follower count alone is not sufficient to explain engagement rate.

H0 (Null Hypothesis): Instagram engagement metrics do not have a statistically significant relationship with influencer popularity.

## 3. Data Source and Collection
The dataset used in this project contains Instagram influencer statistics collected from publicly available social media data sources.

The dataset includes numerical and categorical variables related to influencer popularity, engagement, and audience interaction.

Main variables used in the analysis:

- follower count
- average likes
- engagement rate
- total likes
- number of posts
- influence score
- country

During preprocessing, numerical abbreviations such as "k", "m", and "b" were converted into numerical values.

Percentage columns were cleaned and transformed into float variables for statistical analysis and machine learning implementation.

Missing values and duplicated rows were removed before analysis.

## 4. Data Description
| Variable | Description | Purpose |
|---|---|---|
| Followers | Total follower count of influencer | Measures popularity |
| Average Likes | Average likes per post | Measures audience interaction |
| Engagement Rate | Percentage of audience engagement | Main engagement metric |
| Total Likes | Overall received likes | Measures total interaction |
| Posts | Number of posts shared | Measures posting activity |
| Influence Score | Overall influencer popularity score | Target analysis variable |
| Country | Influencer country information | Used for group comparison |

## 5. Methodology
This project combines exploratory data analysis, statistical analysis, hypothesis testing, and machine learning techniques.

### Statistical Analysis

The following statistical methods were used:

- correlation analysis
- scatter plots
- log-log visualizations
- country-based comparisons
- engagement distribution analysis

The relationships between followers, likes, engagement rate, and influence score were examined using visualizations and correlation analysis.

Log-log plots were additionally used because influencer datasets contain extreme outliers with very large follower counts.

### Machine Learning

Machine learning models were implemented to predict influencer engagement and popularity using Instagram metrics.

The following features were used in the machine learning models:

- followers
- average likes
- engagement rate
- total likes
- posts

The dataset was divided into training and testing sets.

The following machine learning approaches were applied:

- Linear Regression
- Random Forest Regression

Performance evaluation metrics:

- R² Score
- Mean Absolute Error (MAE)

Feature importance analysis was also performed to determine which variables contribute most to influencer engagement prediction.

## 6. Figures and Visualizations

### Followers vs Average Likes
![Followers vs Average Likes](figures/followers_vs_likes.png)

This scatter plot shows the relationship between follower count and average likes.

Key observations:

- There is a moderate positive relationship between followers and average likes.
- Influencers with more followers generally receive more likes.
- However, the relationship is not perfectly linear because engagement also depends on content quality and audience interaction.

### Log-Log Relationship Plot

### Engagement Rate vs Influence Score

### Country-Based Engagement Comparison

### Actual vs Predicted Engagement

### Feature Importance – Random Forest

## 7. Machine Learning Validation

## 8. Coefficient Analysis

## 9. Conclusion

## 10. Limitations and Future Work

## 11. AI Usage and Academic Integrity
