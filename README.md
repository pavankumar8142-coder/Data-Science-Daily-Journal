# Data-Science-Daily-Journal
# 📘 Data-Science-Daily-Journal
**My daily data science learning log**
---
### 📅 11 May 2025  
**Day 1 – Introduction to Data Science**
---
#### ✅ Topics Covered:
- What is Data Science?
- Importance of data-driven decision-making
- Overview of key roles: Data Analyst, Data Scientist, Data Engineer
- Introduction to tools and technologies (Python, SQL, Excel, Power BI)
#### 🧠 Key Takeaways:
- Data Science combines statistics, computer science, and domain knowledge.
- Python and SQL are essential programming languages.
- Understanding data is more important than just modeling it.
---
### 📅 12 May 2025  
**Day 2 – Power BI Overview**
---
### 🔍 What is Power BI?
- Power BI is a **business analytics tool** by **Microsoft**, released in *2015*.
- It transforms raw data into interactive **dashboards** and **reports**.
- Designed for ease of use, with drag-and-drop interfaces and natural language queries.
---
### 🚫 Is Power BI Open Source?
- No, it's a **proprietary tool**.
- However, it provides **free versions** with limited capabilities.
- Can connect to a wide variety of **data sources**: Excel, SQL, SharePoint, Azure, APIs.
---
### 🧠 Key Concepts in Power BI:
- **Feature Engineering**:  
  Transforming raw data into features (columns) that better represent the problem.
- **Feature Selection**:  
  Choosing the most important columns for analysis to reduce complexity and improve performance.
- **Observations (Rows)**:  
  Each row represents a single record or event in your dataset.
---
### 📊 Power BI Use Breakdown (From a Data Analyst's Perspective):
| Component            | Purpose                                   | Time Spent (%) |
|---------------------|-------------------------------------------|----------------|
| Visualizations       | Creating charts, dashboards               | 60%            |
| Power Query Editor   | Data cleansing and transformation         | 30%            |
| Data Modeling        | Defining relationships, creating views    | 5%             |
| DAX                 | Writing measures and calculated columns   | 5%             |
---
### 💡 Notes:
- Visual storytelling is key—use color, labels, and interactivity wisely.
- Always ensure your data model is optimized before building reports.
- Power BI is widely used in business settings; mastering it adds significant value.
---
### 13 may-2025
## Power BI Learning Journey - Day 3
----
# Focus Areas
Today we dive deeper into the *visualization elements* of Power BI, especially those involving *maps, **legends, **labels, and **location options*. This guide explains:
- How to work with *Map* and *Filled Map* visuals
- Customize *Legends* and *Text Labels*
- Configure *Location Fields* for accuracy
---
## 1. Understanding Maps in Power BI
### 1.1 Map Visual
Power BI’s standard *Map* visualization uses Bing Maps to plot data points as bubbles on a map.
*Use Case:* Best for showing *individual locations* (e.g., cities, stores, customer addresses).
#### How to Create:
1. Select the *Map* visual from the Visualizations pane.
2. Drag a geographic field (like City, Country, State) into the *Location* field well.
3. Drag a numerical value (e.g., Sales) into the *Size* field.
4. Optionally add a field to *Tooltips* to show more info on hover.
#### Customization Options:
- *Legend*: Add a categorical field (like Region) to the *Legend* well to color-code bubbles.
- *Size*: Larger values = larger bubbles.
- *Color saturation* (deprecated in map): Use *Conditional Formatting* or choose Filled Map if you want shaded areas.
---
### 1.2 Filled Map Visual
A *Filled Map* (also called a choropleth map) shades areas based on values.
*Use Case:* Best for showing *aggregated data* across regions (e.g., total revenue by country or state).
#### How to Create:
1. Select the *Filled Map* visual.
2. Drag a field like Country, State, or Postal Code into *Location*.
3. Drag a numerical value into *Values*.
#### Key Notes:
- Ensure the geographic field is *unambiguous* (e.g., “Georgia” could mean a state or country).
- You can modify the *Data Category* of the field in the *Model View* (e.g., set State to *State or Province*).
---
## 2. Legends in Power BI
### Purpose of Legends:
Legends describe the categories shown using different *colors* on visuals like *maps, **charts*, etc.
### Legend Configuration:
- Go to the *Visualizations* pane > *Format* > *Legend*
- Options:
  - *Position*: Top, Bottom, Left, Right, etc.
  - *Title*: Rename the legend
  - *Text Size, **Font, and **Color*
