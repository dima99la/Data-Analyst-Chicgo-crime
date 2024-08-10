Overview of the Project
This project aims to analyze the network speed and coverage across different regions and towns in Catalonia, Spain, using a large dataset that includes various network parameters such as speed, network type (2G, 3G, 4G), geographical location, and operator information.

1. Data Cleaning
The project begins with data cleaning to ensure the dataset is ready for analysis. This includes:

Dropping unnecessary columns (downloadSpeed, uploadSpeed).
Removing rows with missing values.
Creating a datetime object from separate date and hour columns for easier time-based analysis.
2. Exploratory Data Analysis (EDA)
The initial exploration involves:

Visualizing the relationship between time and network speed, showing how speed varies throughout the day and across different years.
Grouping and analyzing data by operator to compare the performance of the top three operators (Movistar, Vodafone ES, and Orange) using pivot tables.
Assessing the conditional probability of network states (e.g., STATE_IN_SERVICE) based on user activities, revealing insights into how network performance varies with different activities.
3. Geographical Mapping
Geospatial analysis is conducted to visualize network speed distribution across Catalonia:

A map is plotted showing towns with median network speeds above 50 Mbps and those below 50 Mbps, highlighting areas with faster and slower network speeds.
The analysis identifies a significant variation in network performance across different towns, with more areas experiencing slower speeds.
4. Network Type Analysis
The project further explores the distribution and performance of different network types (2G, 3G, 4G):

Heatmaps and geographical plots reveal the spread and concentration of each network type.
Pivot tables and bar plots are used to compare the count of measurements and network usage across towns, emphasizing that 4G, despite being the fastest, is less widespread compared to 3G.
5. Regional Analysis
The dataset is enriched by adding a region_code based on postal codes, dividing Catalonia into four regions: Barcelona, Girona, Lleida, and Tarragona. This allows for:

A focused analysis on how network speed varies across these regions.
Identifying Barcelona as the region with the highest need for infrastructure improvement, despite having the most 4G coverage concentrated in the city of Barcelona.
6. Recommendations
Based on the findings, the project concludes with recommendations to improve network infrastructure across Catalonia, particularly in regions with slower speeds. The analysis suggests that the government should focus on spreading high-speed networks (4G) beyond the main cities to ensure more uniform network performance across the entire region.

This comprehensive analysis provides valuable insights into the current state of network performance in Catalonia, highlighting areas for potential improvement in network infrastructure.
