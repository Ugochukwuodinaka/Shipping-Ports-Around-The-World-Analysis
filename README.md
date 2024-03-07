# Shipping Ports Around The World Analysis
![](images/Shipping_Ports_image.jpg)


## Project Overview

### Introduction:
The question has changed over time as maritime operations have improved and stakeholders’ needs have altered. Today, a seaport serves different functions than what it did for several decades. Seismic changes, such as the growth of China as a manufacturing giant, have substantially changed the industry. But the biggest difference is the role that seaports now play in the wider global economy. Time was that a seaport would simply be a place to unload or load goods from a vessel. Today, seaports are central to any manufacturer’s supply chain plan and are ranked based on several aspects. These could be the amount of automation equipment they possess, the skill of their workforce, its access to key markets, and the depth of its berth.
Increasingly, data and the ability of a seaport to process and share it among stakeholders is what supply chain companies are looking for. This then raises a further set of questions, such as ‘What is a smart port?’ Although frequently located on a seacoast or estuary, some ports can be situated miles inland, with access to the sea via river or canal. If a port is located on a lake, river, or canal that goes to a sea or ocean, that port can be defined as an inland port. Ports can also be called a harbor.

The "Shipping Ports Around The World Analysis" project aims to provide insights into the global shipping industry by analyzing data related to shipping ports worldwide. The project will involve gathering, processing, and analyzing data pertaining to various aspects of shipping ports, including port country, traffic volume, port name, port types, UN Code, vessels volume in ports, geographical distribution, and operational efficiency. 


### Objectives:
- Determine the total number of ports worldwide categorized by type to provide an overview of global port infrastructure.
- Identify the top 10 ports with the highest number of vessels in traffic to pinpoint major maritime hubs and assess their significance in global shipping networks.
- Determine the top 10 countries with the most number of ports to understand regional variations in port infrastructure and maritime connectivity.
- Identify the top 10 ports with the most expected arrival vessels to understand the busiest ports in terms of incoming maritime traffic.
- Determine the top 10 ports with the most traffic by area globally to gain insights into the spatial distribution and magnitude of maritime activities on a global scale.
- Identify the top 10 ports with the most traffic by area locally to understand regional variations in port activity and traffic distribution.
- Examine the trends of the top 20 ports over time, including vessels in port, vessels departed, and vessels arrived, to identify patterns, fluctuations, and growth trajectories in maritime activities.
- Create a geospatial map illustrating the locations of ports across continents to visualize the global distribution of port infrastructure and its relationship with geographical features.


### Deliverables:
- I will render a summary of the total number of ports worldwide by type, providing insights into the composition and distribution of global port infrastructure.
- Will list of the top 10 ports by vessels in traffic, along with relevant statistics and analysis highlighting their importance in global maritime transportation.
- Will identify the top 10 countries with the most number of ports, accompanied by analysis showing regional disparities and maritime connectivity.
- Will render a compilation of the top 10 ports with the most expected arrival vessels, offering insights into the busiest ports in terms of incoming maritime traffic.
- Will analyze the top 10 ports with the most traffic by area globally, providing insights into spatial distribution and magnitude of maritime activities.
- Will analyze the top 10 ports with the most traffic by area locally, offering insights into regional variations in port activity and traffic distribution.
- Will create an analysis of traffic trends for the top 20 ports, presenting visualizations and interpretations of vessels in port, vessels departed, and vessels arrived over time to discern patterns and growth trajectories.
- Will generate an interactive map showcasing the locations of ports across continents, providing a visual representation of global port infrastructure and its spatial distribution.


### Dataset Overview
This dataset containing useful data of 450+ ports around the world. The dataset comprises of vital information crucial for a deep insight into the locations and operations of shipping ports around the world. It includes fields such as Serial_No, Country, Port Name, UN Code, Vessels in Port, Departures(Last 24 Hours), Arrivals(Last 24 Hours), Expected Arrivals, Type, Area Local, Area Global, and Also known as. By analyzing this dataset, we aim to uncoverports type, location, arrival and departure traffic volume, and more.

