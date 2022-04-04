# Bikesharing Data Visualization Project

## Overview

In this analysis we used comma separated data in Tableau to visualize the viability of a bike-sharing business in NYC. By plotting various metrics against each other we can get a better idea of the demographics and usage statistics behind a bike-sharing business. Each visualization is listed and discussed in greater detail below.

## Results

![august_peak_hours](https://user-images.githubusercontent.com/95315957/161465414-32535870-07ce-40c8-8332-b71ee1201b8a.PNG)

First, we selecteed a high-traffic period in the summer to see what hours our users would generally use bike sharing. From the visual (which depicts the month of August) it is clear that users need bikes the most around 8-9a and 5-6p, which makes sense as these are peak commuter hours. The dependent variable is hours (in military time) and the independent variable is the total number of bikes demanded. 


![trips_weekday_hour](https://user-images.githubusercontent.com/95315957/161466307-dad373f7-ba37-4f76-83b3-ccde79eb6870.PNG)

Our second graphic drives the earlier point home in more detail, as it shows the day of the week on the upper X axis. From this visualization, we can conclude that weekday demand is mostly commuter-driven (with the hours reflecting this, see 6p TR) while weekend demand appears more scenic, as the heavier demand occurs fairly symmetrically in the afternoon. 


![trips_weekday_gender](https://user-images.githubusercontent.com/95315957/161466710-ab842f12-5f28-4745-b3e0-e52f20181690.PNG)

Our third graphic adds a little more detail to number 2, it is essentially the same visual but broken down by gender. Both genders seem to match the trend from visual two, but the marked difference is in the larger number of men who use the service. 


![checkout_times](https://user-images.githubusercontent.com/95315957/161466873-1e250c95-6535-442d-9f10-1e07abd35727.PNG)

The fourth grpahic shows how long users rent bikes, with each column representing another hour of the ride. It is clear that most users do not ride more than an hour away, as the majority of uses are for around twenty minutes. 


![checkout_times_gender](https://user-images.githubusercontent.com/95315957/161467203-7daf9df0-1218-4bdf-be4f-391a1d4b651d.PNG)

Similar to above, this next graphic adds a little more texture to the ride times. Here we see which genders are using bikes for longer, with men siginifcantly over represented. 


![users_gender_weekday](https://user-images.githubusercontent.com/95315957/161467313-93e52eb1-9185-4aff-af19-9be7deb392f0.PNG)

For the second to last graphic we added a new component: user breakdown. In this graphic we breakdown our users into customers or subscribers and further divide the data by gender. We see that subscribers are far more likely to use the service (which makes sense, given they have enough interest to pay monthly), and that many more of the users are men during the work week. 


![top_start_locs](https://user-images.githubusercontent.com/95315957/161467649-23d53795-6dfc-420f-8334-dd59fb8ecfd4.PNG)

Our final graphic shows a map with the most likely spots for departure. The darker the bubble the more users start their trip at that location. While this map would benefit from an analyst with greater background knowledge of the greater NYC area, it seems as though people need bikes more in the denser areas of downtown such as Manhattan, versus the outter boroughs which have much fewer trip starts. 


## Summary

A clear trend running through this data is the discrepancy between our users genders. There are many possible explanations for this, it could be that men (with a greater statistical preponderance for risky behaviour) are more willing to brave the concrete jungles of Manhattan with not but a helmet to protect them. Perhaps a cyclist fatality map could shed some light on this, as we would expect the higher traffic areas such as downtown to have more incidents with cyclists. If the areas where users are more likely to need bikes are also more dangerous for bikes, then we would expect more risk-averse users to be underrepresented. Further, there are realities at play for women who live in a major metropolitan area that are mostly absent for men. Women are far more likely to be the vicitms of crime, and are therefore less likely to opt for a bike commute home in the dark. We could shed further light on this with a map depicting crime statistics and female user departure locations and usage times. While there is little we can do to alter the underlying sociology of NYC, we can at least have a derived explanation for the gender discrepancy. Leaving aside the gender discrepancy, it seems the most traffic on bikes resutls from commuters. Knowing this, we ought to foucus our marketing and infrastructure on commuters.
