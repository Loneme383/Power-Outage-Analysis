

# Power Outage -Dashboard

### Dashboard Link :https://app.powerbi.com/links/plL2uS0r0T?ctid=e211321f-b810-409b-8a2d-68db91a64a14&pbi_source=linkShare
## Project excerpt

This project involves developing a comprehensive dashboard to analyze and monitor significant electric disturbance events across various U.S. regions. The dashboard provides a high-level overview and regional insights into the impact of power outages, helping stakeholders identify patterns, regional vulnerabilities, and the effects of major events on energy demand and population impact.
Leveraging a structured data model, the dashboard aggregates data from numerous electric disturbance events, categorized by event types, geographic areas affected, and the scale of disruption. Key metrics, such as total customers affected, demand loss in megawatts (MW), and restoration times, allow for in-depth analysis of event severity and recovery efficiency.



### Key Dashboard Insights:
•	Customer Impact Summary Page: Presents total figures for customers affected, downtime duration, demand loss, and number of events, with yearly trends shown for each metric to capture historical changes in outage severity.
•	Regional Analysis Page: Allows users to drill down by state, viewing event frequency and customer impact over time. A map visualization highlights areas most affected, providing geographical context and enabling quick regional comparisons.

### Data Model and Measures: The data model captures detailed event attributes such as:
•	Time and Duration: Event start, and end times allow precise calculations of duration and restoration time.
•	Impact and Scale: Metrics like Number of Customers Affected and Demand Loss (MW) give insight into both the human and economic impact of each event.
•	Regional Breakdown: Filters for NERC regions, event types, and affected areas support targeted analysis.

## Assumptions and remarks

### Cleaning Steps
1.	Header Promotion: Setting the first row as column headers for consistency.
2.	Data Type Conversion: Assigning correct data types (e.g., text, date, integer) to columns for accurate processing.
3.	Row Filtering: Removing irrelevant rows (e.g., notes, empty rows, month names) to keep only essential data entries.
4.	Adding Year and Month Columns: Extracting and adding columns for "Event Year" and "Event Month" based on event dates.
5.	Column Renaming: Standardizing column names for clarity, such as renaming "Table B.2." to "Date Event Began" or updating other columns to match a specific naming convention.
6.	Value Replacement: Replacing placeholders (e.g., "Unknown", "N/A") with nulls and standardizing ranges or time formats.
7.	Column Reordering: Organizing columns in a logical sequence for readability and analysis
8.	Standardize and Consolidate Data: Combine yearly data into a single dataset, apply filters to ensure consistent location names, remove unwanted rows, and reorder columns for a clear, analyzable structure

9. The report was then published to Power BI Service.
 
 
![Publish_Message](https://user-images.githubusercontent.com/102996550/174094520-3a845196-97e6-4d44-8760-34a64abc3e77.jpg)

# Snapshot of Dashboard (Power BI Service)

![image](https://github.com/user-attachments/assets/a274321c-7305-450c-8da9-b8158f220163)


 
 # Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload]![Screenshot 2024-11-07 180927](https://github.com/user-attachments/assets/93d2dd03-87a6-4f9b-b0cb-7a140ba863fc)


### Recommendations
These are some suggestions to handle the threat coming from event types:
### Weather or natural disaster

1. Power lines in the ground: hiding power lying higher than the surface reduces chances of damage and outages if any occur. Though it is an expensive and lengthy method, it serves a better purpose in making the electrical supply systems more dependable.

2. Auxiliary power systems: Temporary supply of energy can be provided with the use of standby power sources or energy storage devices. Such systems are useful for sustaining the operations of essential establishments like hospitals or emergency response units and for the quick rehabilitation of power supply later.

3. Vegetation control: It is beneficial to periodically cut back the trees or bushes growing along the electric wires since they could break off in strong winds and cause disruption to the services. This practice reduces the scenarios whereby power lines connecting trees snap and blackout the whole region.

### Operational system failure

1. Redundancy and backup systems: The power grid system can be reinforced with additional components in each layer to guarantee that the system works without interruption. This will entail providing spare elements of some critical parts or systems such as transformers and control systems as well as providing stand-by power or alternative sources.

2. Response and recovery plans: Creating a clear plan to address potential problems and how to deal with their effects if they embrace the system is necessary to flatten the curve of effects that failings of the systems include. This involves quick restoration strategies, establishing alternative energy supply strategies and alerting the relevant parties to the crisis.


