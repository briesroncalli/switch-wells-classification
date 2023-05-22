# switch-wells-classification

## Project
This project follows an analysis of a public health study performed in rural Bangladesh (Gelman et al. 2004). In this study, wells used for drinking water were analyzed for arsenic contamination and correspondingly labeled as safe or unsafe. The study determined whether households switched the well used for drinking water and measured. Additionally, several variables where measured that were thought to possibly influence the decision of whether or not to switch wells. Here, we will investigate how accurately we can predict whether or not a household will switch wells based on these environmental variables.

## Data Collection
See Gelman et al. (2004) for a discussion of data collection. Briefly, arsenic levels were measured in Araihazar, Bangladesh during the years 1999 - 2000. Additional information was collected by a survey: 
1. Whether or not the household swithed wells. 
2. The distance (in meters) to the closest known safe well.
3. Whether any members of the household are involved in community organizations.
4. The highest education level in the household.

## Files
#### Water-Quality-Project.Rmd: 
Main body of data analysis, containing data preprocessing, EDA, and all of the modeling other than the random forest, SVM, and NN. Also contains discussion and analysis of modeling. 

#### BenRR_WaterQuality.html: 
Knitted file RMarkdown file. 

#### WaterQuality_NN.ipynb:
Python jupyter notebook using sklearn library to do random forest decision tree, support vector machine, and neural network models.
