# SecyRecruitment Machine Learning Task

a) Took almost 6 hours searching for the dataset. The sites like pubmed, physionet or NIH had datasets corresponding to only patients with health
conditions and with around 70-80 rows of data. For calculating Tidal volume more generally I refered to this Research Article https://www.researchgate.net/figure/Definition-of-variables-Summary-of-all-calculated-and-estimated-variables_fig1_326076521

It relates the Height of the individual to their Lung Tidal Volume by calculating pbw or Predicted Body Weight(PBW) given as         
**48+0.91*(Height-152.4)in kg**

Which gives Tidal volume as = **6ml/kg * PBW** (FORMULA GENERALLY USED FOR RESEARCH PURPOSE)

Now Any Dataset Having age weight and height can be used for the task, which was found on Kaggle!

--------------------------------------------------------------------------------------------------
b)To approach the problem I created a simple Linear Regression Model with Multiple Variabless/Features

(i) using just the numpy library and mathematics from scratch which yielded accuracy upto \(10^-4\)

To improve accuracy of the model i used **sklearn** which led to accuracy of order *\(10^-27\)*

(ALSO made a model using tensorflow to check if the model was even better or not, ps with help from LLM so not to be considered as a submission)

I used the gradient descent algorithm with mean squared error as my cost function

I also tried to learn and apply Data Augmentation Techniques like adding **Gaussian Noise** or **Shuffling Data** but the improve in accuracy was there
but not significant hence  the code is commented out.

--------------------------------------------------------------------------------------------------------
TO RUN THE CODE
---------------
* Open the JUYPTER Notebook by either clicking on the Collab Link at top in the code file or just copying the whole code in Google Collab
* ![image](https://github.com/naman065/SecyRecruitmentPCLUB/assets/146644023/2f8e4f77-ae98-4879-9a0c-fd4d99f6f246)

* Change the new_data dataframe as per requrement for user input in the model you want to run
* ![image](https://github.com/naman065/SecyRecruitmentPCLUB/assets/146644023/71660cc9-b476-41a6-b186-9d6f76404d82)

* There are 2 codeblocks with 2 models just click run to run the model.
------------------------------------------------------------------------------------------------------------
MODEL IN ACTION
---------------
* MODEL 1
![image](https://github.com/naman065/SecyRecruitmentPCLUB/assets/146644023/185f5ed0-ca64-4e57-9d52-a645bcdcbc46)
* MODEL 2
![image](https://github.com/naman065/SecyRecruitmentPCLUB/assets/146644023/543790ea-98e1-4be9-9707-fc6864956a79)
* A PLOT OF COST FUNCTION DECREASING OVER ITERATIONS
![image](https://github.com/naman065/SecyRecruitmentPCLUB/assets/146644023/ed3ab8af-a93c-4691-b5cc-d3d1aa5dab5d)






