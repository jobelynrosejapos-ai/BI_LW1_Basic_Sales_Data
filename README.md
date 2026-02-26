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




