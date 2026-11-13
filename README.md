## Marketing Campaign Performance Analysis
### 🎯Project Overview
This project was developed as part of the BCG X Data Science Job Simulation and focuses on evaluating the performance of two marketing campaigns across multiple digital channels. The goal was not only to compare Campaign A and Campaign B, but also to understand which campaign-channel combinations generated stronger customer engagement, conversions, and sales.

Using Power BI and DAX, I transformed customer interaction data into an interactive dashboard designed to support a practical business question:

- Which campaign and marketing channel should the client prioritize to improve marketing performance?

### 👩🏻‍💻Business Problem
A client needed to compare the performance of two marketing campaigns distributed across Email, Instagram, and Web Banner channels. Simply comparing total interactions was not enough. A campaign with more interactions could generate more sales while still being less efficient.

The analysis therefore focuses on performance metrics such as:

- **Total Customer Interactions:** measures the total number of customer interactions associated with each campaign and marketing channel. This metric provides context on campaign reach and helps determine whether higher sales are driven by stronger performance or simply by a larger volume of customer interactions.
  
- **Total Conversions:** represents the number of customer interactions that resulted in a successful conversion. This metric helps identify which campaigns and channels are generating actual customer outcomes rather than engagement alone.

- **Conversion Rate:** Measures the percentage of customer interactions that resulted in a conversion. It is calculated by dividing total conversions by total interactions. This metric is particularly important because it allows campaigns and channels with different interaction volumes to be compared based on efficiency.

- **Total Sales:** represents the total revenue generated from converted customer interactions. This metric helps quantify the financial contribution of each campaign, channel, and customer segment.

- **Revenue per Interaction:** measures the average amount of sales revenue generated for every customer interaction. This provides a more normalized view of performance and helps determine whether a campaign-channel combination is creating meaningful revenue relative to the traffic it receives.

- **Average Order Value (AOV):** represents the average revenue generated per successful conversion. This metric helps determine whether certain campaigns or channels attract customers who tend to generate higher-value purchases.

- **Customer Type:** segments customer interactions between new and existing customers. Because the client's primary objective is to grow new-customer sales, this dimension is essential for isolating acquisition performance rather than relying only on overall campaign results.

- **Time on Site:** measures the amount of time customers spend interacting with the campaign experience. Analyzing average time on site alongside conversion and sales metrics can help assess whether higher engagement is associated with stronger commercial outcomes.

- **Campaign and Channel Performance:** evaluates the combined performance of Campaign A and Campaign B across Email, Instagram, and Web Banner. Rather than analyzing campaigns and channels independently, this comparison helps identify the specific campaign-channel combination that delivers the strongest results for new customers.

The dataset contains 500 customer interactions with information related to:

- Campaign type
- Marketing channel
- Customer type
- Conversion status
- Sales
- Time on site

The analysis compares two campaigns:

- Campaign A
- Campaign B

across three marketing channels:

- Email
- Instagram
- Web Banner

### Insights 
- Revenue per Interaction: The analysis generated an average of $29.32 in revenue per customer interaction. This metric helps evaluate how effectively customer interactions were translated into sales value.
- Campaign Performance: Overall, Campaign B outperformed Campaign A, generating stronger sales results across the analyzed customer interactions.
- Campaign + Channel Performance: The combination of Campaign B + Email delivered the strongest performance among the campaign-channel combinations analyzed. This suggests that the effectiveness of Campaign B was particularly strong when delivered through Email.

### Recommendations
- NewCo should prioritize Campaign B + Email as the leading candidate for increasing new-customer sales. Rather than immediately reallocating the entire marketing budget, the company should validate this strategy through additional A/B testing and scale investment if the performance advantage remains consistent.
- Future analysis should incorporate marketing spend, customer acquisition cost (CAC), cost per acquisition (CPA), and return on ad spend (ROAS).
  
### Tools & Technologies
- Power BI: Dashboard development and data visualization. 
- DAX: KPI and performance metric calculations.
- Power Query: data preparation and transformation. 
- Excel: source dataset.
- Data Visualization: interactive business reporting.
- Marketing Analytics: campaign and channel performance analysis.