#### Tips:
- Always keep the legend *visible* when multiple categories are shown.
- Keep names *short and intuitive* to avoid overlap.
---
## 3. Configuring Location Fields
### Best Practices:
1. Use separate fields for Country, State, City, Postal Code instead of combining into one.
2. Set correct *Data Category*:
   - City → City
   - State → State or Province
   - Country → Country/Region
   - Zip → Postal Code
### How to Set:
1. Go to *Model View*.
2. Select the field.
3. In the *Properties pane, set the **Data Category*.
### Why Important?
It helps *Bing Maps resolve the location correctly* and prevents mapping errors.
---
## 4. Labels and Text Elements
### 4.1 Data Labels
Data labels show numeric values (e.g., totals, counts) on visuals.
*For Maps:*
- You can’t directly label on Map/Filled Map, but you can use *Tooltips* and *Legends* for clarity.
*For Charts:*
- Toggle *Data Labels* in the Format pane.
- Options: font size, color, position.
---
### 4.2 Text Boxes and Titles
You can add static or dynamic text using:
#### Text Box
1. Go to *Insert > Text Box*
2. Enter your title, caption, or description
3. Format with font size, color, bold/italic, alignment
# 📊 Power BI Learning Journey -day -4
## 1. Numeric Card
*Purpose*: Display a single, prominent value such as total sales, profit, or count.
*Steps*:
- Go to the Visualizations pane and select *Card*.  
- Drag a measure (e.g., Total Sales) into the *Fields* area.
- Customize fonts, colors, and display units via the *Format* pane.
*Use Case*: Highlight key performance indicators (KPIs).
---
## 2. Table
*Purpose*: Show detailed data in rows and columns.
*Steps*:
- Select the *Table* visual.
- Drag fields into the *Values* area.
- Use the *Format* pane to customize styles, sorting, and column formats.
*Use Case*: Display raw data like transaction records.
---
## 3. Matrix
*Purpose*: Create a pivot-style summary with row and column groupings.
*Steps*:
- Select the *Matrix* visual.
- Drag fields into *Rows, **Columns, and **Values* areas.
- Use expand/collapse and subtotals for better structure.
*Use Case*: Show performance by category and time (e.g., sales by region/month).
---
## 4. Pie Chart
*Purpose*: Show part-to-whole relationships with slices.
*Steps*:
- Insert a *Pie Chart*.
- Add a category field to *Legend, and a numeric field to **Values*.
- Customize labels, tooltips, and slice colors.
*Use Case*: Visualize proportions like revenue share by product.
---
## 5. Donut Chart
*Purpose*: Like a pie chart but with a center area for total display.
*Steps*:
- Choose the *Donut Chart* visual.
- Set *Legend* and *Values*.
- Use the center to show totals or KPIs.
*Use Case*: Show categorical proportions with emphasis on the total.
---
## 6. Conditional Formatting
*Purpose*: Highlight data based on rules with colors, icons, or bars.
*Steps*:
- Click dropdown beside a field in a *Table* or *Matrix*.
- Select *Conditional Formatting* (Background color, Font color, Data bars, Icons).
- Define custom rules or use default scaling.
*Use Case*: Highlight top-performing salespeople or risky regions.
---
## 7. Funnel Chart
*Purpose*: Visualize sequential processes with drop-offs at each stage.
*Steps*:
- Select the *Funnel Chart*.
- Add a categorical field to *Group, and a numeric field to **Values*.
- Customize colors and label placements.

