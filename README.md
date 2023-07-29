# A2: U.S. COVID Trends

## Overview
In many ways, we have come to understand the gravity and trends in the COVID-19 pandemic through data. Regardless of media source, people are consuming more epidemiological information than ever, primarily through reported figures, charts, and maps.

This assignment is your opportunity to work directly with the same data used by the [New York Times](https://github.com/nytimes/covid-19-data/). While the analysis is guided through a series of questions, it is your opportunity to use programming skills to ask more detailed questions about the pandemic.

## Getting Started
You should start this assignment by opening up the `analysis.R` script. The script will guide you through an initial analysis of the data.

* **Coding prompts.** Complete the coding prompts in `analysis.R`. You MUST use the `dplyr` package.

* **Reflection prompts.** Throughout `analysis.R`, there are prompts labeled `"Reflection"`. Please write at least 1-3 sentences for each of these prompts below in this `README.md` file. As appropriate, provide evidence, give justification for your opinions, or genuinely reflect on your views. Please strive for concise, clear, and interesting writing.

## Reflection 1
Before actually calculating the total number of COVID cases and deaths, record your guesses for the following questions.

Guess: How many total COVID cases do you think there have been in the U.S.?
- I guess that there might be thirty million total COVID cases in the U.S. as 10% of the total population.

Guess: How many total COVID-related deaths do you think there have been in the U.S.?
- I guess that there have been around a million total COVID-related deaths in the U.S..

Guess: Which state do you think has the highest number of COVID cases, and which state do you think has the lowest?
- I guess that California state might has the highest number of COVID cases, while Washington state has the lowest.

## Reflection 2
Did the number of COVID cases and deaths surprise you? Why or why not? What about the states with the highest and lowest number of cases? How did your guesses line up with the actual results? Answer in at least 1-3 sentences

I was genuinely surprised by the number since I never anticipated it would be that substantial. Before doing this research I believe that most of the states have pretty good epidemic prevention and control measures. The states with the highest and lowest number of cases align with my expectations.

## Reflection 3
Which county has the highest number of cases in the state of Washington, and does it surprise you? Why or why not? (You may need to google this county to learn about it) Answer at least in 1-3 sentences

King County having the highest number of cases in the state of Washington didn't surprise me due to its association with Seattle. Before doing the research, I've expected a county includes city Seattle, which is really famous around the world and has a coastal geographical location, to have the highest number of cases.

## Reflection 4
Why are there so many observations (counties) in the variable `lowest_deaths_in_each_state`? That is, wouldn't you expect the number to be around 50? Why is the number greater than 50? Answer in at least 1-3 sentences

The observations in the variable `lowest_deaths_in_each_state` is greater than the number of counties in U.S. because the dataset contains each county multiple times with different dates while they have the exactly the same death number.

## Reflection 5
What do you think about the number and scale of the inconsistencies in the data? Does the fact that there are inconsistencies mean that people should not use this data? Why or why not? Answer in at least 1-3 sentences

I think there are reasons for the number and size of inconsistencies in the data. For example, there are some incoherent data from the three datasets used in this assignment, possibly because there may be very different methods for estimating and calculating the total number of COVID cases in the scale of county, state or nation. While these inconsistencies can affect data reliability, it doesn't imply that the data should be abandoned entirely. Instead, users should exercise caution, acknowledging potential errors stemming from different calculations or data sources, and take appropriate measures to verify and cross-check the information before making critical decisions based on it.

## Reflection 6
Why were you interested in this particular question? Were you able to answer your question with code? What did you learn? Answer in at least 1-3 sentences

I am curious about the latest COVID information for each county across different locations. I believe this can be addressed using the code, considering the uniqueness of locations. However, I discovered the dataset contains missing values and possible duplicates, leading to errors in my initial code when I filtered by county name instead of locations. Additionally, there are counties with the same name but in different states, underscoring the importance of understanding the dataset thoroughly before proceeding.

## Reflection 7
What, if anything, made you curious about this COVID analysis? What, if anything, surprised you? What might you do the same or differently on your next data wrangling project? Answer in at least 1-3 sentences

This analysis of COVID information got me curious about trends in cases and deaths in different states/counties among the nation. I'd like to know more about what's causing the cases and deaths: whether it's the population, medical conditions, or policies of each state/county. I would like to make more state-to-state comparisons and intra-state county comparisons to go deeper. he next time I do a data collection and data collation project, I will try to find connections between different rows and columns to try to do more analysis for COVID.