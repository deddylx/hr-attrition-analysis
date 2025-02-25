# Paid Search Campaign Analysis
## Overview
Conducted analysis in SQL and Python to uncover insights on campaign performance and customer engagement for a Kaggle-derived Shopping Mall Paid Search Campaign dataset containing a 5-months ad records. Worked independently for two weeks to clean, transform, and analyze the data, identifying key metrics such as click-through rates (CTR), cost-per-click (CPC), and return on ad spend (ROAS). Built an interactive dashboard in Tableau to visualize trends related to campaign performance and ad spend efficiency. Delivered actionable insights and recommendations for the marketing team, focusing on optimizing ad spend allocation and improving campaign targeting strategies.

## Tools and Technologies
- **SQL**: PostgreSQL for data cleaning, transformation, and querying.
- **Python**: Pandas, NumPy, Matplotlib, and Seaborn for data analysis and visualization.
- **Visualization**: Tableau for creating interactive dashboards.
- **Version Control**: GitHub for project documentation and code sharing.

## Dataset
Source: [Shopping Mall Paid Search Campaign Dataset](https://www.kaggle.com/datasets/marceaxl82/shopping-mall-paid-search-campaign-dataset)

Description: The dataset contains information about the ad group advertising, clicks, conversions, impressions, revenues and costs with the following columns:
- `Ad Group`: category of the advert (coupon/promo code, desktop ad/mobile ad etc…)
- `Month`: month of the campaign. The campaign started in July 2021 and ended in November 2021.
- `Impressions`: metric used in digital marketing to quantify the number of digital views or engagements of an advertisement. Impressions are also referred to as an "ad view.
- `Clicks`: how many clicks the ad received
- `CTR`: Click Through Rate, the number of clicks that your ad receives divided by the number of times your ad is shown: clicks ÷ impressions = CTR.
- `Conversions`: Conversions are those valuable actions that users take on your site like buying something or filling in a form. The success can be measured in the number of conversions generated at a particular cost.
- `Conv Rate`: Conversion Rate. It is the percentage of people who convert after clicking on your ads. Depending on your goals, a conversion may mean they make a purchase, complete a contact form, request a free trial, or take another desired action.
- `Cost`: Cost is the actual money spent by the advertiser (the "shop") for the related ad group.
- `CPC`: Cost Per Click, it is the cost of the specific ads divided by the click. It is one of the metrics used to evaluate the effectiveness of the campaign in terms of ROI (Return on Investment), therefore a low or decreasing CPC is better than a high or increasing CPC.
- `Revenue`: Revenue is the total amount of income generated by advertisment.
- `Sale Amount`: Sale Amount for this dataset means the quantity of sales derived by the single ad group.
- `P&L`: Profit and Loss, based on the formula Revenue - Cost. For this dataset mesaures the profit of the specific Ad Group.

## Project Workflow
1. **Data Loading and Cleaning**
   - The dataset was downloaded from Kaggle and loaded into PostgreSQL.
   - SQL was used to clean the data:
     - Checked and removed duplicate rows.
     - Checked and handled missing values.
     - Transformed the date column into the correct DATE type for easier time-based analysis.
     - Split the ad_group text column into three parts for better granularity.
     - Calculated key metrics such as CTR, CPC, and ROAS.
2. **Data Analysis with Python**
   - The cleaned data was extracted from PostgreSQL and analyzed using Python.
   - Key analyses performed:
     - Total sales and profit by category
     - Sales trends over time
     - Top-performing products and regions
3. **Dashboard Creation**
   - The analyzed data was used to create an interactive dashboard in Tableau/Power BI.
   - Key visualizations:
     - Sales trends over time (line chart).
     - Top-performing products (bar chart).
     - Regional sales performance (map).

## Project Structure
```
shopping-mall-campaign-analysis/
├── data/
│   └── shopping_mall_campaign_data.csv
├── sql_scripts/
│   └── data_cleaning.sql
├── notebooks/
│   └── analysis.ipynb
├── dashboard/
│   └── campaign_dashboard.twb
├── images/
│   └── dashboard_screenshot.png
└── README.md
```
## Dashboard
The dashboard can be found in Tableau Public [here](https://public.tableau.com/shared/N7Z7344QJ?:display_count=n&:origin=viz_share_link). This dashboard enables users to filter by device type, match type, and ad type, and focuses on trends and values in marketing metrics.

<img width="1203" alt="Screenshot 2025-02-19 at 16 10 07" src="https://github.com/user-attachments/assets/95c1f21d-92f6-4488-bbf9-b910525efc53" />

<img width="1209" alt="paid campaign analysis" src="https://github.com/user-attachments/assets/a62d6215-e49e-42b3-b678-1cae163df3ee" />



## Key Insights
1. **Seasonal Campaigns Drive Performance**  
   - Black Friday/Cyber Monday campaigns achieved the highest **Return on Ad Spend (ROAS) of 9.32** and the highest **conversion rate of 19.09%**, indicating strong performance during peak shopping periods.  

2. **Device Performance: Desktop vs. Mobile**  
   - **Desktop campaigns** delivered higher **conversion rates (15.24%)** and **ROAS (1.18)** despite a higher **Cost Per Click (CPC)**.  
   - **Mobile campaigns** generated higher **Click-Through Rates (CTR) of 41.45%**, but conversion rates were lower, suggesting a need for further optimization.  

3. **Promo and Coupon Codes Increase Engagement**  
   - Ads featuring promo and coupon codes achieved the highest **CTR (41.45%)**, demonstrating strong user interest. However, the **ROAS (0.92)** was lower, indicating the need for strategic adjustments to improve profitability.  

4. **Match Type Efficiency**  
   - **Phrase match campaigns** provided the highest **ROAS (1.13)**, making them the most cost-effective targeting strategy.  
   - **1:1 match campaigns** had the highest **CTR (38.68%)**, making them valuable for engagement-focused advertising.  

5. **Budget Optimization Strategies**  
   - Increasing investment in **high-ROAS campaigns** such as Black Friday and free shipping promotions.  
   - Optimizing **mobile campaigns** to improve conversion rates through refined ad copy and landing pages.  
   - Prioritizing **phrase match targeting** to enhance cost efficiency and maximize returns.  

## **Next Steps**  

- Reallocate budgets toward high-performing campaigns to maximize ROI.  
- Optimize mobile campaigns by improving ad copy, landing page experience, and targeting.  
- Focus on phrase match campaigns to improve efficiency and return on ad spend.  
- Plan ahead for seasonal campaigns to capitalize on high-conversion periods.

## Contact
For questions or feedback, feel free to reach out:
- Name: Deddy Laudryansyah Putra
- Email: ldeddy25@gmail.com
- LinkedIn: [@deddyl](https://www.linkedin.com/in/deddyl/)
- GitHub: [deddylx](https://github.com/deddylx)
