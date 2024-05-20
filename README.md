# Computer Vision Task
*LINK TO DATASET*- https://drive.google.com/drive/folders/12ju_7ZeEn0reD4agQt5UmQ9qSHV4C9w6?usp=sharing
*LINK TO COLAB FILE*- https://colab.research.google.com/drive/1nT0N2qGaN4mo2p13b_6cJkuh2OHLKsPc?usp=sharing

--------------------------------------------------------------------------------------------------------
 b) The DataSet was obtained on Kaggle with 89000 images of people in masks.
* I filtered the data and used only 700 images in total for training validating and testing(300+200+200)
* This was done to reduce upload time on drive and runtime of model which also reducing the robustness of the model
* Since the Model uses pre-trained MobieNetV2 model, having a smaller dataset shouldn't pose a problem
* I also additionally added a test sub-folder  to check the accuracy of the model and check overfitting.

--------------------------------------------------------------------------------------------------------
c)APPROACH AND ROADBLOCKS
* I learned the how to deal with such feature detection problems from scrath in the period and decided to use a pre-trained
  model to avoid making a CNN by myself and ust apply my knowledge of ML, another reasoon for implementing it was using a smaller dataset for the problem.
* Using the weights of the pre-trained model I added the required layers of NN on top of it for binary classifiction
  (tookreferences from notebooks on kaggle related to age detection and other problems related to computer vision)
* One of the major roadblock I faced was dealing with such a large amount of data. The original file was 2gb compressed
  zip file which took too much time to upload on google colab, to counter this I filtered the dataset to 700 images only
  with 300 + 200 + 200( train validation and test respectively)
  I was also confused between validation and test data and why we use it to fine tuee the model.
* Another minor roadblock was accessing the zip file on colab in the local directory hence I switched to google drive for the same.
* THE CODE HAD MANY MINOR ERRORS WHICH WAS FIXED BY ONLY LOOKING AT SIMILR EXAMPLES ON KAGGLE
* THE CODE WORKS WITH VARIATION IN MASK COLOR, DESIGN ETC!!!!
------------------------------------------------------------------------------------------------------------
d) HOW TO RUN THE CODE
----------------------
* DOWNLOAD THE DATASET FROM GITHUB OR FROM DRIVE LINK AND SAVE IT ONN YOUR GOOGLE DRIVE AS *dataset* ONLY DONT CHANGE NAMES
* OPEN THE COLAB file FROm ABOVE LINK OR or FROM THIS LINK
* RUN THE CODE CELL BY CELL AND MOUNT YOUR GOOGLE DRIVE ON COLAB HAVING THE dataset file
* IN THE LAST CELL I HAVE PROVIDED MY IMAGE IN A MASK DOWNLOAD IT ON YOUR COMPUTER AND RUN THE CELL AND SELECT THAT IMAGE
  (you can download any random image of a person in mask and select it)
* THE CODE PREDICTS THE GENDER IN MY CASE MALE:P
--------------------------------------------------------------------------------------------------------------
e) MODEL IN ACTION (can be seen in the notebook uploaded here also)
-------------------------------------------------------------------
* MY IMAGE I PROVIDED
* ![image](https://github.com/naman065/SecyRecruitmentPCLUB/assets/146644023/d18fd0ca-13c2-4bb5-8a22-dc4ff9e8292c)
* OUTPUT
* ![image](https://github.com/naman065/SecyRecruitmentPCLUB/assets/146644023/07993d50-0b51-4868-a71e-1b84a1aff829)
* ACCURACY
* ![image](https://github.com/naman065/SecyRecruitmentPCLUB/assets/146644023/42ba8380-ca7a-4290-9b83-c577a23c0a2a)

  ---------------------------------------------------------------------------------------------------------------



