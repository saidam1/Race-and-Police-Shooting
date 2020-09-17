# Race and Police Shootings
by Saida Muktar

### Overview
 * Police shootings is something that we all see in the news very regularly now.
 * The question here is, what does that have to do with race and is it really true that Black people are stigmatized and profiled leading to more deaths?

### Abstract
   * Whenever we talk about Police brutality, it comes with a lot of arguments from different sides. Police brutality occurs among all races, however, the oppression that Black people have to face is way more than others. This reoprt shine light on a couple reasons why Black people are being systemically, disproportinally killed by Police officers. There might be a lot of rebutl to this claim as it is shown that it is acutally more White people that get killed in the hands of officers, but I still stand ground on the hypothesis that Black people are being disproportinally killed by Police Officers. The data being used is from [The Washington Post] (https://www.washingtonpost.com/graphics/investigations/police-shootings-database/) which includes police shooting information from January 2015 until June 2020 across the US.  ![image](https://user-images.githubusercontent.com/70491460/93474416-4fd7a600-f8c5-11ea-83be-575f4160085c.png) 
  
  * We used specific columns from the data given in order to check the assupmtion that Black people are being disproportionally killed by Police Officers. The libraries that were mostly used to do this pandas, and matplot.pyplot from Python 3.0 via Anaconda. 

### Data Analysis
 * The data was read into python through the pd.read_csv function. Some important information from the data that we were used were the date, armed, race, and age columns. 
 
 #### Preview of Data
 ![image.png](attachment:image.png)
 
 
	

 * The data shown above had to be manipulated so that we could have just year as a part of the data, and thus it was added through putting data into a DataFrame and using pd.DatetimeIndex. Once that was done the first thing that needed to be done is to show the increase of Police Shooting from 2015 to 2019. The reason that we did not go all the way to 2020 was because we did not have the data for all the months yet. The process of making the graph for this task was basically calling every year and also precising it to all shootings that happened that year, the total number of shootings that occured that year within Whites, Blacks, or other races.
 ![image.png](attachment:image.png)

 * The next step of analyzing this data was checking the number of people the police killed in each race from 2015-2020. 
 ![image.png](attachment:image.png)
    * The result shown here is that the majority of deaths that occured due to Police Shootings happened the those in the White race. You might think our hypothesis is wrong at this point, but let's keep going.

 * It is known that the majority race population in the US is White, thus we should put that in mind before concluding that there are more White people killed and thus Black people are not the ones being disproportionally killed. Having that in mind, the next process of what was done is that we took in acoount the population of White people in the US and also the population of Black people in the US. At this point, we disregarded the other races, since we are mainly just conserned about the White and Black population. Once we obtained the total populations from Google, we were able to check the number of White and Black people that were being killed by police officers.
![image.png](attachment:image.png)
      * The results shown are that 12.96 White people per million are killed, while 32.10 Black people per million are killed. This shows us that Black People are most likely to get killed more than White people at a rate of 2.47% more.
    

 * What about all these news we hear about police brutality? In a lot of fatal cases we see on the news it is shown to us that the victim did not have a weapon. The data that we are using had a column that told us whether the person was armed or not. Using that data we decided to compare which race is more likely to be killed unarmed. The reason we are doing this is even though we have proved that Black people are more likely to get killed than White people in the hands of the police, this study would like to show the severity in how badly Black people are discriminated against. Saying that, we found the percent of White and Black people who were unarmed from the total number of the ones that were killed. Once we had the percentage of both, we used them to graph our results for comparison.
 ![image.png](attachment:image.png)
     * The results show that out of the 2555 White people killed only 5.75% (147 people) were killed unarmed. Comparing to the 125 out of 1329 giving a 9.4% of Black people who were killed unarmed. This again is another evidence that shows, the harshness of Police officers towards Black people.

* The final comparison we did was check the age group of those killed in both White and Black races. We chose an age of 20, and used it to check how many people were killed at the age of 20 or younger. Age is another key determining factor, as these are cops killing young adults and kids, instead of showing lineancy to them. A lot of people do not even see young Black kids as kids anymore, but see them as dangerous, which is why this data is being compared. We were looking for the percentage of people who were 20 or younger that were killed from the total amount of deaths. 
![image.png](attachment:image.png)
    * This gave us a result that there was only 4.38% of White people who were killed that were 20 years or younger, compared to 11.6% of Black people who were killed that were 20 years or younger. Showing, how even Black youth are being disproportionally killed.

### Conclusion
 * The hypothesis that was stated at the beginning of the report holds true. Even though there are more White people that are killed by Police officers, looking at per population shows us that Black people are being disproportionally killed. Out of the amount of unarmed, and young people that killed by Police officers are higher in Blacks than Whites.


```python

```
