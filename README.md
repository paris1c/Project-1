# Impact of COVID-19 across the world

## Team Members: 
### Vasanta Prayaga, Laurane Gerber, Parisa Ch, Victoria Sandoval

## Introduction:
A novel corona virus (COVID 19) was identified in 2019 in Wuhan China. It has spread rapidly worldwide and was officially declared to be a pandemic by the WHO. To better understand the data available about it, we will be doing exploratory data analysis of the available COVID 19 data.  The goal of the project is to study the impact of COVID 19 across the world using Python, Pandas, Plotly express and Matplotlib and present visualizations to show our analysis.

## Dataset:
### Our World In Data - COVID 19 data, Vaccination data and Hospitalization data
We have use Our World in Data Covid dataset for the purpose of this project. Our World in Data is a scientific online publication which focuses on large global problems such as disease, climate change, war, etc. This dataset is consist of 207 countries.

## Project proposal and questions to analyze:
1. Global impact of Covid 19 by Income Groups - Parisa
2. If people with pre-existing conditions are more prone to be hospitalized or die -Laurane 
3. Top 10 Countries by Cases - Victoria
4. Top 10 Counties by Hospitalization/ICU Admissions - Victoria
5. Trend of Covid related total deaths by country  -Vasanta
6. Progress of fully vaccinated people in the world by country - Vasanta

##  Analysis and conclusions
After reviewing COVID-19 data from Our World in Data, several findings were made.

1. A glance at the vaccination plot reveals a clear pattern that, rich countries are vaccinated but poor countries are not! We also notice that Rich countries had access to vaccine lots earlier compared to Poor countries. 

By looking at number of cases Plot, we notice a sharp increase in number of cases in Rich Countries right before the 2022 New Year, which suggests that people were getting infected when they were not practicing social distancing during the Holidays.
On the other hand, when we look at Cases Plot for Poor countries, we notice that those countries don't have many cases. The reason is not that they have lower cases, the reason could be that those countries have limited access to test kits and also their healthcare providers don't have all the necessary resources to record and report the number of cases accurately.

At last, by studying the number of deaths we notice that number of deaths are lower in Rich countries compared to low income countries which is related to not having access to vaccination and having limitation in hospitalization and medication. 

The countries that reported the highest number of cases as of March 31st, 2022 were the United States, India, Brazil, France, Germany, United Kingdom, Russia, Turkey, Italy, and South Korea. 6 out of those 10 countries were also in the top 10 countries with weekly hospital admissions. Initially, Italy, France and the United Kingdom reported the highest rate of weekly hospital admissions, each reporting over 15K weekly hospital admissions within a two-week span beginning March 2020. As these are neighboring countries, the data supports how contagious the virus was early on and how impactful this disease has been on hospitals across the world. Unfortunately, almost one year after the first initial outbreak, these same countries experienced another round of high hospital admissions along with Germany and Spain.  

On trend, France, Spain, Italy, and Germany reported the highest number of ICU admissions over the winter season from 2020 to 2021.  France was one of the first countries to begin tracking ICU admissions and as of recent, ICU admissions to hospitalizations averaged 16% or approximately 1200 weekly ICU admissions to approximately 7200 hospital admissions. Although tempted to take the average of these weekly admissions, the timeline clearly shows the high and low points of the COVID-19 outbreak and how unpredictably contagious it was. 

Unfortunately, not all countries that reported their weekly hospital admissions also reported their weekly ICU admissions. For example, the country with the most covid cases and the highest weekly hospital admission rate on record is the United States; however, ICU admissions were not reported. 

France, Italy, Germany, and South Korea were the part of each of the top 10 categories for total cases, weekly hospital admissions and weekly ICU admissions. 

### Trend of Covid related total deaths by country -Vasanta
- **Description of Analysis**: Covid was declared a pandemic because of the huge number of deaths it caused. To check the trend of covid related deaths in each country, a time series analysis was done using a scatter plot where x-axis is the date, and the y-axis is the highest death count of each country. After cleaning the data, it was grouped by country. This dataset was used to create a dataframe, with columns relevant to date, location, and deaths. It was then sorted, after calculating the highest death count of each country, to find the top 50 countries with highest deaths. Another scatter plot with total death and countries was plotted to visualize the countries with most deaths. Finally using a pie chart a closer view of the top 10 countries with highest death was found.
- **Findings:**
    - 1. From the time series scatter plot, we know that as of Mar10, 2021, United States has the highest number of deaths of 0.991254M. It was followed by Brazil on Sep 14, 2021, with deaths totaling 662.891K, only to be followed by India which reached its peak death count of 522.223K even earlier, on Feb 11, 2020.
    - 2. When we look at the highest death and country scatter plot, we see that United States, Brazil, India, Russia, and Mexico were the top 5 countries to have seen the most deaths.
    - 3. From the pie chart we can see that United States constituted 26.7%, Brazil 17.8% and India 14% of the top 10 countries with highest deaths
### Progress of fully vaccinated people in the world by country – Vasanta
- **Description of Analysis:** One of the ways to combat covid was by building immunity to it through vaccinations. The next analysis is used to observe the progress of fully vaccinated people i.e., those who received at least 2 or 1dose based on the type of vaccination. The previously cleaned dataset was used to create a dataframe with columns relevant to dates, location, and vaccination. A sentiment analysis was performed using line plots and choropleth maps to identify if the progress was positive or negative. A line graph was plotted to show the progress of fully vaccinated people in 10 countries with highest vaccination rates. Another animated choropleth map was created to show the progress of vaccinations throughout the world. 
- **Findings:**
    - 1. From the line plot we can see that almost all the countries were making a positive progress in being fully vaccinated with China being the highest with 1.2 billion being fully vaccinated, followed by India and United States with 846.58 million and 219.26 million respectively as of Apr 20, 2022. Some dips can be observed which are most likely due to missing data in the original dataset.
    - 2. The animated choropleth map shows almost every country starting the administration of vaccination, with a positive progression from Feb 2, 2020, to Apr 04, 2022.

### Reference links:
- Dataset [owid data set](https://github.com/owid/covid-19-data/tree/master/public/data)
- Plotly [https://stackoverflow.com/questions/66789515/plotly-px-animation-frame-error-with-datetime-not-being-accepted]
- Plotly [https://www.analyticsvidhya.com/blog/2021/05/analyze-covid-vaccination-progress-using-python/]
