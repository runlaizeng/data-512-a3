## What make human happy

### Introduction 
  In this project, I will explore and analysis what make human being happy. I will explore this based on the world happiness report. The world Happiness us a worldwide survey about happiness. They have 5 reports in total, the first one published in 2012, the second published in 2013, the third published in 2015, and the fourth in the 2016 Update. The World Happiness 2017 was released at the United Nations at an event celebrating International Day of Happiness on March 20th,  which ranks 155 countries by their happiness levels.
  
  The report now increasingly uses happiness indicators to get governments, organizations and civil society’s attention and help them to make their policy decisions. The world Happiness Report review the current state of happiness in the world and show about the new science of happiness to explains personal and worldwide variations in happiness. 


### Data will use 
[world-happiness](https://www.kaggle.com/unsdsn/world-happiness/data) the datasets come from [Kaggele](www.kaggele.com). The world happiness contains three dataset. They are 2015.csv, 2016.csv, and 2017.csv. There are 12 varaibles for each data set. The varaible names , description and data type is in the following table. 


| Varaible name  | Description | Data Type |
| --- | --- | --- |
| `Country` | Name of the country | String |
| `Region` | Region the country belongs to | String |
| `Happiness.Rank` | Rank of the country based on the Happiness Score. | Numeric |
| `Happiness.Score` | A metric measured in 2015 by asking the sampled people the question: "How would you rate your happiness on a scale of 0 to 10 where 10 is the happiest" | Numeric |
| `Economy..GDP.per.Capita.` | The extent to which GDP contributes to the calculation of the Happiness Score. | Numeric |
| `Family` | The extent to which Family contributes to the calculation of the Happiness Score | Numeric |
| `Health..Life.Expectancy.` | The extent to which Life expectancy contributed to the calculation of the Happiness Score | Numeric |
| `Freedom` | The extent to which Freedom contributed to the calculation of the Happiness Score | Numeric |
| `Generosity` |The extent to which Generosity contributed to the calculation of the Happiness Score | Numeric |
| `Trust..Government.Corruption.` | Show file differences that **haven't been** staged | Numeric |
| `Dystopia.Residual` | The extent to which Dystopia Residual contributed to the calculation of the Happiness Score. | Numeric|
| `Standard Error` | No desciption provide | Numeric|

### License of Data
1. [CC0 1.0 Universal (CC0 1.0)](https://creativecommons.org/publicdomain/zero/1.0/)
2. terms of using datasets. Access to the dataset is subject to the [Kaggle Terms of Use](https://www.kaggle.com/terms) and [Rules](https://www.kaggle.com/c/expedia-hotel-recommendations/rules) of the competition.


#### Note for Happiness score
The happiness scores and rankings use data from the Gallup World Poll. The scores are based on answers to the main life evaluation question asked in the poll. This question, known as the Cantril ladder, asks respondents to think of a ladder with the best possible life for them being a 10 and the worst possible life being a 0 and to rate their own current lives on that scale. The scores are from nationally representative samples for the years 2013-2016 and use the Gallup weights to make the estimates representative. The columns following the happiness score estimate the extent to which each of six factors – economic production, social support, life expectancy, freedom, absence of corruption, and generosity – contribute to making life evaluations higher in each country than they are in Dystopia, a hypothetical country that has values equal to the world’s lowest national averages for each of the six factors. They have no impact on the total score reported for each country, but they do explain why some countries rank higher than others



### What I will do with data 
1.	I will first have a bar graph to show the distribution of happiness score. I will then know distribution of happiness score, is it left-skew, right-skew or normal distribution
2.	Give a table of top 10 highest score of happiness country and top 10 lowest score of happiness country to see whether bias exist
3.	Make a box plot of happiness score by each region, we can easily compare highest, lowest and median by each region. 
4.	Find the correlation strengths between variables and happiness score and print them out
5.	Plot the variable with maximum correlation to happiness score vs the happiness score to get a visual on how correlated they are
6.	Combine two variables to see whether the correlation become stronger or not
7.	Setting up linear model to predict happiness

### what is my expecation
1.	The 10 highest happiness score countries
2.	The 10 lowest happiness score countries
3.	The distribution of happiness score
4.	I expect to see which variable is most correlated with happiness score and which variable is least correlated with happiness score
5.	I expect to see the plot that show the correlation between variables 
6.	I expect to see is there any combination of variables could make stronger correlation
7.	I expect the linear model could predict happiness core

### Importantce

  As a human centered data scientist, I think it is important to explore the factors could affect happiness index. There most important reason for this exploration is the happiness index can reflect the happiness of the country and higher the happiness is, more happiness the country is. There are couple reasons why happiness is important to human.

  First, happiness means fun, easy and feels good help human to achieve their goal.  This is a crucial reason why happiness is important for human. We all want to live easier and feels good all the time. The fundamental reason why happiness is very import for human beings is that it not only important to our personal goals in life but also can help us to achieve many other wonderful ambitions and goals. And also, being happy we could also change many other life, we could influence the people around us. 

  Second, more happiness means human can live longer and have better health. Many studies shown that happy people live longer. We all know that there is a link between stress and illness, as is the reverse. Positive feeling can change the chemical which make up of our bodies, produce benign chemicals that enhance our immunity system, cell repair, and body building strength. Happiness is the natural enemy of stress. Thus, more happiness can help human live longer and have better health. 

  Third more happiness could reduce the crime and violent rate, and in some extent can stop the war. Recent studies reveal an important reason why happiness is so important to all human beings. As we become happier, we become better people for society. It is because as human become happier they become more compassionate, more creative, more energetic, more emotionally and physically healthy. It is possible that there would have a huge reduction in incidents of violent and crime if we could raise the happiness index.

  Thus, we can see how important happiness for human being. More happiness is not only can help us achieve our personal goals but also can help us build a better world without violence and war. As a human centered data scientist, it is my duty to explore the underline principles that can affect happiness.


