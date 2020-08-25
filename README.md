# World-Suicide-Cases

Suicide is an act of taking one’s life or a situation where one either voluntarily or forcefully kills themselves. Usually, many factors influence suicide; however, in this study, we look at the impact of the Gross Domestic Product (GDP) of a country on its suicide rate, while also studying the suicide rate across the different age ranges, sorted by generations. The general overview of the classification is below:

https://miro.medium.com/max/605/1*AEBzoTW5kTwTm0MInuebQg.png
 
Source: https://www.careerplanner.com/Career-Articles/Generations.cfm
NB: the ages contained herein are estimated using the year 2020 as the current year.
The dataset used for this study was gotten from Kaggle (https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016.) and contained the reported cases of suicide across 101 countries and spans between 1985 - 2016 (32 years).
Upon obtaining the data, an additional feature (Continent) was introduced to the data set, to study the continental suicide rate further, considering the impacts of GDP ($ per-capital) and population. This study made use of Microsoft Power BI as its analytics tool, and the results of the analysis are as follows;
1.	The continental breakdown for the number of countries captured in the data set is below;
i.	Europe: 41
ii.	Asia: 21
iii.	North America: 21
iv.	South America: 10
v.	Africa: 4
vi.	Oceania: 4

2.	The number of reported suicide cases over the period captured in this study is 7 million, and the continental breakdown is as follows;
i.	Asia: 3M
ii.	Europe: 2M
iii.	North America: 1M
iv.	South America: 447K
v.	Oceania: 85K
vi.	Africa: 11K

3.	The average continental suicide rate/100k population breakdown is as follows;
i.	Asia: 19.62%
ii.	Europe: 14.27%
iii.	Oceania: 12.97%
iv.	North America: 10.52%
v.	South America: 5.58%
vi.	Africa: 1.25%

4.	The Average continental GDP Per Capital ($) is as follows;
i.	Europe: $23.1K
ii.	Oceania: $20.77K
iii.	Asia: $16.64K
iv.	North America: $11.25K
v.	Africa: $6.82K
vi.	South America: $6.01K

5.	The breakdown of suicide rate by gender and generation is as follows;
https://miro.medium.com/max/586/1*Rd-m2CgtcNOei9rGFSgsgg.png

6.	The top 5 and bottom five countries by suicide rates are;
i.	Lithuania (41.18%), Russian Federation (32.78%), Sri Lanka (30.48%), Belarus (30.34%) and Hungary (29.72%)
ii.	Dominica (0.00%), Saint Kitts and Nevis (0.00%), Oman (0.58%), Jamaica (0.81%) and Maldives (0.91%)

7.	During the study, we observed that there is a negative correlation between Average GDP ($) and Suicide rate (/100k pop), i.e., suicide rate (/100k pop) decreases as average GDP ($) increases and vice versa. Similarly, there is a positive correlation between population and suicide rate, i.e., suicide rate (/100K pop) increases as population increases. We observed that there is a positive correlation between population and average GDP ($), i.e., average GDP ($) increases as population increases.

8.	The highest record of suicides was in the year 1999 (256119;14.42%), while the lowest record was in the year 2016 (15603)

9.	We used the “key influencers” tool to investigate the rise/decline in suicide rate using Average GDP, Total Population and Age Range as explanatory variables, and Country and Generation as an expansion variable. We noted that when the age range is 5 -14, suicide rate (/100K pop) decreases by 21.64%, while as population decrease by 45673223, suicide rate (/100K pop) decreases by 1.85%. When the age range is 75+, the suicide rate increases by 21.06%, hence, we can say that the two age ranges that influence suicide rate as 5 – 14 and 75+, with 75+ accounting for 21% increment in the suicide rate, and 5 -14 accounting for 22% decline in the suicide rate.
For more insights, the dashboard is accessible via https://app.powerbi.com/view?r=eyJrIjoiNDY0MTY5MzUtZDgyOC00YWI3LWEzMGYtYzAzZGVlZWI0ZDJlIiwidCI6IjYxMjFjMDZiLWI1ZGItNDc4Ny04YmU3LTAzZDljMjc0Mjk5NSJ9&embedImagePlaceholder=true 
