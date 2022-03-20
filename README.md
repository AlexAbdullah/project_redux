# US Mass Shootings Analysis

### Group Members: 
Alex Abdullah and Kelly Tran

# Motivation & Summary
<b>Hypothesis:</b> A greater number of mass shootings that occurred in the 20th century were driven by mental health issues than motivated by race.

The questions explored in this analysis were related to the drivers of the shooting as well as the unique attributes of the shooter and victims/fatalities involved. They played a key role in better understanding the key reasons why mass shootings in the US were occurring as well as where they were occurring most.

With the dataset used in the analysis, the questions were answered however could have been explored furthered with an overlay of other datasets about the prominance of mental illness in the US as well as the social and economic status of certain states in the US.

# Questions explored: 
1. Are there any relationships with attributes of the shooter - age, gender, mental health, race?
2. How frequent are mass shootings occurring in the US that are related to mental health vs not related to mental health?
3. Where and when are mass shootings occurring most? 
4. What are the weapons used by individuals with and without a mental illness?
6. Are there more victims involved when it is a mental health related shooting?

## Dataset used: 
----
The dataset was obtained from  [Kaggle.com](Kaggle.com) and [motherjones.com](https://www.motherjones.com/politics/2012/12/mass-shootings-mother-jones-full-data/).

After some data preparation such as dropping columns, renaming columns and removing null variables we have concluded to retaining the following datapoints from the dataset for the years 2000 and above.

<b><u> Note:</b></u>  For additional information on the data clean up and preparation process, refer to the notebook.

---------

### Additional points explored:
* Profiling shooters and victims involved 
* Profiling details of shootings - year, location (city/state), total shootings related to race vs mental illness 
* Total fatalities and total victims as a result of shootings that were mental health related

`Location`: Location where incident took place                              
`City`: City where shooting took place                                  
`State`: State where shooting took place                                 
`Latitude`: Latitude coordinate where shooting occurred                                
`Longitude`: Longitude coordinate where shooting occurred                              
`Total Number of Fatalities`: Number of fatalities as a result of shooting          
`Total Number of Victims`: Number of victims as a result of shooting including fatalities and those injured     
`Description`: Description of the incident                           
`Date`: Date of shooting                                                             
`Number of shooters`: Number of shooters involved                     
`Shooter Age(s)`: Age of shooter                         
`Shooter Sex`: Shooter gender                            
`Shooter Race`: Shooter's race                                              
`Type of Gun - General`: Type of gun used in the shooting                                    
`Total Number of Guns`: Total number of gun used in the shooting                    
`Fate of Shooter`: Shooters fate                         
`Shooter's Cause of Death`: Shooters cause of death              
`School Related`: Whether the shooting was school related                     
`Place Type`: Place type where the shooting took place                             
`Relationship to Incident Location`: Shooters relationship with the incident location                   
`Targeted Victim/s - General`; Type of victims involved           
`Possible Motive - Detailed`: Detailed description of motive              
`Possible Motive - General`: High level motive of shooting             
`History of Mental Illness - Detailed`: Description of shooters mental illness   
`History of Mental Illness - General`: Indication if shooter had a mental illness     

-------
## Data Analysis 
### The Numbers
* California had the highest number of recorded mass shootings
  - As of 2021, the estimated population of California is 39.24 million making it the highest populated city in the US. 
  - This state also has the highest rate of homelessness with an over 150,000 homeless people
  
* The handgun was the most popular weapon used
  Accessible and most affordable of the observed firearms (~$350 USD)
  
* Over 98% of shootings were commited by a male perpetrator
  - This could be part of a whole separate analysis. Males generally tend to exhibit more violent tendencies than women.
  - Approximately 81% of crimes in the US are committed by males.
  
* The average shooter age was ~33 years old
  Shootings were committed by perpetrators anywhere from 15 to 59 years of age.
  
* The most commonly occurring motive for shootings in our analysis was domestic disputes. 
  
* Mental Illness occurred far more frequently as a motive versus Race

### Mental Illness vs Race 
