# Credit Risk Analysis
## Overview
The purpose of this analysis is to explore various models and resampling techniques to determine an effective way to assess credit worthiness (credit risk).

## Results
Methods that were used and the results are shown below:

### Random Over Sampling
![Screen Shot 2022-07-14 at 12 13 51 PM](https://user-images.githubusercontent.com/93801125/179046226-f4faac43-36fa-4323-b03c-390e34c68beb.png)



Balanced Accuracy Score was = .66
* Precision
  * High Risk = .01
  * Low Risk = 1.0
* Recall
  * High Risk = .70
  * Low Risk = .61


### SMOTE Over Sampling
![Screen Shot 2022-07-14 at 12 15 56 PM](https://user-images.githubusercontent.com/93801125/179046239-b7edde5c-8a13-4195-9443-6805edd70289.png)



* Balanced Accuracy Score was = .66
* Precision
  * High Risk = .01
  * Low Risk = 1.0
* Recall
  * High Risk = .63
  * Low Risk = .69


### Under Sampling
![Screen Shot 2022-07-14 at 12 17 24 PM](https://user-images.githubusercontent.com/93801125/179046262-2b19047e-531e-4b6c-a928-274c142d2e98.png)



* Balanced Accuracy Score was = .54
* Precision
  * High Risk = .01
  * Low Risk = 1.0
* Recall
  * High Risk = .69
  * Low Risk = .40


### Combination Sampling
![Screen Shot 2022-07-14 at 12 36 08 PM](https://user-images.githubusercontent.com/93801125/179047540-94441b93-7a00-4986-a385-c24d0dbb1736.png)




* Balanced Accuracy Score was = .67
* Precision
  * High Risk = .01
  * Low Risk = 1.0
* Recall
  * High Risk = .76
  * Low Risk = .58


### Balanced Random Forest Classifier
![Screen Shot 2022-07-14 at 12 37 31 PM](https://user-images.githubusercontent.com/93801125/179047531-6cc82fd8-b78d-4c2f-89c6-99a8cc3e522d.png)




* Balanced Accuracy Score was = .79
* Precision
  * High Risk = .03
  * Low Risk = 1.0
* Recall
  * High Risk = .7
  * Low Risk = .87


### Easy Ensemble Classifier
![Screen Shot 2022-07-14 at 12 37 52 PM](https://user-images.githubusercontent.com/93801125/179047515-60543886-e5d7-41a4-b66c-2cec22adbfb4.png)




* Balanced Accuracy Score was = .93
* Precision
  * High Risk = .09
  * Low Risk = 1.0
* Recall
  * High Risk = .92
  * Low Risk = .94


## Summary

According to the results that were gathered from the different methodology that was used, the Easy Ensemble Classifier model is the preferred choice.  It had the highest Balanced Accuracy Score at .93, the highest Precision accuracy of 0.09 (high risk) and the hightest Recalls of 0.92 (high risk) and 0.94 (low risk).  The precision was the same at 1 for all methods. When combining all this together, with a marked difference between this and the next highest model (Balanced Random Forest Classifier), Easy Ensemble Classifier is the best choice.
