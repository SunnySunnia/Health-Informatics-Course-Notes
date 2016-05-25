##Goal:  
Given labeled data (i.e. TMI vs non-TMI), analyze the diffence in the data behaviors, model the trajectories, and assess risk among the groups.  
* What features and how many features to model? ---->`feature selection`  
* use case: given a value(or set of values) at a time point (9-month-old), assess the risk of having the disease.  
* so the model has to be sensitive to **time** of course, secondly will be **segmental change over time** from the past of the same subject (i.e. a certain elevation in the features over 3 months will 'qualifies' the subject to a higher risk?) 
* look for influetial features that help assessing risk (i.e. a boy is more likely to have autism than a girl)  




##Analysis/Modeling approaches:  

###Growth Curve Modeling (GCM)  
-------------------  
**Mechanism:**  
* fitting an unconditional model that estimates the shape of development over time using `mean` and `covariance structure`.  
* pro: if all individuals in the population follow a similar functional form of development.  
* con: if one trajectory shape is not able to "fit all".  

**Algorithm:**  
* 


###Growth Mixture Modeling (GMM)  
-------------------------  
**Mechanism:**  
* finite mixture models  
* approximating unknown distributions  
* pro: if the general population is thought to be composed of distinct sub-populations that are not identifiable based on measured characteristics.  
* con: if you dont know how many sub-populations are there.  

**Algorith:**  
*  

###Group-Based Trajectory Modeling (GBTM)  
--------------------  
**Mechanism:**  
* application of finite mixture  
* assumes the population is composed of a mixture of distinct groups defined by their `developmental trajectory`.  
* 



