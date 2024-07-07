# Unlocking-Global-Joy-World-Happiness-Analysis-Prediction
![](https://github.com/KoreJosh/Unlocking-Global-Joy-World-Happiness-Analysis-Prediction/blob/main/worldHappiness.png)


# Introduction
How happy do you think you are in your country in respect to other parts of the World?

Imagine a world where happiness is not just a fleeting emotion but a measurable and trackable phenomenon. The World Happiness Report does exactly that, providing a comprehensive snapshot of happiness across the globe. From the snow-capped peaks of Switzerland to the bustling streets of Burundi, this report delves into what makes people smile, laugh, and feel fulfilled. It's a deep dive into the heart of humanity, revealing surprising insights about the factors that contribute to our collective well-being. Whether it's the freedom to make life choices, trust in government, or the sheer generosity of a nation, the World Happiness Report captures it all, painting a vibrant picture of global happiness from 2015 to 2017. Buckle up as we embark on a journey through the data, uncovering what truly makes the world happy!

# About the Analysis
This analysis was carried out using a time framed data to expressly look into the happiness state of each country in the world and majorly contributed to this and if this same metrics can be explored by other countries and to help in migration and settlement for better standard of living.

# Data Analysis Process
To make sense of a data it has to be well dealt with, as the saying of my Prof.

_"If you torture data enough, it will confess."_
                                         - Prof. Stanley Omeike

                                 
- Data Collection and Cleaning
- Data Exploration
- Sentiment Analysis
- Data Visualization
- World Happiness Prediction
- Communication and Insight

## Data Collection and Cleaning
The Data set was provided by Quantum Analytics a data company that deals in using data to generate insights to improve productivity and create a data driven world.
The data wasn't quite a large data as its based on the countries of the world and as cleaning is 90% of most data analysis process as a cleaned data gives better insights with little to no bias. I explored the data using Microsoft Excel where I found out just few regions was not imputed , no duplicated value and no null values.
Data Exploration
I further explored data using python to check if all our cleaning process was well done and carried out a Regression model on the data to checkmate our analysis which I would later talk on the insights derived.

## Data Visualization
![](https://github.com/KoreJosh/Unlocking-Global-Joy-World-Happiness-Analysis-Prediction/blob/main/world%20Happiness%20Analysis.png)
1. Top and Least Happy Countries:
 - Top Happy Countries: Switzerland, Iceland, Norway, Denmark, and Finland consistently ranked as the happiest countries with scores around 7.5.
 - Least Happy Countries: Burundi, Syria, Togo, Central African Republic, and Benin ranked at the bottom with scores below 3.5.
 
2. Global Distribution:
 - The world map illustrates the average happiness scores by country, with darker green representing higher scores and darker red indicating lower scores. Notably, the happiest regions include Western Europe and North America, while Sub-Saharan Africa and parts of the Middle East show significantly lower scores.
   
4. Happiness by Freedom and Life Expectancy:
 - There is a positive correlation between average happiness scores and both freedom and life expectancy. Countries like Iceland and Switzerland score high on both freedom and life expectancy, contributing to their high happiness scores. Likewise, countries with lower life expectancy and perceived freedom, such as Syria and Burundi, have lower happiness scores.
   
6. Economic Disparities by Region:
 - The box plot of economic disparities highlights significant variation in GDP per capita across different regions. Western Europe and North America exhibit high GDP per capita, correlating with higher happiness scores. In contrast, Sub-Saharan Africa and South Asia show lower GDP per capita and lower happiness scores.
   
8. Generosity:
 - The scatter plot showed a modest correlation between happiness and generosity. Countries like Myanmar and New Zealand exhibit high generosity scores, which positively impact their happiness levels.
   
10. Trust in Government:
 - Trust in government is another crucial factor. The data shows a positive correlation between happiness and trust in government in countries like Rwanda and Switzerland. However, countries with low government trust, such as Syria and Ukraine, tend to have lower happiness scores.

12. Regional Dynamics:
 - The dynamic comparison across different regions emphasizes that Australia and New Zealand, as well as Western Europe, consistently rank high in happiness. Sub-Saharan Africa, despite its rich cultural heritage, struggles with lower happiness scores due to economic and political challenges.

14. Dystopia Residual:
 - This measure represents the gap between a hypothetical dystopian society and the actual scores of countries. Higher dystopia residuals indicate better performance than expected, highlighting countries that exceed in factors contributing to happiness beyond economic and social metrics.

Dive deep into the nuances of global happiness with the interactive dashboard! Interact with the report [here](https://public.tableau.com/app/profile/korede.joshua/viz/MyWorldHappinessData_16812011471270/Dashboard1?publish=yes1.)

## World Happiness Prediction
![](https://github.com/KoreJosh/Unlocking-Global-Joy-World-Happiness-Analysis-Prediction/blob/main/worldHappinessPrediction1.png)

I further explored the data using machine learning model [scikit-Learn] to check for important features in the world happiness data for the time frame and to use this features as predictive parameters.
I used various Regression Models such as Linear Regression, Lasso Regression, Ridge Regression , Decision Tree Regressor, and Random Forest Regressor. Of which the Linear Regression gave the uptmost prediction and best metrics against the rest.
Hence I went further to visualize the feature importance of the linear regression to see the order of feature ranking it took into consideration and if it correlated with our analysis.

![](https://github.com/KoreJosh/Unlocking-Global-Joy-World-Happiness-Analysis-Prediction/blob/main/worldHappinessPrediction.png)

### Communication and Insights
1. Trust (Government Corruption):
Importance: Trust in government highlighting that lower perceptions of corruption significantly contribute to higher happiness scores.
Correlation: This aligns with our earlier observation that countries like Rwanda and Switzerland, which have high trust in government, report higher happiness levels. Conversely, countries with low government trust, such as Syria, show lower happiness scores.

2. Health (Life Expectancy):
Importance: Health is another paramount factor, emphasizing that longer life expectancy is strongly associated with higher happiness.
Correlation: The scatter plot depicting happiness scores by life expectancy reinforces this finding, where countries with higher health metrics, such as Iceland, enjoy greater happiness.

3. Generosity:
Importance: Generosity plays a significant role, underscoring the impact of altruistic behavior on happiness.
Correlation: This mirrors the earlier observation where nations like Myanmar and New Zealand exhibit high generosity and correspondingly high happiness scores.

4. Freedom:
Importance: Freedom emerges as the most critical factor, freedom to make life choices is crucial, indicating that personal autonomy greatly enhances happiness.
Correlation: The positive correlation between happiness and freedom is evident, with countries scoring high on freedom metrics, such as Denmark, also ranking high in happiness.

5. Family:
Importance: The importance of family support systems is highlighted as a key contributor to happiness.
Correlation: Although specific family-related data isn't explicitly shown in the previous visualizations, the overall happiness trends in socially cohesive countries like those in Western Europe reflect this.

6. Economy (GDP per Capita):
Importance: Economic prosperity remains a vital component, showing that higher GDP per capita is associated with greater happiness.
Correlation: The economic disparities box plot and GDP per capita scatter plot confirm this, with wealthier regions such as Western Europe and North America displaying higher happiness scores.

7. Dystopia Residual:
Importance: The dystopia residual, representing how countries perform relative to a hypothetical dystopian baseline, is also a significant factor.
Correlation: This metric helps identify countries that outperform expectations, like Costa Rica, providing a nuanced understanding of happiness beyond traditional indicators.

8. Regional Factors:
Importance: While regional factors like being part of North America or Western Europe have some importance, they are less critical compared to the aforementioned features.
Correlation: This reinforces the idea that while geography and regional characteristics influence happiness, they are secondary to factors like governance, health, and economic conditions.

#### Synthesis with Previous Insights
The feature importance analysis provides a robust quantitative backing to our previous qualitative insights. It confirms that good governance, health, generosity, freedom, and economic prosperity are the linchpins of national happiness. Regions that excel in these areas naturally report higher happiness scores, as seen in Western Europe and North America. In contrast, regions struggling with these factors, such as Sub-Saharan Africa and parts of the Middle East, display lower happiness levels.

## Conclusion
The World Happiness Report underscores the multifaceted nature of happiness. While economic factors such as GDP per capita play a significant role, other aspects like social freedom, life expectancy, and trust in government are equally crucial. The data suggests that policies aimed at improving public health, ensuring political stability, and fostering community trust can significantly enhance national happiness levels.
  Furthermore, the disparities highlighted by the report point to the need for targeted interventions in less happy regions. For instance, increasing life expectancy through better healthcare, enhancing freedom through democratic reforms, and building trust through transparent governance can be effective strategies.
The World Happiness Report shows that trust in government, good health, generosity, freedom, family support, and a strong economy are key to happiness. Regions like Western Europe and North America, which do well in these areas, have the highest happiness scores. On the other hand, places like Sub-Saharan Africa, which struggle with these factors, have lower happiness scores. This highlights the need for balanced improvements in society, economy, and politics to boost happiness worldwide.

_This can further help you in your "Japa" plans and this serves has a road map to government of developing countries on areas to tackle to better the livelihood of their citizens._
