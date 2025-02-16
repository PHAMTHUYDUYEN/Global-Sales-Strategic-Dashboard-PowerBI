# [PowerBI] Global Sales Strategic Dashboard 
## **I.INTRODUCTION**
In this project, a **_strategic dashboard_** was developed using _**Design Thinking**_ approach and _**Power BI**_ tools (**_DAX_**, **_Power Query_**, and **_Visualization_** tools) to analyze **_global sales performance_** over 4 years. The dashboard aimed to assist senior managers in **_understanding business performance by region, product, and sales personnel,_** which led to **_decisions_** in **_Market expansion_**, **_Market optimization_**, and **_Product selection_**.

### **1. BUSINESS QUESTIONS**
Superstore is a global retail enterprise with operations spanning multiple regions. Senior management of Superstore requires a ***detailed understanding*** of the company’s ***business performance*** to inform ***strategic decisions*** regarding:
  - Market Expansion
  - Selection of Key Products for Growth

### **2. DATASET**
The dataset (as attachment) contains global sales information of Superstore, including 3 tables:
- Orders: a table storing transaction information
- People: a table containing information about sales representatives in each region
- Returns: a table recording transactions that were returned

## **II.DESIGN THINKING APPROACH**
### Stage 1: Empathize

<img width="950" alt="Product" src="https://github.com/user-attachments/assets/83e091af-e163-4cc6-b67b-fde010b561cd">

<img width="600" alt="Product" src="https://github.com/user-attachments/assets/acf5fe9f-dad5-4a27-871e-c07bbe3487dc">

### Stage 2: Define Point of View

<img width="450" alt="Product" src="https://github.com/user-attachments/assets/1cc3cc58-bdf1-4393-aef2-c2021e0ee12b"> \

<img width="450" alt="Product" src="https://github.com/user-attachments/assets/9242a9ce-595a-4138-b136-2c26690849e5"> \

<img width="400" alt="Product" src="https://github.com/user-attachments/assets/926eb43b-b171-4a04-acd3-a9763b009d7b">

### Stage 3: Ideate
Brainstorming

<img width="580" alt="Product" src="https://github.com/user-attachments/assets/50f3b975-97df-4b0d-8be5-115262027d46">


Structure idea

<img width="950" alt="Product" src="https://github.com/user-attachments/assets/32ada3ac-18d2-443d-be63-59f3553ef5c2">

### Stage 4: Prototype & Review
This is implementation and review stage. Prototype and Review dashboard multiple times to achieve the final dashboard.

## **III. DASHBOARD**
### **Data Modeling**
<img width="950" alt="DataModeling" src="https://github.com/user-attachments/assets/9413c9a9-945c-4ab6-ad49-932c0e682b86">

### **View 1: Market Analysis**
<img width="952" alt="Market" src="https://github.com/user-attachments/assets/90292d44-c85a-434d-b1cc-f3f4404f414e">

➡️ Insights:
- The company has its **_presence in all major markets_** around the world.
  - **_LATAM_**: Contributes **_highest revenue and profit_**, average rate of goods returned.
  - **_APAC_**: **_Highest YoY growth rate & customers count_**, ranks **_second in revenue_**, but exhibits **_low profit margins_**.
  - **_US Market_**: Ranks **_second in profit_**, this market has **_surprisingly high profit margin_**, an average number of customers, but **_low revenue_**.
  - **_Africa_** and **_EMEA_**: Has **_high customer numbers_** but **_negative profit_**.
  - **_Canada_**: Having **_strong YoY growth rate_** but **_few customers, low revenue_**

### **View 2: Product Analysis**
<img width="950" alt="Product" src="https://github.com/user-attachments/assets/4c8edaa8-0132-456e-b769-1225b51686ae">
<img width="950" alt="Product-Market" src="https://github.com/user-attachments/assets/0256876b-f3a2-4de8-ac04-98691dc09b53">

➡️ Insights:
-	**_Copiers_** are the company’s **_best-selling product overall_**, except for **_US market_**, where **_phones_** and **_chairs_** out-perform copiers.
-	**_Tables_** has poor performance with **_negative profit margins_** over the past four years, resulting in losses.
-	The **_return rate for binders_** has reached **_25%_**, which is **_highest among all_**.

### **View 3: Sales Agent Analysis**
<img width="950" alt="Salesman" src="https://github.com/user-attachments/assets/a638370e-018d-45e6-84e4-2e130cb034ff">

➡️ Insights:
-	**_Sales Agent of APAC-South East Asia market_**: performance is not very well with **_negative profit_** and a **_profit margin_** of only **_4%_**, although the he is **_selling key products_** such as copiers, phones, and bookcases in his market-in-charge.

## **IV. INSIGHTS & RECOMMENDATIONS**
### 1. Market Expansion
- ***Market Overview***:
  - The company has established presence in all major global markets. Rather than entering a completely new market, it is recommended to **_expand within the existing market_**. **_Canada_** market is **_recommended_**.
  - Despite Canada's strong Year-over-Year (YoY) growth rate and profit margin, its customer base remains limited, resulting in lower revenue. <br>--> It is proposed to develop a **_strategy to reach a broader customer segment_** in **_Canada_**.

- ***Sales Agent***:
  - **_Nicole Hansen_** is currently **_responsible for the Canadian market_**. The revenue, profit margin, and YoY growth rate indicators are **_performing well_**. <br>--> It is advisable to **_continue_** his/her oversight of this market.

- ***Product Strategy***:
  - Copiers are the company’s best-selling product overall. <br>--> It is suggested that **_copiers_** be positioned as a **_strategic product for the company_**.

### 2. Current Market Optimization
- ***LATAM Market***: **_Maintain the current strategy_** for this market as this market has been the best performer overall.

- ***APAC Market***:
  - This market is growing rapidly, has the highest number of customers, and ranks second in revenue, though it exhibits low profit margins. <br>--> It is recommended to **_investigate the reasons_** for the **_low profit margins_** and to develop **_strategies_** to **_enhance profitability from existing customer base_** by either increasing sales or improving profit margins.

- ***US Market***:
  - Ranked second in profit, this market has an unexpectedly high profit margin, an average number of customers, but low revenue. <br>--> It is proposed to develop **_strategies_** to drive **_more customer purchases_**, potentially considering a lower profit margin to stimulate higher sales volumes. **_Strategic products_** for this market should include **_phones_** and **_chairs_**.

- ***Ineffective Markets***:
  - **_Africa and EMEA are underperforming_**, with high customer numbers but negative total profits. <br>--> It is recommended to **_investigate the causes_** behind these issues to develop appropriate **_strategies_** for **_either improvement or withdrawal_** from these markets.

- ***Product Performance***: 
  - **_Tables_** have shown **_poor performance_** with negative profit margins over the past four years, resulting in losses with each sale <br>--> **_Discontinue_** this product or **_adjust its pricing_**.
  - The return rate for binders has reached 25% <br>--> **_Investigate the causes_** behind this high return rate and **_implement corrective measures_**.

- ***APAC-South East Asia Sales Agent***: It is proposed to issue a **_warning to the sales agent_** in this region due to negative profit and a profit margin of only 4%, despite the market's strong performance in key products like copiers, phones, and bookcases. The sales agent should reassess and **_adjust their sales plan_** accordingly.
