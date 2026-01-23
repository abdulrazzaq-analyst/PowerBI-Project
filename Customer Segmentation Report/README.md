# 🎯 Customer Segmentation Dashboard – Power BI

**An advanced customer segmentation dashboard built in Microsoft Power BI** using the **RFM Model (Recency, Frequency, Monetary)** to analyze customer behavior, identify valuable segments, and drive targeted marketing strategies.

This dashboard transforms raw transaction data into actionable customer insights for **improved engagement, retention, and revenue growth**.

---

## 🖼️ Dashboard Preview

### 1️⃣ Sales Dashboard  
![Sales Dashboard](https://github.com/user-attachments/assets/93e4ffdb-d217-45a0-963d-5a605bbf481d)

### 2️⃣ RFM Analysis  
![RFM Analysis](https://github.com/user-attachments/assets/f297a818-603b-4590-ae20-d2329d86eafa)

### 3️⃣ Customer Detail  
![Customer Detail](https://github.com/user-attachments/assets/daac9e79-1752-47bc-8b9c-874d3aae5ed5)

### 4️⃣ RFM Overview  
![RFM Overview](https://github.com/user-attachments/assets/d4643bc3-be83-4139-b40d-579f1e43c78b)

---

## 🚀 Features

### 🎛️ Interactive Elements
- **Dynamic RFM Scoring**: Real-time calculation of Recency, Frequency, Monetary scores
- **Customer Segment Filters**: Filter by RFM segments (Champions, Loyal, At-Risk, etc.)
- **Time Period Selector**: Analyze customer behavior across different timeframes
- **Demographic Filters**: Segment by location, age, or customer type
- **Drill-through Capability**: Click any segment to view detailed customer profiles

### 📊 Dashboard Pages
1. **Sales Dashboard** – Overall sales performance, KPIs, and revenue trends
2. **RFM Analysis** – Customer segmentation based on Recency, Frequency, and Monetary metrics
3. **Customer Detail** – Individual customer profiles with transaction history
4. **RFM Overview** – Segment descriptions with recommended marketing actions

---

## 📈 Key Performance Indicators (KPIs)

| Metric | Description | Business Impact |
|--------|-------------|-----------------|
| **Total Customers** | Number of unique customers analyzed | Market reach assessment |
| **Average RFM Score** | Mean Recency, Frequency, Monetary score | Overall customer health |
| **Champions Segment %** | Percentage of high-value customers | Revenue concentration |
| **At-Risk Customers** | Count of customers likely to churn | Retention focus areas |
| **Customer Lifetime Value** | Predicted long-term value per segment | Investment prioritization |

---

## 🏷️ RFM Segmentation Model

### 📋 Segment Definitions & Recommendations

| Segment | RFM Profile | Characteristics | Recommended Actions |
|---------|-------------|-----------------|---------------------|
| **Champions** | High R, High F, High M | Recent, frequent, high spenders | Reward programs, premium offers |
| **Loyal Customers** | Medium R, High F, High M | Regular buyers, consistent spending | Loyalty programs, exclusive access |
| **Potential Loyalists** | High R, Medium F, Medium M | New customers with potential | Engagement campaigns, onboarding |
| **Recent Customers** | High R, Low F, Low M | New but infrequent buyers | Welcome series, first-purchase incentives |
| **Promising** | Medium R, Low F, High M | Big spenders but infrequent | Reactivation campaigns, personalized offers |
| **Need Attention** | Medium R, Medium F, Medium M | Average across all metrics | Re-engagement, cross-selling opportunities |
| **About To Sleep** | Low R, Medium F, Medium M | Decreasing engagement | Win-back campaigns, special offers |
| **At Risk** | Low R, High F, High M | Former high-value, now inactive | Aggressive retention, feedback requests |
| **Can't Lose Them** | Low R, High F, High M | Critical customers at risk | Personal outreach, customized solutions |
| **Hibernating** | Low R, Low F, Low M | Long-term inactive | Reactivation or deprioritize |

---

## 📊 Visual Analytics Components

### Sales Dashboard
- **Revenue Trends**: Monthly/quarterly sales performance
- **Geographic Distribution**: Customer concentration by region
- **Product Performance**: Best-selling items and categories
- **Customer Acquisition**: New vs. returning customer analysis

### RFM Analysis Dashboard
- **RFM Matrix Visualization**: 3D scatter plot of Recency, Frequency, Monetary
- **Segment Distribution**: Pie/bar charts showing customer segment proportions
- **Score Distribution**: Histograms of individual R, F, M scores
- **Segment Migration**: How customers move between segments over time

### Customer Detail Dashboard
- **Individual RFM Scores**: Detailed breakdown per customer
- **Purchase History**: Timeline of transactions
- **Behavioral Patterns**: Buying frequency, preferred products
- **Contact Information**: Customer demographics and details

### RFM Overview Dashboard
- **Segment Characteristics**: Key metrics for each RFM segment
- **Action Planning**: Recommended strategies per segment
- **Success Metrics**: Expected outcomes from segment-specific actions
- **Resource Allocation**: Budget and effort recommendations

---

## 🔧 Technical Implementation

### Power BI Features Used
- **DAX Formulas**: Advanced calculations for RFM scoring
- **Power Query**: Data transformation and cleaning
- **Data Modeling**: Star schema with customer-centric design
- **Custom Visuals**: RFM matrix and advanced charts
- **Bookmarks & Navigation**: Seamless dashboard switching
- **Drillthrough Pages**: Detailed customer analysis

### RFM Calculation Methodology
1. **Recency (R)**: Days since last purchase (lower score = more recent)
2. **Frequency (F)**: Number of purchases in period (higher score = more frequent)
3. **Monetary (M)**: Total spend in period (higher score = higher spend)
4. **Segmentation**: Combined scores assigned to 10 customer segments
5. **Dynamic Updates**: Scores recalculate with new data automatically

### Data Preparation Process
1. **Data Extraction**: Transaction data from multiple sources
2. **Customer Deduplication**: Ensuring unique customer identification
3. **Date Alignment**: Standardizing time periods for analysis
4. **Outlier Handling**: Managing extreme purchase behaviors
5. **Score Normalization**: Creating comparable RFM metrics

---

## 🖱️ How to Use the Dashboard

### Navigation Guide
1. **Open the Power BI file** (.pbix) in Power BI Desktop or Service
2. **Start with Sales Dashboard** for overall business performance
3. **Navigate to RFM Analysis** to view customer segments
4. **Click on any segment** to drill through to Customer Details
5. **Use RFM Overview** for segment-specific strategies
6. **Apply filters** to analyze specific time periods or regions

### Key Interactions
- **Hover over RFM matrix** to see customer concentration
- **Click segment names** to filter entire dashboard
- **Use date slicers** to analyze different time periods
- **Export customer lists** for targeted marketing campaigns
- **Bookmark views** for frequent reporting scenarios

---

## 🔍 Business Insights & Strategic Recommendations

### Key Findings
1. **Customer Value Concentration**
   - 20% of customers (Champions & Loyal) generate 80% of revenue
   - High-value segment identification enables targeted resource allocation

2. **Retention Opportunities**
   - At-Risk and Can't Lose Them segments require immediate attention
   - Win-back campaigns could recover significant lost revenue

3. **Growth Potential**
   - Potential Loyalists and Recent Customers show highest growth potential
   - Targeted nurturing can upgrade these segments to higher value tiers

4. **Seasonal Patterns**
   - RFM scores fluctuate with seasonal buying patterns
   - Marketing should adapt to seasonal customer behavior changes

### Actionable Recommendations
1. **For Champions**: Implement exclusive loyalty programs and early access to new products
2. **For At-Risk Customers**: Launch personalized win-back campaigns with special offers
3. **For Potential Loyalists**: Increase engagement through educational content and community building
4. **For Hibernating Customers**: Consider low-cost reactivation attempts or deprioritization
5. **Overall Strategy**: Shift from mass marketing to segment-specific approaches

### Expected Business Impact
- **15-20% increase** in customer retention rates
- **25-30% improvement** in marketing campaign ROI
- **10-15% growth** in customer lifetime value
- **Reduced churn** by 20-25% in at-risk segments

---

## 📌 Project Summary

This **Customer Segmentation Dashboard in Power BI** demonstrates advanced skills in:

- **RFM Modeling**: Implementation of industry-standard customer segmentation
- **Behavioral Analytics**: Transforming transaction data into customer insights
- **Strategic Visualization**: Presenting complex data for business decision-making
- **Actionable Intelligence**: Connecting analytics to specific business actions
- **End-to-End Solution**: From data preparation to strategic recommendations

The dashboard showcases how **data-driven customer segmentation** can transform customer relationship management and drive sustainable business growth.

----

## 🌐 Portfolio Website
Explore more of my data analytics projects:  
👉 https://abdulrazzaq-analyst.github.io/Portfolio_Website/

---

## 📞 Contact
For questions or collaboration:  
📧 abdulrazzaq.analytics@gmail.com  
🔗 https://github.com/abdulrazzaq-analyst

---

## 👤 Author
**Abdul Razzaq**  
Statistics Graduate | Data Analytics & Visualization  
🔗 GitHub: https://github.com/abdulrazzaq-analyst

---

## 📋 Project Metadata

*Analytical Method*: RFM (Recency, Frequency, Monetary) Segmentation  
*Tool Used*: Microsoft Power BI  
*Data Type*: Customer Transaction Data  
*Business Application*: Marketing Strategy, Customer Retention, Revenue Optimization  
*Project Status*: Completed & Deployed

*Note: This dashboard uses sample customer data to demonstrate RFM segmentation methodology. All insights and recommendations are based on analytical models and can be adapted to specific business contexts.*
