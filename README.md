# Bootstrap_Analysis_of_Semmelweis_Handwashing_Data

Through this project , I have **performed boostrap analysis of the Handwashing dataset compiled** by Dr Ignaz Semmelweis , Hungarian physician and scientist , also described as the "saviour of mothers".**The analysis highlights the importance of washing of hands when the whole of the world is facing the CoronaVirus pandemic**.

If you are interested in reading the story of Dr Ignaz , please visit [here](https://github.com/RishabhBansal2409/Bootstrap_Analysis_of_Handwashing_Data/blob/master/Writeup%20on%20%20Dr%20Ignaz%20%20Semmelweis).

**Steps involved in doing the bootstrap analysis** are as follows :-

1.**Importing the required libraries and the dataset**.  

`Observation` : Observed **alarming no of women died** as the result of childbed fever.

2.**Calculating Proportion of deaths out of the number of women giving birth** and added it to our original dataframe.  

`Observation` : At a first glance,**clinic 2 seems to be performing better (lesser proportion of deaths) when compared with clinic 1.**

3.**Visualizing the death proportion for the two clinics** from the year 1841 till 1846 using a line chart.  

`Observation` : We can clearly see from the line charts that the **death rate is much higher at Clinic 1 when compared to Clinic 2.**

4.**Checking the monthly death rate to see the effect of 'Wash your Hands'** decree issued by the doctor.  

`Observation` : Clealy observed the **significant decline in the concerned death proportion rate before and after the decree was issued**.

5.Question before us is **How much did the handwashing reduce the monthly proportion of deaths on average?**  

`Observation`: Handwashing **reduced the proportion of deaths by around 8 percentage points.**

6.**Built Confidence interval to get sense of uncertainty** around how much handwashing reduces mortalities using bootstrap method.  

`Observation` : We can say **with 95% confidence that handwashing reduced the proportion of deaths by between 6.7 and 10 percentage** points.
