# BI_LW1_Basic_Sales_Data
Getting Started with Power BI – Loading and Exploring Data

Step 1: Open Power BI Desktop
1. Click Start
2. Open Microsoft Power BI Desktop
3. Wait for the startup screen

<img width="597" height="337" alt="image" src="https://github.com/user-attachments/assets/1a51cf35-64f4-4b19-acd1-4117e4815b78" />


Step 2: Load the Dataset
1. Click Home Tab
2. Click Get Data
3. Select Text/CSV

4. Browse and select:
Week1_Basic_Sales_Data.csv
5. Click Load

<img width="597" height="337" alt="image" src="https://github.com/user-attachments/assets/0d866dc0-2ea7-4ff5-976b-43b234718cf4" />
<img width="597" height="337" alt="image" src="https://github.com/user-attachments/assets/1d91a931-deb1-4e34-a92a-0f1a5902b9c7" />
<img width="597" height="337" alt="image" src="https://github.com/user-attachments/assets/336fd8b7-dd56-43a8-97c3-5a03eea07e11" />



Step 3: Verify Data in Data View

Question:

1. Are all columns visible?

 ANSWER: Yes
 
2. Is “Date” formatted as Date?

 ANSER: YES
 
3. Is “Sales” formatted as Decimal Number?

 ANSWER: NO, but i change it into Decimal number.
   
1. Click the column
2. Go to Column Tools
3. Change Data Type accordingly:
   
○ Date → Date

○ Sales → Decimal Number

○ Product/Category/Region → Text

<img width="597" height="337" alt="image" src="https://github.com/user-attachments/assets/3ba987c4-1089-4042-8235-25fdda874d8f" />



PART 2: Exploring the Interface

Report View

<img width="597" height="337" alt="image" src="https://github.com/user-attachments/assets/5bbac149-f27a-4441-871d-b9f43b3671fd" />

Data View

<img width="597" height="337" alt="image" src="https://github.com/user-attachments/assets/1bb10df0-1b2a-462e-b9bf-01fe2bcb3e6e" />

Model View

<img width="597" height="337" alt="image" src="https://github.com/user-attachments/assets/2557f53f-f2e0-4f02-8711-b305ce0ee709" />




PART 3: Creating Auto-Generated Visuals


Step 1: Quick Visualization
1. Drag Sales into canvas

<img width="597" height="337" alt="image" src="https://github.com/user-attachments/assets/ecb07380-4d64-4c46-9b51-cf7253467fb2" />

2. Power BI automatically creates a visual

Question:

   What type of chart was created?

   Clustered column chart
   
   What does it show?

   Clustered chart for Sum of Sales

 PART 3: Creating Auto-Generated Visuals

Step 2: Create a Sales by Region Chart

1. Click blank canvas
   
2. Select Clustered Column Chart

3. Drag:
   
○ Region → X-axis

○ Sales → Values

<img width="597" height="337" alt="image" src="https://github.com/user-attachments/assets/e0b41916-0013-416c-b64a-407b0635a6d3" />

Question:

● Which region has highest sales?

Answer: West

Step 3: Sales by Category

1. Insert a Pie Chart

2. Drag:
   
○ Category → Legend

○ Sales → Values

   <img width="597" height="337" alt="image" src="https://github.com/user-attachments/assets/5e70e08e-f417-4f9c-962f-522de7504e7f" />

Question:

● Which category dominates?

Answer: Electonics

● Is the distribution balanced?

Answer: No

Step 4: Sales Over Time

1. Insert Line Chart
   
2. Drag:
   
○ Date → X-axis

○ Sales → Values

<img width="1202" height="417" alt="image" src="https://github.com/user-attachments/assets/1c2de1fc-333a-4fcd-9630-e984022e3130" />


Question:

● Is there growth?

Answer: 

No, there is no growth shown in the chart. Instead, there is a significant decline in the sum of sales, which dropped from approximately 0.2M in 2024 to well below 0.1M in 2025.

● Any noticeable trend?

Answer: The most noticeable trend is a sharp year-over-year decline in the sum of sales, which dropped from approximately $0.2M$ in 2024 to nearly zero in 2025.

PART 4: Basic Data Insight Interpretation

Question:

