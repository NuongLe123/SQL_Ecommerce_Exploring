# SQL_Ecommerce_Exploring

## Part 1. Introduction 
- The eCommerce dataset is stored in a public Google BigQuery dataset. This dataset contains information about user sessions on a website collected from Google Analytics in 2017. Here is the link to table description:
  https://support.google.com/analytics/answer/3437719?hl=en 
- Based on the eCommerce dataset, I write SQL queries to analyze website activity in 2017, such as calculating bounce rate, identifying days with the highest revenue, analyzing user behavior on pages, and various other types of analysis. This project aims to have an outlook on the business situation, marketing activity efficiency analyzing the products.
## Part 2. The goal of creating this project
- Overview of website activity
- Bounce rate analysis
- Revenue analysis
- Transactions analysis
- Products analysis
## Part 3. Business questions
For more details about the results of the queries, please follow the link: https://console.cloud.google.com/bigquery?sq=277003598955:76d34ad508dc46188d48b81e4f65116e

### 1. Calculate total visits, pageview, transaction, and revenue for Jan, Feb, and March 2017
<img width="774" alt="Screenshot_1" src="https://github.com/NuongLe123/RFM_analysis/assets/168357450/90a34456-f0e8-406c-b824-61bee87b898a">

- Result:
<img width="577" alt="Screenshot_1" src="https://github.com/NuongLe123/RFM_analysis/assets/168357450/f1918b6a-d185-4d88-a863-4ad7e4ee85dd">

### 2. Bounce rate per traffic source in July 2017

<img width="771" alt="Screenshot_2" src="https://github.com/NuongLe123/RFM_analysis/assets/168357450/a9141253-3e90-4ced-81fa-6788a941edaf">

- Result:
<img width="576" alt="Screenshot_2" src="https://github.com/NuongLe123/RFM_analysis/assets/168357450/342cd9ad-cff8-4b53-bf4f-c80bcd09c6a9">

### 3. Revenue by traffic source by week, by month in June 2017

<img width="774" alt="Screenshot_3" src="https://github.com/NuongLe123/RFM_analysis/assets/168357450/ebc94734-ee52-4328-a284-7481871f395b">

- Result:
<img width="714" alt="Screenshot_3" src="https://github.com/NuongLe123/RFM_analysis/assets/168357450/580fe201-7368-41d1-b8b7-6c24067f9e2d">

### 4. Average number of pageviews by purchaser type (purchasers vs non-purchasers) in June, July 2017

<img width="764" alt="Screenshot_4a" src="https://github.com/NuongLe123/RFM_analysis/assets/168357450/bc597b7d-d008-4a74-a13e-4fef213edf96">
<img width="768" alt="Screenshot_4b" src="https://github.com/NuongLe123/RFM_analysis/assets/168357450/09d2e8b0-b9bf-4ed0-97af-a13c06b434d4">

- Result:
<img width="470" alt="Screenshot_4" src="https://github.com/NuongLe123/RFM_analysis/assets/168357450/0fa12105-fabf-473f-b3fe-53f2c3edd1ba">

### 5. Average number of transactions per user that made a purchase in July 2017

<img width="774" alt="Screenshot_5" src="https://github.com/NuongLe123/RFM_analysis/assets/168357450/d0fe349e-62ba-42e9-8aa8-7342b6bb9a47">

- Result:
<img width="353" alt="Screenshot_5" src="https://github.com/NuongLe123/RFM_analysis/assets/168357450/e411023e-8c89-4587-a48c-b3ebc36db450">

### 6. Average amount of money spent per session. Only include purchaser data in July 2017

<img width="773" alt="Screenshot_6" src="https://github.com/NuongLe123/RFM_analysis/assets/168357450/74475a09-c232-4137-8721-7ae93565914c">

- Result:
<img width="351" alt="Screenshot_6" src="https://github.com/NuongLe123/RFM_analysis/assets/168357450/eeaeec94-0756-42a3-9480-18b9d39ee41d">

### 7. Other products purchased by customers who purchased product "YouTube Men's Vintage Henley" in July 2017.

<img width="775" alt="Screenshot_7" src="https://github.com/NuongLe123/RFM_analysis/assets/168357450/1408d04e-c0fc-4a8f-a20e-40ef58f4421b">

- Result:
<img width="352" alt="Screenshot_7" src="https://github.com/NuongLe123/RFM_analysis/assets/168357450/a93efc2c-a171-4934-bb28-ddfe033b78ee">

### 8. Calculate cohort map from product view to addtocart to purchase in Jan, Feb and March 2017.
<img width="774" alt="Screenshot_8a" src="https://github.com/NuongLe123/RFM_analysis/assets/168357450/0ca6dd1d-d05f-4fd0-bca8-e363af36dc25">
<img width="773" alt="Screenshot_8b" src="https://github.com/NuongLe123/RFM_analysis/assets/168357450/6518d176-4178-4806-92a2-76fab5d0f129">

- Result:
<img width="806" alt="Screenshot_8" src="https://github.com/NuongLe123/RFM_analysis/assets/168357450/874916ff-14db-4c6d-918d-d307c19f15d3">
  
## Part 4. Conclusion
- In conclusion, my exploration of the eCommerce dataset using SQL on Google BigQuery based on the Google Analytics dataset has revealed interesting insights of the customer behavior through the bounce rate, transaction, revenue, visit, and purchase.
- Hence, the company will decide which effective marketing channels enhance traffic and sales by considering referral sources, improving marketing ROI.
- To have insights and key trends, the next step will be visualization the data with some software like Power BI and Tableau.
