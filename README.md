# 📊 EDA on Marketing Campaign Data

This project explores a large-scale marketing campaign dataset using **Exploratory Data Analysis (EDA)**. The objective is to uncover actionable insights that will guide decision-making in marketing strategy, campaign optimization, and audience targeting.

## 🎯 Objective

- Investigate campaign ROI, conversion rates, and engagement
- Identify high-performing vs. under-performing campaigns
- Compare marketing channel effectiveness
- Determine the most profitable audience segments and locations
- Track market trends over time

## 🧾 Dataset Overview

- **Rows**: 200,005
- **Columns**: 15  
- **Fields Include**:
  - `Campaign_ID`, `Company`, `Campaign_Type`, `Target_Audience`
  - `Channel_Used`, `ROI`, `Acquisition_Cost`, `Revenue`, `Profit`
  - `Date`, `Location`, `Clicks`, `Impressions`, `Customer_Segment`, etc.

## 🛠️ Tools Used

- Python (Pandas, NumPy)
- Data Visualization: Matplotlib, Seaborn
- Jupyter Notebook

## 🔍 Key Insights

### 💰 Revenue & Profit
- Average **Revenue**: \$75,091  
- **Alpha Innovations** generated the highest revenue overall.  
- Top companies by profit:  
  - `TechCorp`, `Alpha Innovations`, `DataTech Solutions`, `NexGen Systems`, `Innovate Industries`

### 📈 Channel Performance
| Channel       | CTR (%) | ROI | CPC ($) |
|---------------|---------|-----|----------|
| Website       | 10.02   | 5.01 | 22.62 |
| Google Ads    | 9.91    | 5.00 | 22.83 |
| Facebook      | 9.98    | 5.02 | 22.76 |

> Website had the highest CTR and relatively high ROI.

### 📢 Campaign Effectiveness
| Campaign Type   | CTR (%) | ROI |
|------------------|----------|------|
| Influencer       | 14.03    | 5.01 |
| Search           | 13.99    | 5.01 |
| Social Media     | 14.10    | 4.99 |

> Influencer campaigns performed best on average ROI and engagement.

### 🌍 Location Trends
- **Highest ROI**: Miami
- **Highest CTR**: Los Angeles
- **Least Efficient Spend**: August (highest cost, lowest ROI)

### 👥 Segment & Targeting
- Most Profitable Segments per Company:
  - `TechCorp`: Tech Enthusiasts
  - `NexGen Systems`: Outdoor Adventurers
  - `Alpha Innovations`: Foodies

- Best Target Audiences (by CTR & ROI):
  - `Women 25–34` and `Men 25–34` had top engagement rates

### 🧠 Market Trends
- CTR dropped in **June/July**, peaked in **October**
- High ad spend in **July** didn’t yield good ROI (inefficiency)
- Email + YouTube combo campaigns underperformed

## 📈 Sample Visuals

- Distribution plots: Revenue, CPC, CTR
- Time series: Revenue & ROI over time
- Heatmaps: Channel vs Campaign ROI
- Grouped bar charts for company performance

## 📁 Folder Structure

