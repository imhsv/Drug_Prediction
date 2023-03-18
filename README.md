# Drug_Prediction
# Introduction
The R&amp;D group has invited some groups of people to test the drug, but going through each person’s health report might take a lot of time and cause a delay in launching the drug in the market.
# Company
 inLab  -  ![inlab](https://user-images.githubusercontent.com/114226899/226100578-347f2720-f3ea-4915-a417-395d4dd8c651.png)
  
  Your client for this project is a pharmaceutical company.

>They have a long history of making effective drugs and are the leading producer of antibiotics for bacterial infection.
>Their research and development team have recently developed five types of drugs to fight against chronic throat infection.
>They want to quickly release the drug in the market so that they could cure people and increase revenue for the company.
>Their R&D team made a brief analysis of the chemical composition present in the drug and made a brief report stating that each drug has a different effect according to their health.
>The drug which has a higher concentration of chemicals should be given to those groups of people whose health report passes some criteria as suggested by the R&D team.

![drug](https://user-images.githubusercontent.com/114226899/226100835-59a8054f-0aa9-4a2a-b6c9-96ad4477c4f1.png)

# Current Scenario
>The R&D group has invited some groups of people to test the drug, but going through each person’s health report might take a lot of time and cause a delay in launching the drug in the market.

# The current process suffers from the following problems:

>Testing phase takes a lot of time and it's done manually because they need to carefully examine each person for the side effects.
>Most of the crucial time is being wasted in checking each person’s health report and dispensing specific drugs according to the health metric as suggested by the R&D team.
>This process is time-consuming and wastage of resources.

# Role
>The dataset containing the health report of the people from the test group.
>Task is to build a multi-class classification model using the dataset.
>Only the need to build the best possible model.

# Data


The dataset contains all the necessary information about the person’s health like their sex, BP, Age, Cholesterol etc.

We have the health metrics of the person which is an essential factor for transcribing the drug to that person without any side effect.

This is the data that we have to predict for future samples.


The dataset is divided into two parts: Train, and Test sets.

Train Set: [Train_Data](https://github.com/imhsv/Drug_Prediction/blob/main/drug_train.csv)
The train set contains 160 rows and 7 columns.
The last column Drug is the target variable.

Test Set: [Test_Data](https://github.com/imhsv/Drug_Prediction/blob/main/drug_test.csv)
The test set contains 40 rows and 6 columns.
The test set doesn’t contain the Drug column.
It needs to be predicted for the test set.

# Analysis and Model Evaluation
>The all works done in notebooks.
>[Data Science](https://github.com/imhsv/Drug_Prediction/blob/main/Untitled.ipynb)

## Software
All the analysis are done by using python 3.6 and others usefull libraries .
