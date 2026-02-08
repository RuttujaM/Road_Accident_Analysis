# Road Accident Analysis & Casualty Insights Dashboard  
A comprehensive analytical dashboard designed to uncover patterns, trends, and risk factors in road accidents. It enables data-driven decision-making by visualizing casualty severity, location, vehicle type, and environmental conditions across multiple years.  

This dashboard analyzes UK road accident raw data from 2021 and 2022 to identify patterns in casualties across time, location, and conditions. It provides year-over-year comparisons to highlight changes in accident severity and volume. Key factors such as vehicle type, road type, surface condition, lighting, and urban versus rural areas are explored. The dashboard enables stakeholders to drill down into high-risk scenarios and evaluate the effectiveness of safety measures. It is designed for both operational monitoring and strategic road safety planning.  

## The dashboard was built using the following tools and technologies:  
📊 Power BI Desktop - Used as the primary data visualization and reporting platform to design interactive dashboards, KPI cards, charts, slicers, and drill-down views for UK road accident analysis.  
📂 Power Query (ETL Layer) - Utilized for data cleaning, transformation, and reshaping of raw accident data. A customized calendar table was created to support time intelligence calculations, year-over-year comparisons, and monthly trend analysis.  
🧠 DAX (Data Analysis Expressions) - Implemented to build calculated measures such as total casualties, fatal/serious/slight casualties, percentage contributions, and dynamic year comparisons. DAX logic was also used to enable conditional formatting and responsive visuals.  
📝 Data Modeling - Established optimized relationships between the custom calendar table and the accident fact table to enable accurate aggregations, cross-filtering, and time-based analysis across visuals.    
🗄 SQL Server Management Studio (SSMS) - Used SQL Server as the backend validation layer to write and execute queries for verifying KPI values, trend calculations, and category-wise aggregations against Power BI outputs.  
📄 Microsoft Excel (.xlsx) - Utilized for initial data inspection, sanity checks, and cross-verification of summary metrics before visualization. Also served as a reference layer to validate Power BI and SQL results.  
📁 File Formats & Deliverables -     
.pbix – Power BI development and modeling file  
.png – Dashboard snapshots for documentation and portfolio showcase  
.xlsx – Raw and validated datasets    
.sql – SQL queries used for KPI and trend validation  

## 🧩 Business Problem:  
Road accidents continue to cause significant loss of life and economic damage, yet decision-makers often lack a consolidated, insight-driven view of accident data. Raw datasets make it difficult to identify where, why, and under what conditions casualties are increasing. Without clear visibility into trends by severity, location, road type, and vehicle category, authorities struggle to prioritize safety initiatives effectively.  

## 🎯 Goal of the Dashboard:  
  - To provide a single source of truth for road accident and casualty analysis  
  - To identify high-risk road conditions, vehicle types, and locations  
  - To compare current year vs previous year performance and measure improvement or deterioration  
  - To enable data-driven policy decisions aimed at reducing fatalities and serious injuries  
  - To support proactive safety planning rather than reactive reporting  

## 📈Key Dashboard Features  
### •  KPI Summary Cards :   
   - Total casualties, fatal, serious, and slight casualties  
   - Year-over-year percentage change to track improvement or decline  
   - Clear visual hierarchy for executive-level consumption  
### •  Casualties by Severity :  
   - Breakdown of Fatal, Serious, and Slight casualties  
   - Percentage contribution to total casualties for quick risk assessment  
### •  Monthly Trend Analysis (CY vs PY) :   
   - Line chart comparing current year and previous year monthly casualties  
   - Helps identify seasonal spikes and recurring risk periods  
### •  Vehicle Type Analysis :   
   - Casualties segmented by Cars, Bikes, Vans, Buses, Agricultural, and Others  
   - Highlights vehicle categories contributing most to casualties  
### •  Road Type & Road Surface Analysis :   
   - Identification of high-risk road types such as single carriageways and roundabouts  
   - Road surface conditions (Dry, Wet, Snow/Ice) to assess environmental impact  
### •  Urban vs Rural Distribution :   
   - Casualty comparison between urban and rural areas  
   - Percentage split to support targeted safety strategies  
### •  Light Condition Analysis :   
   - Daylight vs Darkness casualty distribution  
   - Helps assess visibility-related risks  
### •  Interactive Filters :   
   - Year, road surface, weather, and area-type slicers  
   - Enables dynamic, user-driven exploration of data  

## 💡 Business Impact & Insights :  
   - Identified that single carriageways account for the highest number of casualties, indicating critical infrastructure risk zones  
   - Revealed that urban areas contribute a larger share of casualties compared to rural areas, supporting targeted urban safety programs  
   - Showed that cars are the most involved vehicle type, highlighting the need for focused driver safety initiatives  
   - Detected seasonal trends with higher casualties during specific months, enabling proactive enforcement and awareness campaigns  
   - Demonstrated a year-over-year reduction in fatal and serious casualties, helping assess the effectiveness of existing road safety measures  
   - Enabled stakeholders to shift from static reports to data-driven decision-making, improving prioritization of safety investments

<img width="1280" height="723" alt="Snapshot of PowerBi Dashboard" src="https://github.com/user-attachments/assets/7a7d2dae-2c03-4aa7-a3e7-6d79189e9922" />
<img width="1669" height="670" alt="Snapshot of Excel dashboard" src="https://github.com/user-attachments/assets/ee5bd5af-7407-44de-8219-fe4af8b43049" />
<img width="1844" height="678" alt="Snapshot of Data analysis sheet" src="https://github.com/user-attachments/assets/5142713b-da70-4665-ac2a-ff63997e8678" />

