### exploration of world happiness and covid 19
## AIT 580 Final project
## introduction
Governments around the world responded to the Covid-19 pandemic differently, and so did their people. Living through such trauma, going through isolations, and seeking a return to normality –the mental effect of such a global event is ubiquitous. Now that the pandemic has run its course for almost two years, there is enough data in to try and identify exactly what those effects are and how the human spirit has persevered through such trying times
## datasets 
The analysis aims to cross reference the data from the World Happiness Report, powered by the Gallup World Poll, and the Oxford Covid-19 Government Response Tracker. By pulling data for countries present across these disparate sets of data, we gain new insights into the human experience during the Covid-19 pandemic. 
we have done all the visualizations on by using the datasets we have taken
## Data preprocessing
Data from the World Happiness Reports were pulled from 2018 through 2021, but the primary focus is on the latter two years. The method of collecting data for Healthy Life Expectancy was changed from one year to the next and unfortunately eliminated the possibility of looking at this effect over time. However, many of the variables available in the World Happiness Report were still viable for the uses of this analysis. 

Data from the Oxford Covid-19 Government Response Tracker was pulled for countries with corresponding Happiness Data. The variables are primarily ordinal and indicate the strictness of a government policy from 0 to 4; 0 being no policy, and 4 being the most strict a policy could be.

It’s important to note that the World Happiness data is primarily based off of the population’s perception of their happiness and the individual factors of it.
There are three summary indexes used within this data: 1.) Stringency, a quantitative measure which represents a government’s overall level of action in regards to Covid-19 policies, 2.) Containment and Health, a quantitative measure that sums the government’s actions in regards to stay at home requirements and control of public areas, and 3.) Economic support, a variable that represent the actions taken in regards to supplemental income and debt forgiveness
## visualization
![image](https://user-images.githubusercontent.com/95987544/145698667-bbe46cff-6508-4c1d-9090-bcfd4f20b830.png)
the above visualization is about average of happiness score and years and regions are given in the side 
like australia and new zealand,central and eastren europe.....
![image](https://user-images.githubusercontent.com/95987544/145698704-11a90fe0-0766-4060-9df0-fa0bfd510f88.png)
this visualization is between confirmed and deaths and it is differentraed in regresssion line from 2020 (red)and 2021(blue)
 ![image](https://user-images.githubusercontent.com/95987544/145698813-242e539d-929e-4e33-ade6-b4f03777a9f7.png)
the above visualization is between stringency and happiness score
Stringency" refers to an index of overall measure of government action. 
Charting Stringency vs Happiness we notice no relation in 2020, but a definitively positive relationship in 2021!
![image](https://user-images.githubusercontent.com/95987544/145698912-50dc663c-90d1-4de9-9c18-e449811a368a.png)
Higher Death counts show a correlation with a decrease in happiness. (This is eliminating outliers, to better show the cluster of low deaths, but the pattern remains even with outliers) And the colors show that this relationship is independent of region!
![WhatsApp Image 2021-12-10 at 9 55 01 PM](https://user-images.githubusercontent.com/95987544/145698994-37ba4ac2-ebe1-452f-8810-ee516d48568c.jpeg)
![WhatsApp Image 2021-12-10 at 9 55 01 PM (1)](https://user-images.githubusercontent.com/95987544/145699002-b9e98e78-8914-4984-a756-10c644f8417c.jpeg)
![WhatsApp Image 2021-12-10 at 9 55 01 PM (2)](https://user-images.githubusercontent.com/95987544/145699004-b50ffd32-51c1-41e5-9ac7-371facc1e775.jpeg)
![WhatsApp Image 2021-12-10 at 9 55 01 PM (3)](https://user-images.githubusercontent.com/95987544/145699009-b0d1ec83-e0cc-4b4b-8430-a500261c2cf0.jpeg)
Generosity fell, Social support fell, and perception of corruption increased. All starting in 2020, coinciding with the pandemic
meanwhile, Freedom to make life choices actually increased corresponding with the pandemic
![WhatsApp Image 2021-12-10 at 11 08 20 PM](https://user-images.githubusercontent.com/95987544/145699097-ca73863c-456f-4a04-b6f5-b29d4ccff4a1.jpeg)
visualizaion between rate of death vs gdp
![WhatsApp Image 2021-12-10 at 11 15 38 PM](https://user-images.githubusercontent.com/95987544/145699151-992e6566-f0d9-4659-9501-b2c73a51e22e.jpeg)
We can see a definitive shift in 2021. Containment and Health is a government action index that represents the stringency of the government enforcing public movement, closing public spaces, and enacting stay at home orders. So as the pandemic has progressed into 2021, the countries with governments enacting more containment policies also seem to be the countries where people perceive themselves to have more social support. I read this as potentially the greater isolation may cause people to value their social support, or force people to be there for each more often than before. The increased importance of close friends and family is heightened by the difficulties of the pandemic and of the isolation
![WhatsApp Image 2021-12-11 at 3 11 32 AM](https://user-images.githubusercontent.com/95987544/145699173-ea882cec-8ef3-45ed-b5bb-b92bc2d03c7d.jpeg)
![WhatsApp Image 2021-12-11 at 3 11 32 AM (1)](https://user-images.githubusercontent.com/95987544/145699184-23a1b14f-7f4a-4db1-9b50-cb8895c1977c.jpeg)
![WhatsApp Image 2021-12-11 at 3 21 21 AM](https://user-images.githubusercontent.com/95987544/145699189-f6c59445-c714-4caa-aa2c-32f7942e100e.jpeg)
we see the increase happening along the averages
There is also a positive correlation between higher Economic Support and a greater perception of Freedom to make life choices
## conclusion
Data shows overall happiness increasing from 2019 to 2020 and through to 2021, but despite the overall increases, countries who were more heavily effected by Covid-19, those with higher death rates, saw smaller or even negative changes to their population’s happiness.  Although the rate of deaths decreased over the course of the pandemic, it still affected poorer countries, those with a lower GDP per capita, more than wealthier countries. 

As frustrated as people get cooped up at home, the containment requirements didn’t have an overall great effect on overall happiness, in fact it increased the Social Support people felt toward one another, perhaps placing greater importance on close friends and families; and the enriching policies such as Economic Support and work from home heavily increased the sense of freedom felt by people, increasing their happiness despite difficult times. 

The deaths have caused strain on the happiness of people worldwide, but positive trends in people’s perceptions can be seen in response to government’s willing to take action to contain the virus and support the population.
