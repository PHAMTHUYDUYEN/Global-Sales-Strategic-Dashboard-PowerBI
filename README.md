# [PowerBI] Global Sales Strategic Dashboard 
## **I.INTRODUCTION**
### **1. BUSINESS QUESTIONS**
Superstore is a global retail enterprise with operations spanning multiple regions. Senior management of Superstore requires a detailed understanding of the company’s business performance to inform ***strategic decisions*** regarding:
  - Market Expansion
  - Selection of Key Products for Growth

This dashboard, developed using the ***Design Thinking approach*** and ***Power BI tools***, aims to provide valuable insights into overall sales performance and offer actionable recommendations. Its objective is to support senior management in making informed, data-driven decisions to address their problems.

### **2. DATASET**
The dataset (as attachment) contains global sales information of Superstore, including 3 tables:
- Orders: a table storing transaction information
- People: a table containing information about sales representatives in each region
- Returns: a table recording transactions that were returned

## **II.DESIGN THINKING APPROACH**
### Stage 1: Empathize
|5W1H|---|
|---|---|
|Who will be viewing this Dashboard?|	Senior managers (CEO, Sales Manager, Marketing Manager, HR Manager, etc.)|
|If we had to choose only one key Stakeholder, who would it be?| CEO|
|What problem does this Dashboard solve?	| Market expansion strategy<br>Plan for improving the current market<br>Strategic product selection decisions<br>Sales personnel allocation plan|
|Describe the problem in one sentence |	Assist the CEO in understanding the business performance (sales, returns) by region, product, and sales personnel, to support decision-making regarding market expansion, strategic product selection, and personnel allocation.|
|When and where will Stakeholders view this Dashboard?| 1. When working independently, to grasp the business performance to carefully consider strategic decisions.<br>2. During strategy discussions with the team in meetings.|
|Why do stakeholders need this Dashboard?| 1. To quickly understand the business performance of products, markets, and sales personnel.<br>2. To have a basis for selecting strategic products and target markets for expansion.<br>3. To consider the sales personnel allocation plan.<br>4. To determine whether business performance needs improvement in any specific market.|
|How have stakeholders been achieving their goals so far?	| 1. Understand sales, returns, and growth rates across markets <br>--> Identify potential markets <br>--> Determine which markets need improvement <br>--> Plan to investigate causes and propose solutions)<br> 2. Understand sales, returns, and growth rates by product category --> Select strategic products<br>3. Track sales, performance growth, and regions managed by each sales representative --> Allocate personnel accordingly|

|Empathy Map|---|
|---|---|
|**Thinking and feeling**<br>_What does the stakeholder think and feel?_|	The company is performing well, and your focus is on driving further growth with the immediate goal of reaching this year's revenue target. It's great to have that clear objective in mind while exploring strategies to enhance business performance!|
|**Seeing**<br>_What does the stakeholder see?_|	The company is operating successfully on a global scale.<br>This year's revenue target has been set higher than the previous year's.|
|**Saying and doing**<br>_What does the stakeholder say and do?_	|"I believe that expanding into new markets can help the company achieve its revenue goals".<br>"To increase revenue, I should also assess the current markets to identify any areas that require improvement".|
|**Pains**<br>_What are the biggest problems and challenges?_|	1. What are the potential markets for expansion?<br>2. Is there a need to improve the current markets?<br>3. Which products should be prioritized for the new or existing markets?<br>4. Who will be responsible for the new market? Is there a need to adjust personnel allocation?|
|**Gains**<br>_What are the opportunities and benefits?_|	With the analyzed data, the CEO will gain an accurate understanding of the business performance, allowing for the validation of assumptions and informed decision-making.|

### Stage 2: Define Point of View
|Northstar Metric|---|
|---|---|
|What VALUE you want to measure?|Total value generated from customers through sales.|
|WHEN the value DELIVERY SUCCESS?|When an order is completed.|
|Northstar Metric Name|Revenue|
|WHY do you choose this metric?|Reflecting the business's sales performance, higher the revenue better the performance.|

Dimension Data Group
|**Group 1** - Location|**Group 2** - Product|**Group 3** - Salesman|**Group 4** - Time|
|:---:|:---:|:---:|:---:|
|_Market<br>Region<br>Country_|	_Product<br>Product Category_	|_Sales person_|_YoY_|

Define Point of View
|View	|Description	|	Why	|
|---|:---:|---|
|**View1**| Market Analysis|	Identify potential markets for expansion and weak markets that need improvement.	|			
|**View2**| Product Analysis|	Select strategic products for each market or for all markets.	|		
|**View3**| Sales Person Analysis|	Select personnel responsible for the new market and reallocate personnel for existing markets (if necessary).|

Growth Formula
|Northstar Metric:|Revenue|
|---|---|
|View 1 breakdown	| Revenue by Market, by Time|
|View 2 breakdown	| Revenue by Product, by Time, by Product & Market	|
|View 3 breakdown	| Revenue by Sales Person |


