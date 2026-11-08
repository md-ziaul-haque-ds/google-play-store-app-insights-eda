# 📱 App Insights Unlocked — Google Play Store App Performance Analysis

**Exploratory Data Analysis | Python | Pandas | NumPy | Matplotlib | Seaborn**

## 1. Project Overview

App Insights Unlocked is an Exploratory Data Analysis (EDA) project focused on understanding the Google Play Store application ecosystem.

The project explores application categories, ratings, installations, reviews, pricing, app sizes, and update patterns to identify meaningful trends and business insights.

**Objective:** Analyze Google Play Store applications to identify factors associated with app popularity, user engagement, ratings, pricing, and application characteristics.

**Dataset:** Google Play Store Apps Dataset

**Final Dataset:** 10,357 records and 17 columns after data cleaning and feature engineering.

## 2. Project Objectives

- Identify application categories with high representation and user ratings.
- Understand installation and user engagement patterns.
- Analyze the relationship between application size and ratings.
- Compare free and paid applications.
- Explore pricing patterns and user satisfaction.
- Examine content ratings and application update trends.
- Identify correlations between numerical variables.
- Develop data-driven business recommendations.

## 3. Tools & Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook

## 4. Dataset Overview

The dataset contains information about applications listed on Google Play Store.

| Description | Records / Columns |
|---|---:|
| Original records | 10,841 |
| Original columns | 13 |
| Final records | 10,357 |
| Final columns | 17 |

Key attributes include App, Category, Rating, Reviews, Size, Installs, Type, Price, Content Rating, Genres, Last Updated, Current Version, and Android Version.

## 5. Data Cleaning & Preparation

The following data preparation steps were performed:

1. Dataset loading and initial inspection.
2. Data quality assessment.
3. Missing value treatment.
4. Exact duplicate detection and removal.
5. Data type conversion.
6. Text standardization checks.
7. Feature engineering.

### Feature Engineering

The following features were created:

- **Update Year:** Extracted from the Last Updated column.
- **Update Month:** Extracted from the Last Updated column.
- **Install Group:** Categorized applications into Low, Moderate, High, Very High, and Massive installation groups.
- **Price Group:** Classified applications into Free, Budget, Standard, Premium, and High-Priced groups.
- **Log Reviews:** Created using logarithmic transformation to handle the highly skewed review-count distribution.

## 6. Exploratory Data Analysis (EDA)

The project covers the following analytical areas:

1. Rating Analysis
2. Category Analysis
3. Install Analysis
4. App Size Analysis
5. Price Analysis
6. Reviews Analysis
7. Content Rating Analysis
8. Time-Based Analysis
9. Correlation Analysis
10. Advanced Group-Wise Analysis

### Visualization Techniques

- Histograms and distribution plots
- Count plots and bar charts
- Scatter plots
- Line charts
- Correlation heatmaps
- Group-wise performance comparisons

## 7. Key Business Insights

Based on the analysis, the following findings were identified:

| No. | Area | Key Finding |
|---:|---|---|
| 1 | App Ratings | Average rating is approximately 4.19, indicating generally positive user feedback. |
| 2 | Categories | FAMILY has the highest number of apps (1,943), while EVENTS has the highest average rating (4.44). |
| 3 | Installs | The top 10 unique apps all have recorded installation thresholds of 1 billion+. |
| 4 | Install Groups | Massive-install apps have the highest average rating (4.34). |
| 5 | App Size | Average app size is 21.29 MB, while the median is 13 MB. |
| 6 | Pricing | Approximately 92.61% of apps are free and 7.39% are paid. |
| 7 | Paid vs Free | Paid apps have a slightly higher average rating (4.26) than free apps (4.18). |
| 8 | Reviews | Review counts are highly right-skewed, meaning a small number of apps receive a disproportionately large number of reviews. |
| 9 | User Engagement | Reviews and installs have a moderate positive correlation of 0.63. |
| 10 | Content Rating | Everyone-rated apps dominate the dataset with 8,382 applications. |
| 11 | Updates | Most recorded app updates occurred in 2018, with July having the highest monthly update count. |
| 12 | Price vs Rating | Budget-priced apps have the highest average rating (4.30) among the price groups. |

## 8. Business Recommendations

Based on these findings, companies and app developers can consider the following strategies:

### 1. Focus on User Experience
Since the average app rating is relatively high, developers should continue improving usability, application stability, performance, and customer satisfaction.

### 2. Choose Categories Strategically
Categories with higher app counts may have greater competition. Developers should identify underserved user needs instead of entering crowded categories without differentiation.

### 3. Improve User Engagement
The moderate positive correlation between installs and reviews suggests that popular apps often generate more user engagement. Developers should encourage meaningful user feedback and build features that support user retention.

### 4. Optimize App Size
Most apps are relatively small. Developers should optimize application size while maintaining useful features and performance.

### 5. Develop an Appropriate Pricing Strategy
Free apps dominate the dataset. Developers should evaluate freemium models, advertisements, subscriptions, and in-app purchases rather than relying exclusively on paid downloads.

### 6. Maintain Regular Updates
Regular improvements, bug fixes, and feature enhancements can help maintain application quality and user satisfaction.

### 7. Monitor User Feedback
Review analysis can help businesses identify user concerns, product weaknesses, and opportunities for improvement.

## 9. Project Limitations

Every data analysis project has limitations. The following factors should be considered when interpreting the findings:

1. **Historical Dataset:** The dataset primarily contains information up to 2018, so findings may not represent current Google Play Store trends.

2. **Install Thresholds:** Install values originally contained `+` suffixes. After cleaning, they represent recorded thresholds rather than exact download counts.

3. **Missing Values:** Some ratings and app sizes were unavailable. These values were retained as missing rather than introducing unsupported assumptions.

4. **Correlation vs Causation:** Correlation does not establish that one variable causes another.

5. **Limited User Feedback:** The dataset contains review counts but not review text, so detailed sentiment analysis was not possible.

6. **Potential Sampling Bias:** The dataset may not represent every application available on Google Play Store.

## 10. Final Project Conclusion

This project analyzed 10,357 Google Play Store applications to understand the factors associated with app popularity, user engagement, ratings, pricing, and application characteristics.

Using Python, Pandas, NumPy, Matplotlib, and Seaborn, the analysis covered data cleaning, missing-value treatment, duplicate removal, data type conversion, text standardization, feature engineering, and exploratory data analysis.

The findings revealed that free applications dominate the dataset, user ratings are generally positive, and applications with higher install counts tend to receive more reviews. A moderate positive correlation of 0.63 was observed between installs and reviews. However, ratings showed relatively weak relationships with most numerical variables.

The analysis also highlighted differences across app categories, pricing groups, application sizes, content ratings, and update patterns.

Overall, this project demonstrates how data analytics can transform raw application data into meaningful business insights. These insights can support better decisions regarding application development, pricing strategies, user engagement, and product improvement.

---

## 👨‍💻 Author

**MD Ziaul Haque**

Data Analyst | Business Analyst

- **LinkedIn:** [Connect with me](https://www.linkedin.com/in/mdziaulhaque-datascience/)
- **GitHub:** [Explore my projects](https://github.com/md-ziaul-haque-ds)

---

*Thank you for exploring this project!*
