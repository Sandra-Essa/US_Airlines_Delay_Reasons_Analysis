# US_Airlines_Delay_Reasons_Analysis and Visualization
 

- [Description](#description)
- [Samples](#samples)
- [Implementation Details](#implementation-details)
    - [Solution](#solution)
- [Tools](#Tools)


## Description
Examine data pertaining to airport delays to develop an intuitive and user-friendly dashboard. 
The objective is to offer insights into the causes of delays and enable users to filter data by airport, airline, and period. 
This facilitates informed decision-making and enhances overall airport operations. 

## Samples
![Demo Sample](https://github.com/Sandra-Essa/US_Airlines_Delay_Reasons_Analysis/blob/main/Media/US%20Airlines%20Analysis.gif)

![Demo Sample](https://github.com/Sandra-Essa/US_Airlines_Delay_Reasons_Analysis/blob/main/Media/Star%20Schema.png)

## Implementation Details

### Solution

Methodology: To ensure an efficient and effective analysis, the project adopted a star schema approach in data modeling. 
This approach enhances the structure of the dataset, facilitating a streamlined and organized exploration.

Dimensional Modeling:
DimAirports: Extracted and compiled data on worldwide airports, associating IATA codes with airport names for a more user-friendly visualization experience.
DimCancellation: Deciphered cryptic cancellation codes (N, A, B, C) to provide clear and comprehensible reasons, enhancing the interpretability of the data.
DimFlights, DimDelay, DimDate, DimTime: Developed dimensional structures tailored for in-depth analysis, ensuring a thorough exploration of relevant aspects.

Visualization Techniques:

Measures Table: 
Leveraged DAX (Data Analysis Expressions) to create robust measures, enabling accurate and dynamic insights.
Tool Tip: Improved the user experience by implementing informative tooltips for visual elements, offering additional context and details.
Drill-Through: Enabled users to explore specific data points more deeply, fostering a comprehensive understanding of the dataset.
Q&A Chart: Implemented natural language queries, allowing users to interactively explore and report insights.
Synced Slicer: Ensured consistency across multiple visualizations by implementing synchronized slicers.
Bookmarks & Buttons: Designed an interactive dashboard using bookmarks and buttons, enhancing the user experience and enabling seamless navigation.
Filters: Applied strategic filters to refine the data, focusing on relevant insights and facilitating a more targeted analysis.

 ## Tools
 Microsoft Power BI Desktop
 Data source: https://www.kaggle.com/datasets/giovamata/airlinedelaycauses?select=DelayedFlights.csv
   
    
