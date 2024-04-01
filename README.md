## Internship's subject : study of the impact of multicolinearity on data overfitting in survival modelling problems

In this project, we observed the effect of multicolinearity on survival analysis. We simulated data from 5 different scenarios by varying the following parameters: statin's effect ($\beta_{statin}$), feature effect, the size of sample, the number of feature and the correlation rate. However, we varying only statin effect here to give more importance for this feature compared to other. 
We set the parameters by : 
 - number of feature : 51 ;
 - sample's size : 5000 ;
 - correlation rate : 0.8 ;
 - feature effect : 0.1

Then, we modify the value of statin effect with 5 values. 

| $\beta_{statin}$ | Target |
|--- |--- |
| 0 | without multicolinearity  |    
| 0.8 |  with high importance of statin's feature |    
| 0.2 |  with low importance of statin's feature  |  
| -0.2 |  with negative low importance of statin's feature  | 
| -0.8 | with negative high importance of statin's feature | 
