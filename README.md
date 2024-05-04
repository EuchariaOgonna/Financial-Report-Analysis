# E-commerce- SalesReport-Analysis
## Financial Sales Report of Company on Sales
## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Data Cleaning and Analysis](#data-cleaning-and-analysis)
-  [Summary](#summary)
-  [Recommendations](#recommendations)
### Project Overview
The sales data contains a complete details of sales activities in a company during a specific period, such as a daily, weekly, monthly, quarterly, and yearly sales. The report typically includes data on sales revenue, sales volume, sales by product, sales by region or market segment and sales trends over time. Sales data provides actionable insights into product performance in a company. By tracking and analyzing sales data, organizations can identify trends and patterns in customer behavior, product demand, and market conditions, which can inform business strategies and helps to improve revenue growth and strategic decision-making.

### Data Sources
This is an anonymous primary sales dataset gotten from Kaggle.com, the dataset was collated on a spreadsheet (Microsoft Excel).

### Tools Used
- Excel (Data Cleaning)
- Microsoft PowerBI (Creating a report).
![Project Overview](https://github.com/EuchariaOgonna/Financial-Report-Analysis/assets/105076757/c4de565b-953e-4368-ac5f-603b7b50c409)

### Data Cleaning and Analysis
DATA COLLECTION, CLEANING AND CREATION OF CALENDER.

- I uploaded the dataset to Microsoft power BI, and transformed via power query editor. I used the editor to check the dataset integrity.
- I checked the data, remove some duplicates and irrelevant column then closed and apply.
- From the Fact table, I created a calendar table. I clicked on the modeling tab, then new table and entered the DAX measure “CALENDARAUTO” to generate the date from the Fact table. I created four columns from the order date which include year, month, quarter and month number using different DAX measures formular.
- After creating the calendar table, I created a connection between the Fact table and the calendar table using Date.

### Summary
The company generated sales revenue of $118,726,350.20 and profit revenue of #16,893,702.26, it means that the company’s total sales revenue from selling its products or services was 118726350.20. However, after deducting all the expenses incurred in running the business, such as operating costs, taxes, salaries, and other expenses, the company was left with $16,893,702.26 in profit revenue. Comparing the two, we can see that the profit revenue is a smaller figure than the sales revenue. This is because the profit revenue represents the amount of money that the company has left over after deducting all expenses from its sales revenue. While a high sales revenue is important, it is not necessarily an indicator of success. What really matters is the profit revenue, which shows how efficiently the company is being run and how much money it is actually making after all expenses are taken into account. A company with a lower sales revenue but higher profit revenue may be more successful than a company with higher sales revenue but lower profit revenue.
### Recommendations
There are a variety of strategies that a sales company can use to generate more profit. Here are some recommendations:

- Focus on Customer Retention: It is often more cost-effective to retain existing customers than to acquire new ones. Invest in building strong relationships with your current customers by providing excellent customer service, personalized communication, and incentives to encourage repeat business.

- Expand Product/Service Offerings: Consider expanding your product or service offerings to increase revenue streams. This can include developing new products/services, bundling existing products/services, or offering complementary products/services.

- Improve Sales Team Performance: Provide ongoing training and support to your sales team to help them improve their skills and knowledge. This can include sales training, product/service training, and coaching.

- Identify New Markets and do promotion: Explore new markets or customer segments that may be interested in your products/services. This can include expanding into new geographic regions, targeting new industry sectors, or reaching out to a new demographic.
- Analyze Sales Data: Use data analytics to analyze sales trends and identify opportunities for growth. This can include identifying which products/services are most popular, which sales channels are most effective, and which customer segments are most profitable.

By implementing these strategies, the company can generate more profit and achieve long-term success.

### References
- Google.com (https://google.com)