### Stage 3: Ideate
Brainstorming
|Idea Name|Layer 0 dimension| Layer 1 dimension|Layer 2 dimension|
|---|---|---|---|
|View 1: Market| 1. Total Revenue<br>2. Total Profit<br>3. Total Number of Customer|1. Revenue by market<br>2. Profit by market<br>3. Profit Margin by market<br>4. Customer number by market<br>5. Return Rate by market<br>6. YoY Growth Rate of Revenue by market|1. Revenue, profit by market, by category|
|View 2: Product|1. Total Revenue<br>2. Total Profit|1. Revenue by product category<br>2. Profit  by product category<br>3. Product Classification:<br>- High vol, High profit<br>- High vol, Low profit<br>- Low vol, High profit<br>- Low vol, Low profit<br>4. Profit margin by product category<br>5. Return rate by product category<br>6. YoY Growth Rate of Revenue by product category |1. Revenue, profit by category, by year|
|View 3: Sales Person	|1. Total Revenue<br>2. Total Profit|1. Revenue by person<br>2. Profit by person<br>3. Profit margin by person<br>4. YoY Growth Rate of Revenue by person<br>5. Market by person|1. Revenue, profit by person, by category|

Structure idea
|---|	Metric 1 | Metric 2	| Metric 3	| Metric 4 |
|---|---|---|---|---|
|Scorecard	|Revenue	|Number of customers	|Profit	|Profit Margin|

|Idea Name	| Highly important info|	Important info | Detailed info |
|---|---|---|---|
|View 1|1. Revenue by market<br>2. Profit by market<br>3. Profit Margin by market<br>4. Customer number by market<br>5. Return Rate by market<br>6. YoY Growth Rate of Revenue by market|1. Total Revenue<br>2. Total Profit<br>3. Total Number of Customer|1. Revenue, profit by market, by category<br>2. Market details"	|
|View 2|1. Revenue by product category<br>2. Profit  by product category<br>3. Product Classification:<br>- High vol, High profit<br>- High vol, Low profit<br>- Low vol, High profit<br>- Low vol, Low profit<br>4. Profit margin by product category<br>5. Return rate by product category<br>6. YoY Growth Rate of Revenue by product category|1. Total Revenue<br>2. Total Profit |1. Revenue, profit by category, by year|
|View 3	|1. Revenue by person<br>2. Profit by person<br>3. Profit margin by person<br>4. YoY Growth Rate of Revenue by person|1. Total Revenue<br>2. Total Profit|1. Market by person<br>2. Sales person details|	

### Stage 4: Prototype & Review
This is implementation and review stage. Prototype and Review dashboard multiple times to achieve the final dashboard.

## **III. DASHBOARD**
### **Data Modeling**
<img width="950" alt="DataModeling" src="https://github.com/user-attachments/assets/9413c9a9-945c-4ab6-ad49-932c0e682b86">

### **View 1: Market Analysis**
<img width="952" alt="Market" src="https://github.com/user-attachments/assets/90292d44-c85a-434d-b1cc-f3f4404f414e">

### **View 2: Product Analysis**
<img width="950" alt="Product" src="https://github.com/user-attachments/assets/4c8edaa8-0132-456e-b769-1225b51686ae">

### **View 3: Sales Agent Analysis**
<img width="950" alt="Salesman" src="https://github.com/user-attachments/assets/a638370e-018d-45e6-84e4-2e130cb034ff">

## **IV. INSIGHTS & RECOMMENDATIONS**
### 1. Market Expansion
- ***Market Overview***:
  - The company has established presence in all major global markets. Rather than entering a completely new market, it is recommended to expand within the existing market. Canada market is recommended.
  - Despite its strong Year-over-Year (YoY) growth rate and profit margin, Canada’s customer base remains limited, resulting in lower revenue. <br>--> It is proposed to develop a strategy to reach a broader customer segment in Canada.

- ***Sales Agent***:
  - Nicole Hansen is currently responsible for the Canadian market. The revenue, profit margin, and YoY growth rate indicators are performing well. <br>--> It is advisable to continue his/her oversight of this market.

- ***Product Strategy***:
  - Copiers are the company’s best-selling product overall. <br>--> It is suggested that copiers be positioned as a strategic product for the company.

### 2. Current Market Optimization
- ***LATAM Market***: Maintain the current strategy for this market as this market has been the best performer overall.

- ***APAC Market***:
  - This market is growing rapidly, has the highest number of customers, and ranks second in revenue, though it exhibits low profit margins. <br>--> It is recommended to investigate the reasons for the low profit margins and to develop strategies to enhance profitability from existing customer base by either increasing sales or improving profit margins.

- ***US Market***:
  - Ranked second in profit, this market has an unexpectedly high profit margin, an average number of customers, but low revenue. <br>--> It is proposed to develop strategies to drive more customer purchases, potentially considering a lower profit margin to stimulate higher sales volumes. Strategic products for this market should include phones and chairs.

- ***Ineffective Markets***:
  - Africa and EMEA are underperforming, with high customer numbers but negative total profits. <br>--> It is recommended to investigate the causes behind these issues to develop appropriate strategies for either improvement or withdrawal from these markets.

- ***Product Performance***: 
  - Tables have shown poor performance with negative profit margins over the past four years, resulting in losses with each sale <br>--> Discontinue this product or adjust its pricing.
  - The return rate for binders has reached 25% <br>--> Investigate the causes behind this high return rate and implement corrective measures.

- ***APAC-South East Asia Sales Agent***: It is proposed to issue a warning to the sales agent in this region due to negative profit and a profit margin of only 4%, despite the market's strong performance in key products like copiers, phones, and bookcases. The sales agent should reassess and adjust their sales plan accordingly.
