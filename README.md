# Credit_Risk_Analysis
## Overview of the Analysis
The purpose of this analysis is to review different supervised learning models to determin the best fit for predict credit risk.  In doing so we can maximize business and minimize risk for the bank.

## Results
### RandomOverSampler 
* Balanced accuracy score of 65% 
* High risk precision of 1% and sensitivity of 61% that gives a f1 score of .02
* Low risk precision of 100& and sensitivity of 70% that gives a f1 score of .82 
![RandomOverSampler](https://user-images.githubusercontent.com/116597421/225197451-52589352-f86d-4ab4-9401-201e662f62bb.png)

### SMOTE
* Balanced accuracy score of 62% 
* High risk precision of 1% and sensitivity of 61% that gives a f1 score of .02
* Low risk precision of 100& and sensitivity of 64% that gives a f1 score of .78 
![SMOTE](https://user-images.githubusercontent.com/116597421/225203179-b5a256a8-93f4-4ace-b8de-bc0db3dcb44d.png)

### ClusterCentroids 
* Balanced accuracy score of 51% 
* High risk precision of 1% and sensitivity of 59% that gives a f1 score of .01
* Low risk precision of 100& and sensitivity of 43% that gives a f1 score of .60
![ClusterCentroids](https://user-images.githubusercontent.com/116597421/225203316-99976956-c5a2-4786-ad38-5b6a16706269.png)
 
### SMOTEEN 
* Balanced accuracy score of 64% 
* High risk precision of 1% and sensitivity of 69% that gives a f1 score of .02
* Low risk precision of 100& and sensitivity of 60% that gives a f1 score of .75 
![SMOTEEN](https://user-images.githubusercontent.com/116597421/225203456-1d3c1dd2-11aa-4a53-a943-d178b313620b.png)

  
### RandomForest 
* Balanced accuracy score of 79% 
* High risk precision of 4% and sensitivity of 67% that gives a f1 score of .07
* Low risk precision of 100& and sensitivity of 91% that gives a f1 score of .95 
![RandomForest](https://user-images.githubusercontent.com/116597421/225203538-14f7d1ce-c5d2-4055-828f-6e4d61961df7.png)

  
### EasyEnsemble
* Balanced accuracy score of 93% 
* High risk precision of 7% and sensitivity of 91% that gives a f1 score of .14
* Low risk precision of 100% and sensitivity of 94% that gives a f1 score of .97 
![EasyEnsemble](https://user-images.githubusercontent.com/116597421/225203623-313998dc-8b02-44d9-a344-4c427970bc71.png)



## Summary
After review of the data of the 6 supervised learning models the EasyEnsemble would be the choice I would recommend for the bank.  Given that there is very little data on high-risk customers the EasyEnsemble model gave a balanced score of 93% and although the precision was only 7% the sensitivity was 91%.  This will allow for us to minimize risk to the bank, even though some low-risk customers will be labeled as high risk most high risk customers will be assigned correctly.