## power Bi learning Journey - Day -5
- *Bars* = Horizontal
- *Columns* = Vertical
- Both types can show grouped (clustered) or stacked values for comparison.
---
## 2. Data Table

| Region | Segment   | Sales | Profit |
|--------|-----------|-------|--------|
| East   | Consumer  | 80    | 8      |
| West   | Corporate | 120   | 12     |
| Central| Corporate | 90    | 9      |
| East   | Consumer  | 60    | 6      |
| West   | Consumer  | 70    | 7      |
| Central| Consumer  | 110   | 11     |
| East   | Corporate | 100   | 10     |
| West   | Corporate | 130   | 13     |
- *Total Sales (S)* = 760  
- *Total Profit (P)* = 76
---
## 3. Regional Sales Calculation
- *E(S)* = 80 + 60 + 100 = *240*
- *W(S)* = 120 + 70 + 130 = *320*
- *Central(S)* = 90 + 110 = *200*
---
## 4. Segment-wise Sales per Region
- *East*
  - Consumer: 80 + 60 = *140*
  - Corporate: *100*
- *West*
  - Consumer: *70*
  - Corporate: 120 + 130 = *250*
- *Central*
  - Consumer: *110*
  - Corporate: *90*
---
## 5. Stacked Bar Chart (Horizontal)
| Region | Total Sales |
|--------|-------------|
| East   | 240         |
| West   | 320         |
| Central| 200         |
- *Labels* on Y-axis
- *Values* on X-axis
---
## 6. Stacked Column Chart (Vertical)
| Region | Total Sales |
|--------|-------------|
| East   | 240         |
| West   | 320         |
| Central| 200         |
- *Labels* on X-axis
- *Values* on Y-axis
---
## 7. Clustered Bar Chart (Horizontal)
Shows segmented sales by *Consumer* and *Corporate* for each region.
| Region | Consumer | Corporate |
|--------|----------|-----------|
| East   | 140      | 100       |
| West   | 70       | 250       |
| Central| 110      | 90        |
- *Bars* grouped per region
- Horizontal orientation
---
## 8. Clustered Column Chart (Vertical)
Same data as above but visualized vertically.
| Region | Consumer | Corporate |
|--------|----------|-----------|
| East   | 140      | 100       |
| West   | 70       | 250       |
| Central| 110      | 90        |
- *Grouped columns*
- X-axis: Regions
- Y-axis: Values
---
## Notes
- *Bar Charts*: Horizontal (Y-axis = categories, X-axis = values)
- *Column Charts*: Vertical (X-axis = categories, Y-axis = values)
- *Stacked*: Combines values per category
- *Clustered*: Groups values side-by-side for comparison
---
## Summary
This session focused on understanding the *structure, types, and interpretation* of bar and column charts using real sales data by segment and region.
 Visualizations included both *stacked* and *clustered* styles in *bar* and *column* formats.

## power Bi learning Journey -Day -6

# Ribbon Chart

## How It Works
- Categories are *stacked* and *reordered* at each time interval, with *ribbons* connecting their positions.
## Purpose
- Visualizes *ranking changes* of data categories (e.g., products, regions) over time.
## Key Insight
- Shows which category dominates at each time point and how the ranking evolves.  
  Example: Product A overtakes Product B in Q2.
---
## Data Requirements
1. *X-axis*: Time-based field (e.g., year, month, quarter).
2. *Y-axis*: Numeric measures (e.g., sales, profit).
3. *Legend*: Categorical field (e.g., product, region).
---
## Example Sample Data
| Month     | Product | Sales |
|-----------|---------|-------|
| Jan 2023  | A       | 500   |
| Jan 2023  | B       | 300   |
| Feb 2023  | A       | 450   |
| Feb 2023  | B       | 600   |
---
## Why Use a Ribbon Chart?
1. *Track Dominance*:  
   Instantly see which category leads at each time interval.
