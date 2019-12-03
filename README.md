# SI618-final-Project
This is the final project for SI618.

## Project Motivation & Dataset

Do you feel happy? Our intuition tells us that people from richer countries might gain more happiness and people from poorer
countries gain less. Is this the fact? In this project, I will do a research on the happiness and people’s life satisfaction in the
world. Using mainly the datasets of annual world happiness report and other supplementary datasets, I’m going to dig out the
distribution of happiness all over the world and factors that inﬂuence the diﬀerence of life satisfaction most.

I will mainly use the data sets from the World Happiness Report. Yiru Wang has all the original data at her Github repository
downloaded from the ofcial website. Since her data is up to the year 2017, I will combine the whole lists with new data sets
for 2018 on the ofcial website. Besides, in my analysis, I will use the dataset showing share of people saying they are happy in
European countries from the Worldindata website. Another data set I will use is the average income data from world bank, I will
use the average income level to categorize the countries and show its relationship to the happiness. I will merge some of the data
sets above based on countries and years to implement my analysis.

## Data Analysis

I intend to perform several data analysis for my datasets based on the following topics:

### Can life satisfaction represent a feeling of happy?

Using European happy survey data, I will merge it into the main happiness data set by countries. To use Europe as an example, I
plan to show the relationship between the life satisfaction and the proportion of ”real happy” people. Te expected result should
indicate a positive linear relationship between them.

### What are the top ten countries that has the highest happiness score each year?

I will group the data set by years and countries and show the top ten countries with highest happiness scores, then use ggplot() to
visualize the results in a bar chart.

### How is the geographical pattern for the happiness in each country year by year?

For this analysis, I would like to show the distribution of happiness for each country visually. Again, ggplot() will be used and I will
also include a world map shown the geographical distribution and maybe heat map to see the diﬀerence in happiness. A sample
visualization has been done by Wang5.

### How is the geographical pattern for the happiness in each region year by year?

Similarly, I will show the distribution of happinessm, but for diﬀerent region/continent in the world, like Asia, Europe, Latin
America, etc. Visualizations will also be ploted.

### What’s the pattern for happiness in diﬀerent levels of average income year by year?

For this task, I will merge the average income level for each country given by world bank into the main dataset. Ten I will show
the patern related the happiness scores and income level using data.table() in R. A mean() operation will be done on countries of
the same income level before.

### What’s the pattern for happiness in countries with diﬀerent levels of health life expectancy?

I will divide the given health life expectancy into several levels and explore the relationship between happiness and each life
expectancy level. Te analysis tool and method will be similar to the above task.

### Which factor aﬀects the life satisfaction most? Include both positive and negative eﬀects?

In this task, I will use R to fnd which is the most contribute factor to inﬂuence the happiness score, which factor promotes the
happiness score most, and which factor leads to a low happiness in that country. Analysis will be performed by using some
regression operations in R.

### What will the life satisfaction be in each region next year?

For this task, I will use regression to perform a prediction task for each region’s happiness in the next year. Since there are not
enough data for countries, I decide to do the regional analysis. I will use the linear regression commands in R and also the prediction
one.
