# Customer Retention and Revenue Analysis using Cohort

### Objective
The goal of this project is to evaluate customer behavior and revenue stability using cohort analysis. The study focuses on understanding long-term loyalty, assessing the contribution of high-value (wholesale) clients, and identifying seasonal patterns that influence the customer lifecycle.

### Data Source
The dataset was sourced from **[Kaggle](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)**, containing all transactions occurring between 01/12/2009 and 09/12/2011 for a registered non-store online retail business. The company primarily sells unique all-occasion gifts.

### Project Content
1. **Importing Libraries and Data**: Environment setup and dataset loading.
2. **EDA (Exploratory Analysis)**:
   - **Data Cleaning**: Handling missing values, standardizing datetime formats, and filtering records.
   - **Monthly User Activity**: Analyzing trends in unique customer counts and acquisition rates.
   - **Revenue Trends**: Examining revenue fluctuations and their correlation with user volume.
3. **Cohort Analysis**:
   - **Monthly Customer Count**: Tracking the volume of active users within each cohort over a 24-month period.
   - **Retention Rate Heatmap**: Visualizing the percentage of returning customers to demonstrate base stability.
   - **Revenue Retention Rate**: Analyzing financial loyalty, showing spending growth among retained customers.

### Key Findings
- **Established Loyalty Core**: The initial cohort (December 2009) demonstrates an exceptional retention rate (30-50%) throughout the entire observation period.
- **Wholesale Impact**: Revenue retention often exceeds customer retention, reaching peaks of 87% in the 12th month of a cohort's lifecycle, indicating increased order volumes from loyal clients.
- **Cyclicality & Seasonality**: Dips in retention are temporary. Customers show cyclical behavior, returning specifically for peak seasonal demand (Q4).

### Recommendations
- **Stimulate Off-Season Demand**: Develop soft marketing activities or special offers during low-demand periods to maintain a steady flow of orders.
- **Peak Season Preparation**: Utilize the off-season as a preparation stage by announcing new assortments to wholesale clients early, allowing them to form orders before the main peak begins.
- **Core Group Engagement**: Maintain active interaction with the most stable "legacy" cohorts, which provide a baseline revenue level regardless of seasonal fluctuations.