2. *Identify Trends*:  
   Spot rising or falling categories.
3. *Competitive Analysis*:  
   Compare performance across segments.
---
## Best Use Cases
- *Market share shifts* between competitors.
- Ideal for *storytelling* who's winning and losing over time.
## Scatter Plot (Linear Regression)
### What is the difference between:
- *Univariate Analysis*
- *Bi-variate Analysis*
- *Multi-variate Analysis*
> *Histogram* is used to find the amount of data between the intervals.
---
## Univariate Analysis
*Definition*: Univariate Analysis = ID representation of data (one variable). It’s analyzing a single variable at a time.
 The main goal is to describe and summarize the variable’s characteristics.
### Types of Variables:
- *Numerical* (continuous or discrete)
- *Categorical* (nominal, naming, or ordinal)
---
## Techniques - Numerical Data:
- Summary Statistics (mean, median, std dev)
- Histograms
- Box Plots
- Density Plots
### Categorical Data:
- Frequency Tables
- Bar Plots
- Pie Charts
---
## Purpose:
- Understand the distribution (normal, skewed)
- Calculate central tendencies (mean, median, mode)
- Calculate dispersions (range, variance, std dev)
- Identify outliers (skewness, kurtosis)
### Example:
Analyzing the age of customers in a dataset:
- Mean age = 35.7
- Age distribution = right-skewed
- Outliers = ages above 80
---
## Bi-variate Analysis (Two variables) → 2D representation
*Definition*: Bi-variate analysis explores the relationship between two variables. It helps in identifying correlation/association.
### Types of Variable Combinations:
| Variable 1 | Variable 2 | Common Methods                         |
|------------|------------|----------------------------------------|
| Numerical  | Numerical  | Scatter Plots / Correlation / Regression |
| Numerical  | Categorical| Boxplots / t-test / ANOVA              |
| Categorical| Categorical| Grouped Bar Plot / Cross-tabulation    |
### Example:
Analyzing relationship between education level (categorical) and average salary (numerical).
- Higher education → Higher average salary
- Use Box Plot or ANOVA for significance testing
- Scatter plot → If numeric on x and y axis
---
## Multivariate Analysis
*Definition*: 3 or more variables (one representation). We are going to compare with other representation.
Example: pair plot
---
## Outliers
*Definition*: An outlier is:
1. A data point that differs significantly from other observations.
2. A value much higher or lower than most of the others in a dataset.
3. Someone or something that stands out from the rest; an anomaly.
---
## Line Chart
- *x-axis*: date, time field, places
- *y-axis*: numeric field (e.g. sales, revenue, values)
- *Legend*: category field (region, product)
### Trend Analysis
Show how a value (e.g. sales...) changes over time
- Detect upward/downward trends, seasonality, and patterns
---
## Area Chart
Also same as line chart but filled with color.
## learning power bi day -7

# Treemap
1. Treemaps show data in nested rectangles for easy comparison.
2. Use them to visualize categories and their values, like sales or inventory.
3. Rectangle size shows the value (e.g., total sales).
4. Colors help separate different categories.
5. Pick the treemap icon from "Visualizations" in Power BI.
6. Drag a category (e.g., Region) to the "Category" field.
7. Drag a number (e.g., Sales) to the "Values" field.
8. Add hierarchy (e.g., Region > Product) for nested view.
| Feature       | Legend         | Detail                       |
|---------------|----------------|------------------------------|
| Purpose       | color grouping | Show individual data points |
| Visual types  | Bar, line, pie, etc. | Scatter chart, map, etc. |
| Grouping?     | yes            | NO                           |
| Color split?  | yes            | NO                           |
---
- *Nobody will use Treemap in real time*
  1. It occupies most of the space.
  2. It will take a lot of time for developer.
  ### Waterfall Chart?
A Waterfall chart shows how you move from starting values to an ending value by showing all the increases and decreases along the way.
---
