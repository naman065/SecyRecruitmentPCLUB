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
------------------------------------------------------------------------------------------------------------
d) HOW TO RUN THE CODE
----------------------
* DOWNLOAD THE DATASET FROM GITHUB OR FROM DRIVE LINK AND SAVE IT ONN YOUR GOOGLE DRIVE AS *dataset* ONLY DONT CHANGE NAMES
* OPEN THE COLAB file FROm ABOVE LINK OR or FROM THIS LINK
