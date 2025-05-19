# A Comprehensive Analysis to Maximaze Sales Performance and Minimize Curn In The Retail Business

## Overview
This project aims to optimize retail business strategy by segmenting customers using RFM analysis (Recency, Frequency, Monetary) combined with demographic profiling. The project is based on the "Supermarket Customers" dataset, which contains data on 2,240 customers, including purchase history, demographics, and spending patterns. The project provides insights into customer behavior, segmentation, and strategic marketing recommendations to improve revenue and customer loyalty.

## Dataset
The `Supermarket_Customer_Cleaned.csv` dataset includes 2,240 customer records with 29 columns, grouped into the following categories:
- **People**: Customer demographics (age, education, marital status, income, family composition, etc.)
- **Products**: Spending on product categories (wine, fruits, meat, fish, sweets, gold)
- **Promotion**: Customer responses to marketing campaigns
- **Place**: Purchase channels (web, catalog, store) and online activity
  
After data cleaning, the final dataset used for analysis contains 2,202 customers.

## Objectives
- Segment customers into High-Value, Medium-Value, and Low-Value groups using RFM scores
- Identify retention strategies for customers at high risk of churn (At-Risk segment)
- Analyze the influence of demographics (age, education, family structure) on spending behavior.
- Provide marketing strategy recommendations to increase revenue through upselling, cross-selling, and demographic targeting.
- Optimize product and promotion strategies based on customer preferences.

## Key Findings
- **RFM Segmentation**:
  - High-Value: 43% (942 customers), average spending: $1,153.46
  - Medium-Value: 36% (801 customers), average expenditures: $278.52
  - Low-Value: 21% (459 customers); "At-Risk" segment accounts for 22%, with high churn risk
- **Demographic Insights**:
  - Customers with higher education (PhD, Master's) spend more ($610–$678)
  - Customers without children/teenagers spend more (avg. $1,419)
  - The 36–45 age group is the dominant and most profitable segment
- **Segment Distribution**:
  - High-value and Medium-Value customers account for 79% of the total
  - The At-Risk segment (22%) requires targeted retention strategies

## Recommendations
- **Retensi "At Risk"**: Luncurkan kampanye re-engagement (diskon, email personalisasi).
- **High-Value**: Tawarkan produk premium (Wine, Meat) dan program loyalitas.
- **Medium-Value**: Dorong pembelian dengan bundling produk (Fruits-Sweet, Meat-Fish).
- **Strategi Demografis**:
  - Targetkan pelanggan dengan pendidikan tinggi untuk produk premium.
  - Promosikan produk mewah (Gold) untuk pelanggan tanpa anak/remaja.
  - Fokuskan kampanye pada usia 36–45 tahun.
- **Optimalisasi Produk**: Prioritaskan Wine (50.3%) dan Meat (27.5%), dorong penjualan Gold dan Fish melalui bundling.
- **At-Risk Retention**: Launch re-engagement campaigns (e.g., personalized emails, exclusive discounts)
- **High-Value Customers**: Offer premium products (Wine, Meat) and exclusive loyalty programs
- **Medium-Value Customers**: Encourage spending through product bundling (e.g., Fruits–Sweet, Meat–Fish)
- **Demographic-Based Strategy**:
  - Target highly educated customers for premium offerings
  - Promote luxury products (e.g., Gold) to customers without children or teenagers
  - Focus marketing campaigns on the 26–65 age group, especially 36–45
  - Use online promotions tailored to customer demographics to attract new customers
- **Product Optimization**:
  - Prioritize best-sellers like Wine (50.3%) and Meat (27.5%)
  - Boost sales of Gold and Fish through bundling strategies

## Project Structure
```
├── Supermarket_Customers.ipynb         #Main analysis & visualization notebook 
├── Supermarket_Customer_Cleaned.csv    #Cleaned dataset
└── README.md  # Dokumentasi proyek     #Project documentation
```

## Dependencies
This project uses Python 3.11 and the following libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`

To install dependencies, run:
```bash
pip install -r requirements.txt
```

Or install manually:
```bash
pip install pandas numpy matplotlib seaborn scipy
```

## How to Run
1. Clone the repository:
   ```bash
](https://github.com/machie86/CUSTOMER-SEGMENTATION-BY-RFM-ANALYSIS-IN-THE-RETAIL-STORE/edit/main/README.md)   ```

2. Navigate to the project directory:
   ```bash
   cd <CUSTOMER-SEGMENTATION-BY-RFM-ANALYSIS-IN-THE-RETAIL-STORE>
   ```
3. Ensure all dependencies are installed (see Dependencies section)
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Open and run Supermarket_Customers.ipynb to view the full analysis and results.

## Next Steps
- Launch re-engagement campaigns for the At-Risk segment within the next 1–2 months
- Pilot bundling strategies for the Medium-Value segment
- Conduct further analysis on income vs. product preferences for deeper segmentation

## Acknowledgments
- The dataset is adjusted from retail customer data for analytical purposes
- Notable thanks to the open-source community for providing powerful tools and libraries used in this project
