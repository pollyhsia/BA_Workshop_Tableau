# Happier, Less Lonely-- https://public.tableau.com/profile/pollyhsia#!/vizhome/Finalversion_Happierlesslonely/Happierlesslonely?publish=yes
## Project Outline and Tableau Summary

### Part 1--Data and Story Description 

This story has used the dataset Young People Survey from Kaggle which explores the preferences, interests, habits, opinions and fears of youngsters. The original survey was presented to the young between 15 and 30 by both electronic and written forms, and 1010 pieces of information were collected. 

The reason why we choose this domain is that we are exactly young people. The questions and answers in the questionnaires resonate with ourselves. Since the dataset reflects every aspect of the young, we can have a panorama of ourselves through visualizing it, regardless of the differences of demographics.
Data source: https://www.kaggle.com/miroslavsabo/young-people-survey

Our story line focuses on two of human important emotions--happiness and loneliness. We want to explore the elements that may affect these two emotions. Hopefully, through this exploration, we can give suggestions and help young people live happier and less lonely. 

### Part 2--Results

For the happiness part, we leveraged the chart function in Tableau and found six factors that affect happiness ”-- “Numbers of friends”, “Interests or hobbies”, “Spending on healthy eating”, “Giving”, “God” and “Entertainment spending”. We further explore the differences of importance of these six elements between gender. According to the results, We suggest that boys to be happier could make more friends, develop more hobbies and spend more money on socializing. On the other hand, we recommend that girls could spend more money on health eating and be generous if they are chasing happiness. 

For the loneliness part, We digged a little into the features of people who have high level of loneliness. In people with different level of education, it seems that primary school pupils regardless of gender are the group that feel lonely the most, while most of people say they are OK. Besides, people live in villages who spend most of the day on internet are very lonely. People who live cities feels better about loneliness. What is more, people who never drink and never smoke are the group that claims to be highly lonely. The level of loneliness varies among people’s background such as age, education and location. From the result of our story, we provide some suggestion for people to deal with the issue of loneliness: to enjoy eating instead of doing it for survival, to make more friends, and to adapt to new environment faster.

### Part 2--Chanllenges and conquest

During the process of exploring the dataset, we encountered many challenges. For instance, the data covers extensive topics in psychology, but it is challengeable to dig into the inner relation behind the potential problem we figure out due to the limitation of data and the limitation of our understanding of psychological theories in this domain.

Besides, the structure of dataset is very flat. We only have the information of degree of level to questions, but all questions do not seem to have a relation. To make the situation better, when we processed the dataset, we combined the values of those columns concerning measurement into a new column to deliver clearer information. For example, we created a new index called “Giving(group)” to measure a person’s degree of willingness to give by combining level one and level two together (naming it as giving less) and by combining level three and level four together(naming it as giving more). By doing this, we are able to see whether the relationships would be more obvious. 
