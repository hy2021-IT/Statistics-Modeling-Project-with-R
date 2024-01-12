# Statistics-Modeling-Project-with-R
This project involves application of both Generalized Linear Models with binomial distribution and Linear Mixed-effect Models on Forest Fire dataset and Student Grades dataset respectively.

## Notice
- This repository was created by Hongyi Xia to present on the finalized code work for the sake of clarity and conciseness. Any intermediate working proceduce carried out by Hongyi Xia and his team members can be found at a different private repository.

## Key files to highlight
- Algerian_forest_fires_dataset_UPDATE.csv : The csv file that contains the raw Forest Fire dataset
  
- AlgerianForests.csv : The csv file that contains the wrangled Forest Fire dataset at stage 1

- Wrangled.csv : The csv file that contains the wrangled Forest Fire dataset at last stage prior to modelling

- Bressoux Data AnPsycho.csv : The csv file that contains the Student Grades dataset

- Bressoux Variable code.docx : The word document that provides the descriptions of all variables in the Student Grades dataset

- FinalProjectCombined.Rmd :The rmd file that provides the full report on both Generalized Linear Models with Forest Fire dataset and Linear Mixed-effect Models with Student Grades dataset, including the prelimnary anaylsis & findings, data wrangling, explortary data anaylsis, and modelling. To get a thorough understanding on the projects details, please open this file with R-Studio.

- FinalProjectCombined.html : The html version of FinalProjectCombined.Rmd. To get a thorough understanding on the projects details, please open this file with any kinds of web browser.

## Other secondary files that may carry repetition in the key files.
- BressouxDataAnPsycho.Rmd : The rmd file that provides the the prelimnary anaylsis & findings portion of Linear Mixed-effect Models with Student Grades dataset

- BDA-EDA.Rmd : On top of the prelimnary anaylsis & findings, this rmd file also provides the explortary data anaylsis portion of Linear Mixed-effect Models with Student Grades dataset.

- BDA FINAL.Rmd : On top of the prelimnary anaylsis & findings, this rmd file also provides the modelling portion of Linear Mixed-effect Models with Student Grades dataset.

- BDA final with EDA.Rmd : The rmd file that provides the full report on Linear Mixed-effect Models with Student Grades dataset, including the prelimnary anaylsis & findings, data wrangling, explortary data anaylsis, and modelling.

## Summary of Generalized Linear Models with Forest Fire dataset
- The aim of this project is to fit a generalized linear models with binomial distribution on Forest Fire dataset to find out the best model that predicts instances of new forest fires emerging on a given day

- After finishing data wrangling and explortary data anaylsis, forward selection and drop-in-deviance test were applied to find out the optimum model

- The model is effective at predicting instances of fires given an overall accuracy of 0.8443

- The model is also more effective at distinguishing an instance of a new emerging fire rather than an instance where a new fire has not emerged given a sensitivity of 0.89 and a specificity of 0.77

- Based on the figure below, the AUC of the model is 0.919, which is close to 1 and shows that the model is effective at classifying instances of new emerging fires. The model performs better than random chance.

![image](./docs/ROC.png)
