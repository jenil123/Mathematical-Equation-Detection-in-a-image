# Mathematical-Equation-Detection-in-a-image
This project is my internship project.
The dataset used for this task is CROHME dataset.
I have modified this dataset in order for my model to predict some important and more frequently occuring charaters with more accuracy.
If you want my updated dataset open an issue.
I have tried almost all possible equations but the thing that i noticed was that the model was performing best on equations like polynomial. 
The model was not predicting well on trignometric equations and equations containing characters like lim, log.
So I removed them so that my model works better.
Steps that I used for this model are as follows:
1. Defined a model for training
2. Trained the model on individual characters
3. Used character segmentaion for segmenting individual characters present in the image
4. Sorted the characters detected in the image by their X coordinates of detected contours.
5. Performed character detection on this segmented images.
6. Using some logic i generated a meaningfull equation.

Link to Character Segmentation: https://github.com/dishank-b/Character_Segmentation/blob/master/main.py
I have changed this code according to my requirements.
For splitting the dataset into train, test , validation i used this script: https://github.com/jfilter/split-folders/blob/master/splitfolders/split.py

Hope you like this:)
Improvements are welcome
