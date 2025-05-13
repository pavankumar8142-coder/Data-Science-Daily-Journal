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

