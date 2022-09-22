# Neural_Network_Charity_Analysis
Module 19 challenge



## Overview of the analysis:

The goal of this analysis was to help Bek use machine learning via a neural network to determine which applicants would be the most successful if funded by alphabet soup.


## Results: 

* The variable target for this model was the "IS_SUCCESSFUL" variable. This was the main factor in determing the best fit for alphabet soup
* The variables best used for features were the Income and type specific variables they aided in the training of the model
* EIN, Name were irrevelant to the Machine learning process as not much could be learn from strings or objects in this particular case

* For the first hidden layer 82 neurons were put in place and for the second hidden layer 30 were used. the output layer only used 1. This was done with a bit of trial and error to see how accurate I could build the model without using up too much memory
* I was able to achieve close to the target model performence, I feel if I did a few more epochs I could have used less neurons on my hidden layers and achieved my target accuracy
* I mostly focused on epochs to try and optimize performance, but keras was more than enough to help increase my output accuracy

## Summary

  Based on the charts, the overall validity of the model showed off the power of machine learning. Despite this method (even with optimization) being more on the simpler side, we were able to create an effective model to help Bek determine which applicants would be most successful with charity funding. I feel like if other machine learning models were enacted on top of the model that was created we could produce some interesting results. Whether that would be useful to the overall accuracy of the model is left up to testing. Based on my currect understanding of neural networks, this system is a healthy choice for accuracy due to its ease of use. 



