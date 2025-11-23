# Customer Segmentation Analysis for Retail (Python + Power BI)

## Executive Summary
Mall customers behave differently depending on their age, income level, and buying habits. Treating everyone the same often leads to wasted marketing budget and low engagement.

Using Python (EDA + K-Means) and Power BI, I segmented 200 mall customers into **six behavioral clusters**.  
These clusters reveal clear opportunities to improve targeting, personalize communication, and increase customer engagement.

The greatest opportunities identified were:
- Prioritizing **high-income, high-spending customers** with premium offers  
- Re-engaging **high-income but low-spending** customers  
- Creating promotions for **young impulsive buyers**  

This segmentation gives marketing teams a data-driven view of who their customers are and how to communicate with them effectively.

---

## Business Problem
Marketing and product teams lacked visibility into customer behavior.  
Although the company had basic customer attributes — **age, gender, income level, and spending score** — this information was not structured into meaningful segments that could guide strategic decisions.

Key questions the business needed answered:
- What types of customers exist in our mall?
- Which groups show the highest spending potential?
- How do age and income influence purchasing behavior?
- How can we target different customer types with more precision?

This project uses clustering and dashboard analytics to transform raw customer data into actionable insights and meaningful customer segments.

---

## Methodology

### Python (EDA + Clustering)
- Explored distributions of age, income, and spending score  
- Created pairplots and scatterplots to visualize relationships  
- Applied **K-Means with 6 clusters**  
- Profiled each segment using median behavior metrics  

### Power BI (Business Visualization)
- Built a dashboard showing:
  - Total customers  
  - Average age, income, and spending score  
  - Customer distribution by generation and gender  
  - Cluster heatmap (Cluster × Generation)  

---

## Skills Demonstrated
- **Python:** Pandas, Scikit-Learn, Matplotlib, Seaborn  
- **Machine Learning:** K-Means clustering, model evaluation  
- **Power BI:** DAX, calculated columns, ETL, KPI design  
- **Data Storytelling:** cluster profiling, insights, recommendations  

---

## Results & Business Recommendations

### Final Customer Segments
1. **High Income, High Spending (Top Clients)**  
2. **High Income, Low Spending**  
3. **Low Income, High Spending (Young Spenders)**  
4. **Low Income, Low Spending**  
5. **Mid Income, Moderate Spending (Older Adults)**  
6. **Mid Income, Moderate Spending (Young Adults)**

![Customer Clusters](results/Customers_Cluster.png)


### Business Recommendations
- Launch exclusive programs for top spenders  
- Create reactivation campaigns for high-income customers with low spending  
- Use promotional campaigns for younger impulse-driven buyers  
- Maintain consistent value-driven communication for older moderate spenders  

These actions can increase engagement, improve conversion, and optimize marketing spend.

---

## Next Steps

### Business
- Run A/B tests targeting specific clusters  
- Create personalized marketing flows  
- Monitor segment evolution monthly  

---

## Project Structure

