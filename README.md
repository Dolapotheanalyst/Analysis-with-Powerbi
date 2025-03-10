# Analysis-with-Powerbi
this is a Customer transaction analysis with powerbi
# Customer Transactions Analysis of Super Store Dataset (An E-commerce Company)

## Data Cleaning and Preparation

The first thing I did was *import the data into Power Query* for cleaning.

- I ensured all the data had the *correct data type* and was *properly cleaned*.
- I added a few *columns*, including:
  - The *name of the day* (e.g., Monday, Tuesday).
  - The *first three characters* of the day name.
  - The *number of the day of the week* (starting from *0 to 6*).
- After this, I *loaded the data into Power BI*.

---

## Report Creation and Visualizations

### First Report Page: Sales and Transactions Overview

- I added a *line shape* to divide my canvas into two at a *90° angle*.
- I created my *title using a text box*.
- I used the *text box to automatically generate summary numbers*.

#### Sales Trend Analysis
- I created a *line chart* to show *how sales trended over the months*.
- I used a *ribbon chart* to display *the changes in rank of our segments over time*.
- *Key findings:*
  - The *Customer Segment* has always been the *highest segment across time, except for **October, when the **Corporate Segment* took over.
  - The *Home Office Segment* has always been the *lowest segment by sales*.

#### Sales by Day of the Week
- I displayed the *average sales per day of the week* using a *column chart*.
- *Findings:*
  - The *average sales per week range from $216.30 to $259.68*.
  - *Tuesday and Friday* had *more sales than any other day*.

#### Transactions by Day of the Week
- I displayed the *number of transactions by day of the week*.
- *Findings:*
  - *Monday and Friday* had the *highest transactions*.
  - *Wednesday had the lowest transactions*.

#### Filters and Slicers
To improve interactivity, I added:
- A *Year slicer* to filter *all information in the first report page by year*.
- *Region and Product Category slicers* for the *first report page*.

---

### Second Report Page: Location-Based Insights

- I *synchronized the slicers* from the first page.
- I created a *bar chart* to display:
  - *Top 10 states by sales*.
  - *Bottom 10 states by sales* (using filter panels).

#### Transactions by Shipping Mode
- I used a *matrix table* to show the *number of transactions per state by Ship Mode*.
- This focused on the *Top 10 states*, analyzing how many transactions used:
  - *First Class*
  - *Same Day*
  - *Second Class*
  - *Standard Class*  
- I applied *conditional formatting* to highlight the *high and low transaction areas*.
- This helped me focus on *percentage distributions of transaction shipments in the Top 10 states*.

#### Geographical Insights
- Since this is a *location report page, I added a **map* for better visualization.
- I enabled *drill-through from the location report to a desired month*.

---

### Third Report Page: Advanced Analysis

#### Decomposition Tree
- I added a *decomposition tree, allowing users to **drill from any number to any dimension of the dataset*.
- I *fixed the year* so that users can *drill through from the year level*.

#### Key Influencers Visual
- I used *Key Influencers Visual* to analyze *factors contributing to increases or decreases in sales*.
- *Findings:*
  - The *biggest factor for sales increase* was when the *subcategory was "Tables", meaning **Tables contributed positively to sales*.
  - The *biggest factor for a decrease in sales* was *Office Supplies, which reduced sales by an **average of $287*.

#### Q&A Page
- I created a *Q&A page, allowing users to **click a button at the top* and ask *any question about the dataset*.

---

## Recommendations

Based on my findings, I suggest the following:

### 1. *Leverage High-Performing Product Categories*
   - Since *Tables* contribute significantly to *increased sales, focus on **marketing, promotions, and inventory* for this product.

### 2. *Improve Performance of Low-Selling Categories*
   - Since *Office Supplies* negatively impact sales, consider:
     - *Better marketing strategies*.
     - *Discounts and bundled offers*.
     - *Product diversification*.

### 3. *Optimize Sales Days for Maximum Profit*
   - Since *Tuesday and Friday* have *higher sales*, schedule:
     - *Flash sales, ads, and promotions* on these days.
     - *Targeted marketing campaigns*.

### 4. *Enhance Shipping Strategy*
   - Analyze the *most popular shipping modes* and optimize *delivery logistics* in high-performing states.

### 5. *Target High-Transaction Days for Customer Engagement*
   - *Monday and Friday* had the *highest number of transactions*.
   - Focus on:
     - *Customer engagement campaigns*.
     - *Loyalty programs and retention strategies*.

### 6. *Improve Corporate Segment Sales Year-Round*
   - Since the *Corporate Segment outperformed the Customer Segment in October*, implement:
     - *B2B marketing strategies*.
     - *Corporate discounts and offers*.

