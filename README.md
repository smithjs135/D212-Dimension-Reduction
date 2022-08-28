# D212-Dimension-Reduction
D212 task 2. Dimension reduction of the hospital dataset using PCA

## Libraries

## Research Question
Which variables of the medical dataset can best explain which patients are most likely to be readmitted? Principal component analysis will be used to answer the question? 

The scope of this analysis is to find relationships between the variables that attribute to higher patient readmissions using principal components.  Using principal components allows the ability to answer the question using fewer features. 

## Method Justification
The medical data set contains approximately 50 variables.  Some of the drivers to hospital readmission may not be intuitive to humans and hidden from view. PCA is a feature combination technique (Prabhakaran, 2019).  It provides the ability to summarize large feature components using a few principal components (Yiu, 2019).  I expect to input multiple variables into PCA and receive quantitative measurements of their effect. 

One assumption of this analysis is PCA is sensitive to differences in scale because variances are squared (Yiu, 2019).   Larger numbers will have larger variances.  The medical dataset uses multiple scales, for example: Population, Vit-D-levels. Data based on multiple scales must first be normalized prior to using PCA. 

## Variable Selection
* Initial_days        Continuous
* TotalCharge         Continuous
* VitD_levels         Continuous
* Age                 Continuous
* Income              Continuous
* Additional_Charge   Continuous

## Perform PCA
![image](https://user-images.githubusercontent.com/46407407/187056712-518b596a-cbc8-4780-8348-913bbefb6851.png)

**scree_plot**
![image](https://user-images.githubusercontent.com/46407407/187056791-07a931b6-5c7d-45f4-b9ee-6e461c8a33be.png)

![image](https://user-images.githubusercontent.com/46407407/187056839-bb0005a8-d446-408e-be0b-0839cce01d62.png)