● Which region contributes most revenue?

Answer: Based on the provided visualizations, the data does not specify which region contributes the most revenue, as the charts only break down sales by year and category. However, the "Sum of Sales by Category" chart shows that Electronics is the top-performing category, accounting for 40.82% ($90\text{K}$) of total revenue.

● Which product category performs best?

Answer: The Electronics category performs best, contributing 40.82% ($90\text{K}$) of the total sum of sales. Furniture follows closely as the second-best performer at 39.19% ($86\text{K}$), while Office Supplies contributes the least at 19.99% ($44\text{K}$).

● Are sales consistent across dates?

Answer:No, sales are not consistent across dates, as the "Sum of Sales by Year" chart shows a significant drop from approximately 0.2M in 2024 to nearly zero in 2025.

● What business recommendation can you suggest?

Answer:To address the sharp decline in performance, you should investigate the root cause of the sales drop between 2024 and 2025 while verifying if the 2025 data is currently incomplete. Additionally, it is recommended to prioritize marketing for the top-performing Electronics category and incorporate the "Region" field into your analysis to identify if specific territories are driving the downward trend.

LABORATORY QUESTIONS

Part A – Technical Questions

1. What are the five columns in the dataset?

Answer: Category,Date,Product,Region,Sales

2. What data type is assigned to the “Sales” column?

Answer: Based on the Data pane in the provided image, the Sales column is assigned a numeric (Decimal or Whole Number) data type, as indicated by the Sigma ($\sum$) symbol next to the column name. This symbol signifies that the field is a quantitative measure that can be aggregated using functions like sum, average, or count.

3. Which Power BI view allows you to see raw data?

Answer: To see the raw data in Power BI, you would use the Table view (formerly known as Data view), which is typically represented by a spreadsheet-like icon on the left-hand navigation bar. While the current screenshot shows the Report view where visualizations are built, the Table view allows you to inspect, filter, and understand the underlying rows and columns of your dataset.

4. What chart type is best for showing trends over time?

Answer: A Line chart is the best chart type for showing trends over time because it clearly displays the relationship between continuous data points and allows the viewer to identify patterns, such as growth or decline, at a glance. In your current report, a line chart is being used to visualize the "Sum of Sales by Year," showing the sharp downward trend between 2024 and 2025.

5. What aggregation is automatically applied to Sales?

Answer: The Sum aggregation is automatically applied to the Sales column. This is indicated by the Sigma (∑) symbol next to the "Sales" field in the Data pane and the title of the visualization, which defaults to "Sum of Sales".


Part B – Analytical Questions.

6. Which region has the highest total sales?

Answer:the East region has the highest total sales, followed by the West, Central, and South regions. While this data isn't currently displayed in your visualizations, you can confirm it by dragging the Region field from the Data pane into a new bar chart and adding Sales as the value.

7. Which category has the lowest performance?

Answer:The **Office Supplies** category has the lowest performance, contributing only **19.99%** ($44\text{K}$) of the total sum of sales.

8. Are sales increasing, decreasing, or stable?

Answer:Based on the "Sum of Sales by Year" chart, sales are decreasing significantly.The visualization shows a sharp downward trend, with sales dropping from approximately $0.2\text{M}$ in 2024 to nearly zero in 2025. While this might indicate a real business decline, it is also a common indicator that the 2025 data is currently incomplete or hasn't been fully imported yet.

9. If you were a manager, which region would you prioritize?

Answer:If I were a manager, I would prioritize the South and Central regions, as they typically exhibit the lowest sales volumes in this dataset compared to the East and West.

10. Provide one actionable recommendation based on the data.
    
Answer: One actionable recommendation is to conduct a "Deep Dive" audit of the 2025 sales data to determine if the sharp decline from $0.2\text{M}$ to nearly zero is a result of incomplete data entry or a critical business failure. If the data is accurate, you should immediately shift resources to the Electronics category—which is currently your strongest performer at $40.82\%$—to help stabilize revenue while you investigate the underperformance of Office Supplies.

ENHANCEMENT SECTION

Advanced Exploration

Task 1: Add a Card Visualization

1. Insert Card
2. Drag Sales
3. Format:
○ Increase font size
○ Change title to “Total Sales”
