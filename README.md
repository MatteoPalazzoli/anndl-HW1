# Artificial Neural Networks and Deep Learning - homework 1
## Convolutional Neural Network for image recognition  
In this homework you are required to classify species of plants (like the ones in the example image below), which are divided into categories according to the species of the plant to which they belong. Being a classification problem, given an image, the goal is to predict the correct class label.
The framework used to solve the homework are those we have seen during the practical lectures (Tensorflow, Keras).  
![Species 1](https://github.com/MatteoPalazzoli/anndl-HW1/blob/main/00012.jpg)
![Species 5](https://github.com/MatteoPalazzoli/anndl-HW1/blob/main/00064.jpg)
### Challenge instructions
The homework is organized as a two-phases competition:
- Phase 1: development phase. We provide you with labeled training data. Your submissions will be evaluated on an hidden test set. The score obtained by your model will be displayed on the leaderboard.  
- Phase 2: final phase. Your submissions will be evaluated on an final hidden test set (different from the one of Phase 1), to compute the final Leaderboard. During this Phase 2 you have the possibility of performing maximum 2 submissions IN TOTAL. Choose the model you think is the best based on the results on Phase 1.  

### Files
- `dataset.zip` is the dataset zip archive. It contains 8 folders, one for each Species. Each folder contains the samples.
- `model.ipynb` is the notebook with all the code

### Results
```
Accuracy    Species1    Species2    Species3    Species4    Species5    Species6    Species7    Species8
Score       F1 Score    F1 Score    F1 Score    F1 Score    F1 Score    F1 Score    F1 Score    F1 Score
---------------------------------------------------------------------------------------------------------
0.8647      0.7351      0.8503      0.9270      0.8575      0.9029      0.9165      0.9448      0.7836  
```
More detailed results with accuracy score plot and confusion matrix are present into the notebook.
