##Question 1
We use the dataset experiment.csv which contains t, the time in seconds and N, the observed population size. 
We looked at the data in two different phases. Firstly, the early growth phase where t is small and the carrying capacity K is much  greater than the initial population size N0 
This model helps us to estimate the intrinsic growth rate r, as the growth should not be limited by approaching the carrying capacity. Using this model, my estimate for r is 0.009902.
Secondly we looked at the carrying capacity phase as the population is approaching its limit, to estimate the carrying capacity, we estimate K as the mean population size during this stable phase, which is 5.903e+10. Finally, we take N0 from our dataset as the population when t=0 - this is 879.

Using the estimated parameters we created the logistic growth model which shows rapid growth in the early phase close to the intrinsic growth rate and then the curve stabillises as the population approaches carrying capacity. This model shows a good fit between theoretical values and the values we observe in the lab.

##Question 2
Using my estimates of N0 and r, I used the code "N0 * exp(r * 4980)" to find that with exponential population growth at time 4980 is 2.290345x10^24. This is orders of magnitude larger than our estimate of 5.903e+10 with the logistic growth curve, because in the logistic growth model the population is limited by our carrying capacity K whereas with exponential growth there is no limt to the increase whatsoever

##Question 3 


![Exponential Vs logistic growth](https://github.com/user-attachments/assets/c35b2f89-3a22-4be3-8600-4de08ccdf3d8)