This dataset is a CSV file made up of a single table named Ports_Data and was provided by [Quantum Analytics](https://www.quantumanalyticsco.org/). You can click on this [link](Shipping-Ports-Around-The-World-Analysis/blob/main/Port_Data.csv) to preview the raw data file. This dataset table is made up of 12 fields and 480 rows of ports data.

Below are some information on the fields we have in this dataset for a better understanding of this analysis:
- __Serial_No:__ This field represents a unique identifier or serial number assigned to each entry or row in the dataset. It serves as a reference number for tracking and organizing the data.
- __Country:__ This field indicates the country in which the port is located. It provides information about the geographical location or jurisdiction of the port.
- __Port Name:__ This field contains the name or designation of the port. It identifies the specific port within the country and serves as a label for referencing and distinguishing between different ports.
- __UN Code:__ The UN Code is a unique identifier assigned to each port by the United Nations (UN). It provides a standardized code for identifying ports internationally, facilitating communication and data exchange across different systems and organizations.
- __Vessels in Port:__ This field represents the number of vessels currently present at the port. It indicates the level of maritime activity and congestion at the port at a given point in time.
- __Departures (Last 24 Hours):__ This field indicates the number of vessels that have departed from the port within the last 24 hours. It provides information about recent outbound maritime traffic from the port.
- __Arrivals (Last 24 Hours):__ This field indicates the number of vessels that have arrived at the port within the last 24 hours. It provides information about recent inbound maritime traffic to the port.
- __Expected Arrivals:__ This field indicates the number of vessels expected to arrive at the port within a specified time frame, typically within the next few days. It provides advance notice of incoming maritime traffic and helps port authorities and stakeholders plan and manage port operations effectively.
- __Type:__ This field categorizes the port based on its primary function or specialization. Common port types that were provided in this analysis are ports, anchorage, marina and canal.
- __Area Local:__ This field refer to the local geographical area or region in which the port is situated. It provides additional context about the port's location within its immediate surroundings.
- __Area Global:__ This field refer to the global geographical region or area to which the port belongs. It provides information about the port's broader geographical context and its connection to global maritime networks.
- __Also known as:__ This field contain alternative names or aliases for the port. It provides additional information about how the port may be referred to in different contexts or languages.


### Skills Utilized
1. Data Cleaning
2. Data Modelling
3. Data Visualiziation
4. Descriptive Analytics
5. Critical Thinking and Problem Solving
6. Communication and Reporting

### Tools Used
1. Power Query Editor
    - Was used to:
        1. Extract,
        2. Clean,
        3. Transform,
        4. Load all the datasets for this analysis.
           
2. Power BI (Was used to create reports and dashboard for this analysis)
    - The following Power BI Features were incorporated:
        1. DAX
        2. Quick Measures
        3. Page Navigation
        4. Filters
        5. Tooltips
        6. Button

### Data Cleaning, Transformation and Loading using MS Sql Server:
1. Was able to find online and fill in most of the missing __UN Code__ with the help of the __Country__ and __Port Name__ details provided.
2. Was able to find online and fill in the missing __Country__ details with the aid of the __Port Name__ and __UN Code__ details provided.
3. Used __-__ (hyphen) for the __UN Code__ details that couldsn't be found.
4. Changed all data types of the fields in the table to the right data type.


**Power Query View**

Power Query Screenshot                                                             |                                
:---------------------------------------------------------------------------------:|
![](images/Power_Query_Screenshort.png)

You can access the complete Power BI project document [here](SHIPPING%20PORTS%20AROUND%20THE%20WORLD%20ANALYSIS.pbix).


## Data Modelling
No data modelling was required since we needed just a table for the analysis.


## Visualization in Power BI:
#### Report View 1
![](images/Shipping_Ports_Around_The_World_Analysis_Dashboard1.jpg)

#### Report View 2
![](images/Shipping_Ports_Around_The_World_Analysis_Dashboard2.jpg)

### Project Analysis:
From the analysis, i made the following Key findings below:
- The Total Number of Ports is __480.__
- The Total Vessels In Port is __73,590.__
- Total Arrived Vessels is __52,158.__
- Total Expected Vessels is __18,832.__
- Number of Port Types is __4.__

- <img src="images/Total_No_Of_Ports_By_Type.jpg" width="300">
- **Total Number of Ports By Type:**
- In this analysis of the Total Number of Ports By Type, i was able to coome up with the following insights:
- __Port Type Distribution:__ The dataset provides a breakdown of port types, including Port, Anchorage, Marina, and Canal. The majority of the entries fall under the category of traditional __"Ports,"__ constituting approximately 81.46% of the total. __"Anchorage"__ comes next, representing 13.75% of the total, indicating a significant presence of locations where vessels anchor rather than dock. __"Marina"__ and __"Canal"__ types contribute relatively smaller percentages, accounting for 3.75% and 1.04%, respectively.
- __Implications of Port Types:__ The dominance of traditional "Ports" suggests a substantial infrastructure dedicated to handling various types of cargo and facilitating maritime trade.
A notable presence of "Anchorage" indicates areas where vessels anchor, possibly for short stays or as waiting points before entering busier ports. The presence of "Marinas" highlights areas designed for recreational boating and possibly tourism-related maritime activities. "Canals," although a smaller percentage, may represent critical waterways designed for navigation and transportation purposes.


- <img src="images/Top10_Ports_By_Vessel_Traffic.jpg" width="300">
- **Top 10 Ports By Vvessels In Traffic:**
- In this analysis of the Top 10 Ports By Vessels In Traffic, i came up with the below insights:
- __Shanghai Dominates Vessel Traffic:__ Shanghai emerges as the leading port in terms of vessel traffic, with a substantial count of 2,420 vessels in port. This dominance highlights Shanghai's strategic importance as a major hub for maritime transportation and trade in the region.
- __Significance of Chinese Ports:__ Chinese ports feature prominently in the top 10 list, with Nantong, CJK, Nanjing, Jiangyin, Zhangjiagang, Zhoushan, and Yangzhou all making the cut.
This underscores China's role as a key player in the global shipping industry, with several ports handling significant volumes of vessel traffic.
- __Regional Influence:__ The presence of ports like Singapore and Tianjin in the top 10 list indicates the regional significance of these maritime hubs. Singapore, known for its strategic location and world-class port facilities, serves as a crucial gateway to Asia and beyond. Tianjin, located in northern China, serves as a vital port for trade in the Bohai Bay region and beyond.
- __Implications for Trade and Commerce:__ The high volume of vessel traffic in these ports reflects the intense economic activity and trade flows in their respective regions. Ports with high vessel traffic are likely to have robust infrastructure and logistics capabilities to handle the influx of ships and cargo efficiently. Stakeholders involved in global trade and logistics can use this information to optimize supply chain routes and operations.



- <img src="images/Top10_Ports_By_Vessel_Traffic.jpg" width="300">
- **The Top 10 Countries With The Most Number of Ports:**
- In this analysis of the Top 10 Countries with The Most Number of Ports, the details below gives us insights into this analysis:
- __China Leads in Port Density:__ China emerges as the country with the highest number of ports, boasting a total of 122 ports. This dominance underscores China's vast coastline and its strategic focus on maritime trade and transportation.
- __Variety of Port Facilities in the USA:__ The USA ranks second with 45 ports, reflecting its extensive coastline along the Atlantic, Pacific, and Gulf coasts. The USA's ports cater to diverse needs, including container shipping, bulk cargo, oil terminals, and passenger terminals.
- __European Presence:__ European countries like the Netherlands, Germany, and the United Kingdom feature prominently in the top 10 list. The Netherlands, with 38 ports, is known for its world-class port infrastructure and strategic location in Europe.
- __Global Maritime Hubs:__ Countries like Korea, Australia, Spain, and Russia also make the top 10 list, highlighting their importance as global maritime hubs. These countries serve as critical nodes in international trade routes, facilitating the movement of goods and commodities.
- __Strategic Importance of Ports:__ The presence of a large number of ports in these countries reflects their strategic importance in global maritime logistics. Ports play a crucial role in supporting economic growth, facilitating trade, and connecting countries to international markets.


- <img src="images/Top10_Ports_With_Most_Expected_Arrival_Vessels.jpg" width="300">
- **The Top 10 Ports With The Most Expected Arrival Vessels:**
- My analysis below gives an insight into The Top 10 Ports With The Most Expected Arrival Vessels:
- __Singapore Leads in Expected Arrivals:__ Singapore emerges as the port with the highest number of expected arrival vessels, with a significant count of 1,203 vessels. This underscores Singapore's status as a major global maritime hub and a critical waypoint for vessels traversing key shipping routes.
- __Chinese Ports Dominate the List:__ Chinese ports, including Shanghai, Zhoushan, Ningbo, CJK, Qingdao, and Caofeidian, feature prominently in the top 10 list. This highlights China's growing influence in the global shipping industry and the importance of its ports in facilitating international trade.
- __Strategic Importance of Suez Canal:__ The presence of Suez Canal in the list signifies the canal's pivotal role in connecting the Mediterranean Sea to the Red Sea and facilitating maritime trade between Europe and Asia. The expected arrival of 409 vessels underscores the strategic significance of the canal as a major maritime artery.
- __European Presence in Rotterdam:__ Rotterdam, located in the Netherlands, is the largest port in Europe and serves as a crucial gateway to the continent. With 336 expected arrival vessels, Rotterdam reaffirms its status as a key maritime hub in Europe and a vital node in global trade networks.
- __Asian Ports of Busan:__ Busan, located in South Korea, is a prominent port in East Asia and a vital hub for maritime trade in the region. With 252 expected arrival vessels, Busan's inclusion in the top 10 list highlights its importance as a transshipment hub and gateway to Northeast Asia.
- __Implications for Trade and Logistics:__ The high number of expected arrival vessels in these ports reflects the intense economic activity and trade flows in their respective regions.
Port authorities and logistics operators can use this information to anticipate incoming vessel traffic and plan port operations and resources accordingly.


- <img src="images/Top10_Ports_With_Most_Vessel_Traffic_By_Area_Global.jpg" width="300">
- **The Top 10 Ports With The Most Vessel Traffic By Area Global:**
- In this analysis, i developed insights for The Top 10 Ports With The Most Vessel Traffic By Area Global, the details below:
- __Dominance of Central China:__ Central China emerges as the area with the highest vessel traffic, with a substantial count of 16,790 vessels in port. This indicates the significance of central Chinese ports as major hubs for maritime transportation and trade activities in the region.
- __Variation in Traffic Across Chinese Regions:__ The presence of North China and South China in the top 10 list underscores the importance of these regions in China's maritime industry. North China and South China serve as key economic zones, hosting major ports that handle significant volumes of cargo and container traffic with 11,526, qnd 9,457 vessels in port respectively.
- __UK Coast & Atlantic's Strategic Position:__ The inclusion of UK Coast & Atlantic with 9,017 vessels in port in the top 10 list highlights the strategic importance of ports along the UK coastline and the Atlantic Ocean. These ports serve as gateways to Europe and the North Atlantic, facilitating trade between the UK, Europe, and North America.
- __Indonesia's Maritime Significance:__ Indonesia's presence with 2,946 cessels in port on the list signifies the country's importance as a maritime nation with a vast archipelago and numerous ports scattered across its islands. Indonesian ports play a crucial role in facilitating domestic and regional trade, connecting various islands and serving as transshipment hubs.
- __Mediterranean and Baltic Sea Traffic:__ The West Mediterranean and Baltic Sea regions feature in the top 10 list, reflecting the significant maritime traffic in these key European waterways. Ports in these regions serve as important nodes in Europe's maritime trade networks, connecting the Mediterranean Sea to the Atlantic Ocean and the Baltic Sea to the North Sea.
- __US Coastline Traffic Distribution:__ The US East Coast and US West Coast appear with 2,046 and 1,931 vessels in port respectively in the top 10 list, highlighting the importance of ports along the US coastline. Ports on the US East Coast and West Coast serve as major gateways for transatlantic and transpacific trade, respectively, connecting the US to global markets.
- __Arabian Gulf's Role in Global Trade:__ The Arabian Gulf region with 1,718 vessels in port, represented by ports in countries like UAE, Saudi Arabia, and Qatar, features in the top 10 list, reflecting its significance as a key maritime hub in the Middle East. Ports in the Arabian Gulf serve as vital nodes in global trade routes, connecting Asia, Europe, and Africa.


- <img src="images/Top10_Ports_With_Most_Vessel_Traffic_By_Area_Local.jpg" width="300">
- **The Top 10 Ports With The Most Vessel Traffic By Area Local:**
- My analysis below gives an insight into The Top 10 Ports With The Most Vessel Traffic By Area Local:
- __Dominance of the Yellow Sea:__ The Yellow Sea emerges as the area with the highest vessel traffic, with a substantial count of 4,210 vessels in port. This underscores the Yellow Sea's significance as a major maritime thoroughfare, connecting ports in China, South Korea, and North Korea.
- __US Coastlines in Second and Third Place:__ The US West Coast and US East Coast rank second and third with 1,931 and 1,695 vessels respectively, in terms of vessel traffic within their local areas. These regions are vital maritime gateways for trade between the United States and Asia, Europe, and other regions around the world.
- __Importance of West Coast Canada:__ West Coast Canada, represented by ports in British Columbia, demonstrates significant vessel traffic, ranking fourth on the list qith 841 vessels in port. Ports in this region serve as key hubs for trade between Canada, Asia, and the Pacific Rim countries.
- __Mediterranean and Indian Coasts Presence:__ The West Mediterranean and West Coast India regions with 537 and 505 vessels in port, respectively, also feature in the top 10 list, highlighting their importance in regional maritime trade. These areas serve as crucial nodes in global shipping routes, connecting Europe to the Middle East, Africa, and Asia.
- __West Africa and South America Representation:__ West Africa and West South America regions have notable vessel traffic with 353 and 259 vessels in port, resepectively, indicating the importance of ports in these areas for trade and commerce. Ports in West Africa and South America play key roles in facilitating trade between these regions and other parts of the world.
- __Lower Traffic in West Australia and White Sea:__ West Australia and the White Sea regions have comparatively lower vessel traffic, with 66 and 58 vessels in port, respectively.
While these regions may have fewer ports or lower trade volumes compared to other areas, they still contribute to local and regional economies.


- <img src="images/Top15_Ports_By_Vessels_In_Port_Vessels_Departed_Vessels_Arrived_Trend.jpg" width="400">
- **Top 15 Ports By Vessels In Port, Vessels Departed and Vessels Arrived:**
- In this analysis of the Top 15 Ports By Vessels In Port, Vessels Departed and Vessels Arrived, the details below gives us insights into this analysis:
- __Shanghai Dominates Across Metrics:__ Shanghai emerges as the top port across all metrics, with the highest number of vessels in port, arrivals, and departures which are 2,420, 1,626 and 1,376 vessels resctively. This underscores Shanghai's status as a major global maritime hub and a critical node in international trade routes.
- __Regional Trends in China:__ Chinese ports, including Nantong, CJK, Nanjing, Jiangyin, Zhangjiagang, and Zhoushan, feature prominently in the top 15 list. This highlights China's dominance in the maritime industry, with several ports handling significant volumes of vessel traffic.
- __Singapore's Role as a Global Hub:__ Singapore ranks among the top ports in terms of vessels in port, arrivals, and departures with 1,109, 1,748 and 1,682 vessels respectively, highlighting its importance as a key maritime hub in Southeast Asia. Singapore's strategic location, world-class infrastructure, and efficient port operations contribute to its prominence in global trade and logistics.
- __Variety of Port Functions:__ Ports like Tianjin, Jinzhou Anch, and Hong Kong demonstrate significant vessel traffic, indicating their importance in regional and international trade.
Each port may have distinct functions and specialties, catering to specific types of cargo or serving as transshipment hubs.
- __European Ports in the Mix:__ European ports like Amsterdam feature in the top 15 list with 767 vessels in port, 228 arrivals and 179 departures, reflecting their role in facilitating trade between Europe, Asia, and other regions. European ports leverage their strategic location, efficient logistics networks, and advanced infrastructure to attract vessel traffic and support global trade flows.

- <img src="images/Port_Locations_Across_Continents_%26_Countries.jpg" width="400">
- **Port Locations Across Continents and Countries:**
- The geospatial map displaying port locations, countries, port types, the number of ports and vessels in port offers valuable insights into the "Shipping Ports Around The World Analysis." Here's a detailed analysis:
- __Visual Representation of Global Port Infrastructure:__ The geospatial map provides us with a visual representation of port infrastructure across continents and countries. It offers an intuitive understanding of the spatial distribution of ports, highlighting their clustering in different regions.
- __Identification of Continental and Country-Level Port Distribution:__  The map enables us identify the regions with a high concentration of ports, such as coastal areas and major river deltas.
- __Insights into Port Types and Their Distribution:__ By displaying port types on the map, we are enabled to identify the different types of ports, such as port, canal, marina, and anchorage. Understanding the distribution of port types provides insights into the diverse functions and roles that ports play in facilitating maritime trade and transportation.
- __Quantification of Port Infrastructure:__ In this map, port infrastructure are depicted as the the number of ports within each country or region can viewed. This quantitative data offers insights into the scale of maritime infrastructure and the level of maritime activity across different parts of the world.
- __Assessment of Vessel Activity:__ In addition to port infrastructure, this map displays the number of vessels in port, providing insights into maritime traffic and activity levels.
High concentrations of vessels in certain ports may indicate significant trade volumes, economic activity, and strategic importance.




