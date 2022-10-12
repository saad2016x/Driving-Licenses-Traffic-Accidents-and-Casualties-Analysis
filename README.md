# Traffic Accidents & Casulties in Relation to Driving Licences Issuance

## Executive Summary

After going through the process of cleaning and munging available datasets and normalizing for population, there is a **weak** relation between driving livences issuance and traffic accidents. Correlation between driving livences issuance and injuries casualities is -0.5, this might suggest that traffic jams can play a role in that due to more drivers are on the road.

The follwoing data availability will unleash great insights if available and can be linked with what we have, to answer questions that we have generated after conducting analysis on available datasets. Datasets are accidents meta-data, demographics of dead & injured and 'Saher' system and traffic violations data.


## Introduction

A sound policy reform is best introduced using data to generate decisions that are evidance-based and capitalize on available resources. In this project, we used the follwoing datasets to explore relations between traffic accidents and Casulties with driving licences issuance in Saudi Arabia for the years of 2016-2017, here are the datasets in use:

- [Traffic Accidents and Casualties by Region](./data/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008.csv)
- [Driving Licenses Issued By Administrative Area](./data/saudi-arabia-driving-licenses-issued-in-the-kingdom-2004-2008.csv)
- [Population categorized by Administrative Area 2016-2017](http://www.stats.gov.sa/ar/852)

The objective is to find if there is a relation between traffic accidents and casulties with driving licences issuance, and are there any commonalities between administrative areas in terms of ratios of accidents per issued driving licences.
<br>

<center>Key words: #traffic #accidents  #licences #Saudi #Arabia #casulties #deaths #injuries #2016 #2017<center>

***

## Analysis

After going through the process of cleaning and munging the datasets, we created a combined dataset that you can find at your disposal in the follwoing link:

[Combined dataset](./data/combined_datasets.csv)

And here we show a dictionary to understand what each variable accounts for:

|Feature|Type|Dataset|Description|
|---|---|---|---|
|year|date|Driving_Licences|Year at which number of issued driving licences| 
|administrative_area|object|Driving_Licences|Driving licences origin of issuance| 
|num_issued_driving_licences|int|Driving_Licences|Number of issued driving licences| 
|num_of_accidents|float|Traffic_Accidents|Number of traffic accidents| 
|num_of_casualties_dead|float|Traffic_Accidents|Number of traffic accidents that had death casualties| 
|num_of_casualties_injured|float|Traffic_Accidents|Number of traffic accidents that had injuries casualties| 
|pop_2016|float|Population|2016 population of Saudi Arabia divided by administrative area| 
|pop_2017|float|Population|2017 population of Saudi Arabia divided by administrative area|

<br>

### First Glance

The correlation between the variables we analyzed is shown below:


 <center> <img width="500" src="/output_charts/Correlation of Number of Issued Driving Licences, Accidents, Deaths and Injuries.png"/> </center>

It is clear that there is high correlation between most of the variables. Does this holds true if we normalize using population size? We will discover that.

<br>

<br>

### Results

After normalizing for population, there is a **weak** relation between driving livences issuance and traffic accidents (corr = 0.026). It appears at the begining that the relation is highly correlated (positive), however when calculating the correlation after normalizing it does not hold up. Moreover, after normalizing, *correlation flipped to negative* correlation between driving livences issuance and injuries casualities (corr = -0.510). What we suspect is this might suggest that traffic jams can play a role in that due to more drivers are on the road.

<br>

In the following chart, we can visualize how many driving licences issued per 10k of population aggregated by reigon: 

<center><img width="600" src="/output_charts/Number of Licences Issued per 10k of Population in Saudi Arabia - 2017.png"/><center>

It seems Hail and Riyadh have more driving licences issuance on average per 10k people, while average is 198 licences per 10k people.

<br>

In the following chart, we can see how many accedents happened per 10k of population aggregated by reigon: 

<center><img width="600" src="/output_charts/Number of Accidents per 10k of Population in Saudi Arabia - 2017.png" /><center>

It seems that north east of Saudi Arabia is having more accidents on average per 10k people, while average is 151 accidents per 10k people.

<br>

In the following chart, we can check how many deaths happend per 100k of population aggregated by reigon: 

<center><img width="600" src="/output_charts/Number of Casualties (Deaths) per 100k of Population in Saudi Arabia - 2017.png" /><center>

4 out 6 areas that have more deaths on average are in the northern part of Saudi Arabia, average is 33 deaths per 100k people.

<br>

In the following chart, we can visualize how many injuries happend per 100k of population aggregated by reigon: 

<center><img width="600" src="/output_charts/Number of Casualties (Injuries) per 100k of Population in Saudi Arabia - 2017.png" /><center>

Al-Baha had 235 injuries per 100k of population which is way higher than the average while Riyadh is moderately low in terms of injuries per 100k people, average is 136 injuries per 100k people.

<br>

In the following chart, we can visualize how many traffic accidents per driving licences issued aggregated by reigon: 

<center><img width="600" src="/output_charts/Number of Traffic Accidents per Driving Licences Issuance in Saudi Arabia - 2017.png" /><center>
    
Al-Qaseem had 3 accidents per issuance of driving licences on average, this could be due to that Al-Qaseem is among the lowest area issuing driving licences in 2016-2017. Northern Boarder area is present again as upnormal. 8 out of 13 areas on average, have less than 1 accident per issuance of driving licences.

<br>

***

## Conclusion

There is a weak relation between number of driving licences issued and traffic accidents while correlation is moderatly negative between number of driving licences issued and accidents that had injuries which might suggest that more drivers on the road lead to lower severe accidents, could be transulated by traffic jams.

We can say that the following question can be addressed in further research, using these questions for each one of these areas that show some trends and standout among others:

- Northern Boarder: **Why death rates are the highest?**

- Al-Jouf:          **High casualties in general, why?**

- Al-Baha:          **Why injuries rates are the highest?**

- Hail:             **Are there any reasons for high rates of driving licences issuance?**

- Riyadh:           **Are there any reasons for high rates of driving licences issuance? And why casualties is the lowest among other areas?**


<br>

The follwoing data availability will unleash great insights if available and can be linked with what we have:

1. Accidents meta-data.
2. Demographics of dead and injured.
3. 'Saher' system and traffic violations data.

<br>
