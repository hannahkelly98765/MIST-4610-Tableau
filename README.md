# CO2 Emissions
# 21479_8 Members
• [Hannah Kelly](https://github.com/hannahkelly98765/MIST-4610-Tableau)

• [Emma Dolson](https://github.com/eld49325/EmmaDolson_MIST4610GroupProject2)

• [Donovan Vanderpool](https://github.com/donovanv2/MIST4610Project2)

• [Shir Kochi](https://github.com/shirkorchi/MIST4610-Project2)

• [Kaden Williams](https://github.com/kadenwilliams1/MIST4610Project2)

# Dataset

This data was pulled from the US Energy Administration and joined together for an easier analysis. It is a collection of major factors that play into C02 emissions, from the Production and Consumption of each type of major energy source for each country to its pollution rating each year. It also includes each countries GDP, Population, Energy intensity per capita (person), and Energy intensity per GDP (per person GDP). All the data spans all the way from the 1980's through 2019.

Feature Descriptions and Data Types:

<img width="649" alt="Screenshot 2023-04-26 at 11 40 50 AM" src="https://user-images.githubusercontent.com/129444082/234628993-fad7fa73-bcd6-466f-9a47-e026f54696ec.png">

# Question 1

People have employed several approaches to curbing CO2 emissions, ranging from policy changes and regulations to technological advancements and behavioral changes. In 2019, Prince Harry and Meghan Markle announced they would limit their family size to two children, citing environmental reasons. This led people to question if family planning is an effective solution to reducing CO2 emissions. Population growth has been linked to increased CO2 emisssions as increased demand for resources, including energy, food, and transportation, which all contribute to greenhouse gas emissions. However, it is important to note that the correlation between population and CO2 emissions is not straightforward, as other factors such as economic development contribute to CO2 emissions. Economic growth is often accompanied by increased energy demand for transportation, manufacturing, construction, and other sectors, resulting in increased CO2 emissions. This prompted us to ask the question:

Is there a stronger correlation between CO2 emissions and GDP or CO2 emissions and population?

# Question 1 Analysis and Results

![234467370-adc7c351-58fd-4da2-9656-9ade049310af](https://user-images.githubusercontent.com/129444082/234468116-189e84c0-bfc7-4af2-acf0-2ce6ffaff57b.png)

For the top two graphs, we examined the top five countries with the highest CO2 emissions overall (China, US, India, Russia, and Japan). In doing so, the data points are more visible and eliminate less significant countries that could possibly skew the data.

Looking at the visualization between Energy Intensity by GDP vs Energy Intensity per capita, we observed both measures following similar trends year to year with the exception of China. After 2013, China's Energy Intensity by GDP decreases while its Energy Intensity per capita continues to increase. Upon further research, we found this was a result of China's energy restructuring to increase production from its statewide power generators and reduce its reliance on coal. With the other countries' Energy Intensity by GDP and Energy Intensity per capita following parallel trends, the graph reaffirms our hypothesis that GDP and population are contributing factors towards CO2 emissions.

The visualization between Population and GDP shows us there may not be a strong correlation between population and GDP themselves. Looking at the United States, it has the highest GDP in the world yet it has a significantly smaller population compared to China and India. From this graph, we can assume these disparaties will lead to a difference in the correlation between CO2 emissions and population and the correlation between CO2 emissions and GDP.

In the bottom two graphs, we ran a linear regression on the correlation between CO2 emissions and population and the correlation between CO2 emissions and GDP. For both population and GDP, the p-values were less than 0.0001 and reaffirmed our hypothesis that they were statistically significant in contributing to CO2 emissions. The R-squared for CO2 emissions and GDP was 0.8693, which was higher than the R-squared between CO2 emissions and population of 0.6276. This answers our question as the CO2 emissions and GDP has a stronger correlation than the correlation between CO2 emissions and population. The implication of our findings suggests economic policies may have a stronger effect on reducing CO2 emissions than population control.

# Question 2
The Paris Climate Agreement is a global treaty that was adopted in 2015 by 196 countries with the goal of limiting global warming to well below 2°C above pre-industrial levels and pursuing efforts to limit it to 1.5°C. The agreement requires each country to set its own targets for reducing greenhouse gas emissions and regularly report on their progress. While many countries have made efforts to reduce their greenhouse gas emissions, some countries' commitments fall short of the global warming goal and other countries have withdrawn from the agreement or not yet ratified it. In 2017, the U.S. was one country that withdrew from the Paris Climate Agreement only to rejoin it in five years later. With the controversy surrounding its' validity, we used our datset to answer the question:

How effective has the Paris Climate Agreement been in reducing CO2 emissions?

# Question 2 Analysis and Results
![234465683-88a8636a-5fde-4411-835d-14cca78895ab](https://user-images.githubusercontent.com/129444082/234468582-8770facf-634a-48ae-b1b6-64731acd1205.png)

# Manipulations
No manipulations or calculations were performed on the data set. For relevance, we filtered our time period to the decade of 2009-2019 to reduce outliers and exclude countries that no longer exist (e.g. USSR, West and East Germany).

# Sources

Chestney, N. (2018, March 22). Global carbon emissions hit record high in 2017. Reuters. Retrieved April 26, 2023, from https://www.reuters.com/article/us-energy-carbon-iea/global-carbon-emissions-hit-record-high-in-2017-idUSKBN1GY0RB

Guo, X., Xiao, B., & Song, L. (2022, July 29). What cause the decline of energy intensity in China's cities? A comprehensive panel-data analysis. ScienceDirect. Retrieved April 26, 2023, from https://www.sciencedirect.com/science/article/pii/S095965261932030X#sec4

Lai, O. (2021, September 17). Every G20 Country Is Failing to Meet Paris Agreement On Climate Change. Earth.Org. Retrieved April 26, 2023, from https://earth.org/every-g20-country-is-failing-to-meet-paris-agreement-on-climate-change/

