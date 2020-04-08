# Data Science COVID-19 Project
## Matt Prodani and Svanik Dani
A data science project visualizing and manipulating Johns Hopkins COVID-19 Data.


### Reflections
It becomes clear form the graphs that the spread of COVID-19 follows the pattern of a logistic curve. Furthermore, it is possible to strech out the curve over time and lower the rate at which the virus spread through practice such as social distancing. Death rates vary significantly between countries: possible factors may include populations, average age, health care system, availability of testing, and the implementation of preventative measures. The death rates also vary signifacntly over time, possible factors for this may be, overwhelming of the health care system, lack of health care supplies, and lack of proper testing equipment. In the case of Italy these factors have lead to an upward trend. In the United States we see a sharp drop in the death rate after the implemntation of wide spread testing, leading to a more accurate count of cases and therefore a value closer to the mortality of the disease.

### Biggest Challenge
Perhaps the biggest challenge was getting the time series format given by John Hopkins to get along with Altair and other libraries. A lot of data manipulation was required to get everything working as it should. The separated data will also allow us to perform techniques such as regression to come up with predictions. We will be working on this in the near future. Another issue we saw is that in the beginning we used arrays to create our data structures while towards the end, the use of dictionaries made it easier to manipulate.


### Extras
Added an animation showing the Top 10 Countries in cases overtime through matplotlib in a Bar Chart Race ormat
