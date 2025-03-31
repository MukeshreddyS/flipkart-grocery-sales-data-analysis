# Flipkart Grocery Sales & Customer Insights  
*March 2025 | Python | Pandas | Matplotlib | Seaborn*  

Analyzing 46.7 million Flipkart grocery sales records to optimize product strategies, city-wise performance, and customer retention for revenue growth.  

## Objective  
To uncover actionable insights from Flipkart’s sales and product data (April-July 2022) to boost revenue through targeted strategies and improved customer lifetime value (CLTV).  

## Approach  
- **Datasets**:  
  - `dim_product.csv`: 32,226 products (categories, brands).  
  - `monthly_sales/*.csv`: 46.7M sales records (Delhi, Mumbai, Bengaluru, HR-NCR) with pricing and customer details.  
- **Tools**: Python, Pandas, Matplotlib, Seaborn, NumPy.  
- **Steps**: Cleaned data, merged datasets, calculated sales and customer KPIs, visualized trends.  

## Key Insights  
### Sales Performance  
- **Total Revenue**: ~₹21.2B (calculated as `unit_selling_price * procured_quantity - total_discount_amount`).  
- **Top Categories**: Specials (e.g., Bill Breaker) lead—full list in notebook.  
- **City Breakdown**:  
  - Delhi: 40% (₹8.5B)  
  - Mumbai: 30% (₹6.4B)  
  - Bengaluru: 20% (₹4.2B)  
  - HR-NCR: 10% (₹2.1B)  

### Customer KPIs  
- **CLTV**: ₹2.15L ($2,578) over 3 years (Avg. Purchase: ₹37,615; Frequency: 1.9/month).  
- **Retention Rate**: 100% (April) → 70.37% (July).  
- **Churn Rate**: 63.31% overall; Mumbai highest (54.23%), HR-NCR lowest (41.26%).  
- **Purchase Frequency**: 5.25 orders/customer.  

### Trends  
- Peak sales in April; discounts underutilized (`total_discount_amount` often 0).  

## Visuals  
1. **Sales by City**  
   ![Sales by City](https://via.placeholder.com/600x400.png?text=Sales+by+City)  
   *Delhi dominates at 40%.*  
2. **Top Categories**  
   ![Top Categories](https://via.placeholder.com/600x400.png?text=Top+Categories)  
   *Specials lead revenue.*  
3. **Retention Rate**  
   ![Retention Rate](https://via.placeholder.com/600x400.png?text=Retention+Rate)  
   *30% drop over 4 months.*  

## Conclusions  
- **Products**: Specials drive sales—prioritize promotions.  
- **Cities**: Delhi/Mumbai fuel revenue; Mumbai’s churn needs attention.  
- **Customers**: High CLTV potential if churn (63%) is tackled.  

## Recommendations  
- **Retention**: Loyalty programs for Mumbai & July slumps.  
- **City Strategies**: Discounts in Mumbai, value in HR-NCR, scale in Delhi.  
- **Discounts**: Test 20-60% offers to lift sales.  

## Explore the Analysis  
- **Notebook**: [flipkart_sales_analysis.ipynb](flipkart_sales_analysis.ipynb)  
- **Code & Outputs**: Fully rendered with visuals and KPIs.  

*Inspired by eCommerce analyses like Abhishek Mishra’s Flipkart project. Feedback welcome!*
