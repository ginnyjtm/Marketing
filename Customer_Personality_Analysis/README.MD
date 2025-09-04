# Customer Personality Analysis


## Project Overview 
Customer Personality Analysis is a detailed analysis of a company's ideal customers. To helps a business to understand its customers for easier to modify product accroding to the specific needs, behaviors and concerns of different types of customers.

---
## Objective

Group customers into 5 behavior and value-based clusters using spend, recency, and channel preference.

---
## Dataset

- **Source** Kaggle Dataset - Customer Personality Analysis
- **Size** 2,240 records
- **Columns** 
> People
* `ID`: Customer's unique identifier
* 'Year_Birth': Customer's birth year
* 'Education': Customer's education level
* 'Marital_Status': Customer's marital status
* 'Income': Customer's yearly household income
* 'Kidhome': Number of children in customer's household
* 'Teenhome': Number of teenagers in customer's household
* 'Dt_Customer': Date of customer's enrollment with the company
* 'Recency': Number of days since customer's last purchase
* 'Complain': 1 if the customer complained in the last 2 years, 0 otherwise

> Products
* 'MntWines': Amount spent on wine in last 2 years
* 'MntFruits': Amount spent on fruits in last 2 years
* 'MntMeatProducts': Amount spent on meat in last 2 years
* 'MntFishProducts': Amount spent on fish in last 2 years
* 'MntSweetProducts': Amount spent on sweets in last 2 years
* 'MntGoldProds': Amount spent on gold in last 2 years

> Promotion
* 'NumDealsPurchases': Number of purchases made with a discount
* 'AcceptedCmp1': 1 if customer accepted the offer in the 1st campaign, 0 otherwise
* 'AcceptedCmp2': 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
* 'AcceptedCmp3': 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
* 'AcceptedCmp4': 1 if customer accepted the offer in the 4th campaign, 0 otherwise
* 'AcceptedCmp5': 1 if customer accepted the offer in the 5th campaign, 0 otherwise
* 'Response': 1 if customer accepted the offer in the last campaign, 0 otherwise

> Place
* 'NumWebPurchases': Number of purchases made through the company’s website
* 'NumCatalogPurchases': Number of purchases made using a catalogue
* 'NumStorePurchases': Number of purchases made directly in stores
* 'NumWebVisitsMonth': Number of visits to company’s website in the last month

---
## Key Features

- Data Cleaning: drop nulls (e.g., Income), reset index.  
- Data Engineering: 
    - Derived fields: 'Age', 'TotalSpend', 'Children', 'Tenure', 'PromoAcceptanceRate'.
    - Normalized skewed features (Income, TotalSpend) using log transform.
- Customer Segmentation: 
    - Applied K-Means clustering (5 segments) based on behavioral and value features.
    - Standardized features to improve clustering accuracy.
- Cluster Profiling: 
    - Computed mean & median of key features per segment.
    - Labeled segments with descriptive archetypes (e.g., Premium Loyalists, Dormant Shoppers).
    - Count of customers per segment.
- Visualization:
    - Bar charts showing segment sizes.
    - Scatterplots and heatmaps for TotalSpend, Recency, and purchase channels.
- Insights:
    - Identified high-value, deal-responsive, and low-value customer groups.
    - Highlighted skewed clusters where mean differs from median for better targeting.

---
## Technologies used

- Python3
- Pandas, Numpy 
- Matplotlib
- sklearn
- seaborn

---
## Key Insights (Summary)

Clustering customers based on behavior and value (spend, recency, channels) revealed five distinct segments:

- **Segment 0: Loyal Multi-Channel Buyers**  
  - Largest group (541 customers)  
  - Mostly uniform; a few very high spenders slightly raise average spend  
  - Active across both online and in-store channels

- **Segment 1: Premium In-Store Shoppers**  
  - High-income, consistently high spenders  
  - Prefer in-store purchases; mean vs median close → uniform behavior  
  - 516 customers

- **Segment 2: Occasional Shoppers**  
  - Low-value buyers; a few outliers slightly raise the mean  
  - Younger, lower-income, low engagement across channels  
  - 530 customers

- **Segment 3: Dormant Family Shoppers**  
  - Mostly low-value, family-oriented customers  
  - Mean inflated by a few higher spenders; low engagement overall  
  - 465 customers

- **Segment 4: Premium Loyalists**  
  - Small (164 customers), high-income, high-value group  
  - Mean ≈ median → uniform premium behavior  
  - Active and recently engaged

---
## 👩‍💻 About Me

Hi, I’m Ginny — a data analyst with a full-stack development background, passionate about turning raw data into clear, evidence-based decisions.   

## 📬 Let’s Connect

- [LinkedIn](https://www.linkedin.com/in/ginny-jutamat/)  
- [Portfolio Website](https://ginnyjutamat.com)  
- [Email](mailto:work.ginnysangka@gmail.com)


