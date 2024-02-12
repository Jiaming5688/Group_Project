# Group Project Proposal
Project Title: The distribution characteristics of  traffic safety events in Los Angeles

Group Name: Anti Road Rage

Group Members: Catherine Ren, Jiaming Zhu, Kailong Ji, Yaofa Gong, Qingyang Xu

Link to Repo: https://github.com/Jiaming5688/Group_Project/tree/main
## Research Question
In our research, we explore the intricate relationship between traffic safety and the demographic and socioeconomic characteristics of communities. We meticulously selected relevant variables, justified their importance, and merged traffic collision data with census tract information. Through the production of descriptive statistics and the creation of side-by-side map plots, our objective is to uncover any visual correlations that may exist. Specifically, we aim to identify whether areas with high traffic collisions share common demographic or socioeconomic features, shedding light on the underlying factors that may influence traffic safety in these communities. To sum up, our research investigates whether there is a correlation between traffic collision rates and the demographic and socioeconomic characteristics of communities.
## Why This Matters
Our group is interested in enhancing public safety. By understanding the root causes of traffic incidents, we aim to develop effective strategies that reduce accidents and improve public safety. The findings of our research will assist city planners and policymakers in creating targeted interventions or legislation, resulting in more effective traffic safety policies. Additionally, these conclusions can facilitate the more efficient and cost-effective allocation of resources for other initiatives like road repair. We plan to identify specific groups of people or geographical areas that could benefit from increased road safety awareness and education. Policies aimed at reducing traffic incidents can also support environmental goals. For example, by promoting non-motorized or public transport, these policies can help reduce emissions, considering their environmental impact. Equally important is recognizing the correlations between traffic incidents and factors such as poverty and education, which can highlight disparities and lead to more equitable policy responses. Overall, this research aims to create more egalitarian, safer, and productive urban environments, significantly impacting the quality of life, the economy, and public health.
## Spatial Scope
Los Angeles is known for its heavy traffic, making it an ideal area for studying traffic incidents. The city's distinctive traffic patterns provide a comprehensive framework for understanding the dynamics of traffic events. The population of Los Angeles is diverse in terms of age groups, educational attainment, and income levels. Analyzing the relationship between these demographics and traffic events can offer targeted tactics to enhance road safety in specific localities. Other cities with comparable urban structures and demographics can use the study's conclusions as a model. Solutions that work well in Los Angeles can be adapted or modified for use in other metropolitan settings.
## Data Source
**Data Source 1:** This dataset named Major Safety Events, is from the U.S. Department of Transportation. It contains the details of major safety and security public transit events from 2014 to 2023. Because our spatial scope is in Los Angeles, we will only use the date under the agency named “Los Angeles County Metropolitan Transportation Authority”. It has five types of public transit mode: bus, rapid bus, light rail, heavy rail, and vanpool. We can plot and compare the number of safety events happening for each mode type in each year. This dataset also contains event type, event time, and the description of each event. Furthermore, it also has the geometry information, including latitude and longitude, for each safety event. We can use the geographic information to display every safety event on the map, and based on the map to  analyze their distribution characteristics. 

Link: https://data.transportation.gov/Public-Transit/Major-Safety-Events/9ivb-8ae9/about_data 

**Data Source 2:** This dataset named Los Angeles Traffic Collisions, is from the LA City website. This dataset contains the time, location and description of private vehicle collisions in Los Angeles. 

Link: https://data.lacity.org/Public-Safety/West-Los-Angeles-Traffic-Collisions-By-Year/n4ru-wwzt

**Data Source 3/4/5/6/7:** These are all Census Data from Social Explorer, including education level, vehicle ownership, household income, population, and avaliable vehicles.

Link: https://www.socialexplorer.com/

**Data Source 8:** This dataset named LA Times Neighborhood Boundaries from LA Times.

Link: https://geohub.lacity.org/datasets/lahub::la-times-neighborhood-boundaries/about
## Intended Analysis and Resulting Visualizations
In this research project, our primary goal is to explore the distribution patterns of traffic accidents in the Los Angeles area and analyze the relationship between the distribution of these accidents and the demographic characteristics of the area (e.g., population density, age distribution, gender distribution, etc.). Using census data and traffic accident records in Los Angeles, we plan to reveal the interactions and effects between accident frequency and demographic characteristics through data analysis and visualization.

During the research, we will use a data integration approach, combining census data with traffic accident data to create interactive maps through statistical analysis and geographic information system (GIS) techniques (we will use some Python libraries, like folium, to accomplish this process). This process includes data cleaning, integration, and analysis with the ultimate goal of presenting complex data intuitively and user-friendly.

Analyzing data from this project will allow us to identify areas with higher densities of traffic accidents and the demographic characteristics of these areas. This will help us understand whether particular demographic groups are more likely to be involved in traffic accidents and whether the geographic distribution of accidents is associated with certain specific demographic characteristics. To this end, we plan to create a clear, intuitive map that shows the distribution of traffic accidents and highlights areas with various types of population densities.
## Conclusion and Expectation
Regarding our expectations, the study will reveal the high accident rate pattern of specific population groups and areas, providing a basis for formulating targeted traffic safety measures and accident prevention strategies. For example, if drivers of certain age groups are more prone to accidents in specific areas, we can propose education and training programs accordingly. Moreover, the study's results will help identify those critical areas where improvements to the transportation infrastructure are needed. For example, if accident rates are unusually high in specific densely populated areas, this may indicate the need for more traffic signs, improved road conditions, or redesigned traffic flow. Most importantly, this study will provide an empirical basis for policymakers to develop more effective traffic regulations and public safety policies. At the same time, community outreach will increase public awareness of traffic safety, especially among residents in high-risk areas.
## Future Plans
To enhance our research, we are considering implementing the following aspects:

1. Thorough Variable Selection and Justification

We will carefully review the recommended papers to identify variables that have been important in similar studies, aiding in justifying their relevance to our research. Additionally, we aim to integrate traffic and demographic data, ensuring accurate combination of traffic collision data with census tract information. This is crucial for assessing the correlation between traffic safety and community demographics/socioeconomic characteristics.

2. Incorporate Visual and Alternative Data for Storytelling
   
We plan to integrate visual data from Google Maps Street View or photographs taken personally in the neighborhoods of interest. This method will vividly illustrate the built environment's impact on traffic safety and community well-being. Furthermore, we intend to compare neighborhoods by focusing on those with high and low collision rates, extending the comparative analysis beyond statistics to include demographic, socioeconomic, and environmental factors, thus providing a comprehensive view of the factors influencing traffic safety.

3. Conduct a Comparative Analysis

We will select two communities for a detailed comparison or focus intensively on one neighborhood with significant traffic safety issues. This targeted approach will allow for a deeper understanding of the unique factors in different settings. Using data and visual evidence, we will tell a compelling story about each community, highlighting how differences in demographics, socioeconomics, and the built environment contribute to traffic safety outcomes.


