# 📊 Project Overview

The Hotel Insights Dashboard provides a detailed analysis of hotel performance metrics such as revenue, occupancy, ADR, realization %, and booking trends. It helps hotel management and analysts understand business performance across different cities, room categories, and booking platforms.

## 🧩 Key Features

Interactive filters by Cities and Rooms

### KPIs including:

- Revenue (Total: 1.71B)

- RevPAR (Revenue per available room)

- DSRN (Daily Sellable Room Nights)

- Occupancy %, ADR, Realisation %

- Revenue split by Business and Luxury categories

- Trend analysis of RevPAR, ADR, and Occupancy % over time

- Property-level performance metrics (Revenue, Occupancy, ADR, Realisation %, Cancellation %, Ratings)

- Realisation % and ADR by booking platform

- Weekly Revenue trends by category (Business vs Luxury)

- Weekday vs Weekend performance comparison using a custom matrix

# ⚙️ Challenges Faced

- #### Creating the HospitalityIQ Dashboard came with several technical and data-related challenges:

- #### Weekend Classification Issue –
The dataset defined weekends as Friday and Saturday instead of the conventional Saturday–Sunday. This required building a custom date matrix and calculated columns to correctly categorize and analyze weekday vs weekend data.

- #### Dynamic Filtering & Relationships –
Ensuring that slicers and filters dynamically updated KPIs, charts, and property-level visuals without breaking data relationships demanded precise data modeling and DAX filtering logic.

- #### Data Cleaning & Consistency –
Handling inconsistent entries, missing values, and merging city-level data into a unified structure using Power Query transformations was crucial for accurate visualization.

- #### Performance Optimization –
Large datasets and multiple visuals caused initial performance lag, which was improved by optimizing DAX calculations and reducing visual load.

## 🛠️ Tools & Technologies

- Power BI – Dashboard Design & Data Visualization

- Excel / CSV – Source Dataset

- Power Query & DAX – Data Cleaning, Transformation, and Calculations

## 📈 Insights
  
- The Luxury segment contributes slightly more revenue than Business (58% vs 57%).

- Occupancy rate averages around 58%, with weekends performing better.

- Realisation % across booking platforms remains stable around 70%.

- A drop in Revenue is observed after Week 30, especially in the Luxury category.

## 🖼️ Dashboard Preview

