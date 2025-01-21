# A/B Testing: Effectiveness of Advertising Platforms

This project analyzes the performance of two advertising platforms through an A/B test using daily campaign data from 2023. The primary objective is to identify which platform is more effective in terms of conversions, clicks, and cost-efficiency.

## Dataset Overview

The dataset used in this project contains daily metrics for two advertising platforms:

- **Timeframe**: January 1, 2023 – December 31, 2023 (365 rows)
- **Key Metrics**:
  - Daily clicks and conversions for Facebook Ads and AdWords.
  - Associated costs for each platform.

## Data Preprocessing

- The **Date** column was converted to DateTime format for time-series analysis.
- Descriptive statistics showed that the dataset is normally distributed, with mean and median values closely aligned.
- **Outliers** were retained due to their importance in campaign performance analysis.

## Analysis and Findings

### 1. Performance Metrics Comparison

- **Clicks**:
  - Facebook Ads showed a slightly higher click rate on most days.
  - AdWords clicks were more consistent throughout the year.

- **Conversions**:
  - Both platforms had comparable conversion rates, with no significant outliers.
  - The data was symmetric and well-distributed.

<img width="822" alt="image" src="https://github.com/user-attachments/assets/e697d6a1-bf72-429c-adb0-aebb2821204a" />


### 2. High vs. Low Conversion Days

- Conversion data was categorized to identify high and low-performing days:
  - Facebook Ads had more days with high conversions.
  - AdWords showed fewer, but more consistent, high-conversion days.
    
<img width="475" alt="image" src="https://github.com/user-attachments/assets/66cbe223-a5c5-4f5b-be99-e5e305182ea3" />

<img width="475" alt="image" src="https://github.com/user-attachments/assets/d37e72ac-7a84-47d4-9b4d-452b92951b73" />


### 3. Cost Efficiency

- A cost-per-conversion analysis indicated that AdWords provided better ROI on average, despite Facebook generating higher clicks and conversions.
  
<img width="571" alt="image" src="https://github.com/user-attachments/assets/8a4b0c5f-8e6f-4161-a407-47e82529ddbc" />


### 4. Visual Insights

- Histograms and KDE plots provided clarity on distribution patterns.
- Comparative visualizations helped stakeholders understand which platform aligned better with business objectives.

#### 5. Regression Analysis: Prediction of conversions to clicks

<img width="492" alt="image" src="https://github.com/user-attachments/assets/1cf78fd1-6c9e-41a4-815f-e0b67613d941" />


## Business Recommendations

Based on the analysis:

- **For High Conversions**: Invest in Facebook Ads, especially during peak campaign periods.
- **For Cost Efficiency**: Allocate a larger budget to AdWords, as it delivers better ROI.
- **Balanced Strategy**: Use a hybrid approach by leveraging Facebook for visibility and AdWords for consistent, cost-effective results.
