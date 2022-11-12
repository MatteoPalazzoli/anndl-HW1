# anndl-HW1
## Convolutional Neural Network for image recognition  
In this homework you are required to classify species of plants (like the ones in the example image below), which are divided into categories according to the species of the plant to which they belong. Being a classification problem, given an image, the goal is to predict the correct class label.
The framework used to solve the homework are those we have seen during the practical lectures (Tensorflow, Keras).  
### Two-Phases Competition
The homework is organized as a two-phases competition:

    - Phase 1: development phase. We provide you with labeled training data. Your submissions will be evaluated on an hidden test set. The score obtained by your model will be displayed on the leaderboard.  
    - Phase 2: final phase. Your submissions will be evaluated on an final hidden test set (different from the one of Phase 1), to compute the final Leaderboard. During this Phase 2 you have the possibility of performing maximum 2 submissions IN TOTAL. Choose the model you think is the best based on the results on Phase 1.  

### Submission Format

You are required to submit your code instead of directly providing the predictions. In order to do so, you must follow the following submission format:

    submission must be a zip file (e.g., submission.zip) containing two files: model.py and metadata. The names of these two files must not be changed. 
    metadata file is just an empty file that is required by CodaLab to mark the submission as a "code" submission. Please add it in the zip file as shown in the starting kit.
    model.py will contain the code you submit for the evaluation. In order to be compatible with the evaluation backend, it must have the structure reported in the example below. The script must contain the definition of the class Model, which must have at least two functions: __init__ and predict. In the __init__ function you are required to create and load the model (or the model components), while in the predict function the model is used for predicting the class corresponding to the input X. Please notice that the given definition of these two functions must be respected, i.e., the argument path in the init function must be always provided, as well as the argument X of the predict function. If one of the argument is missing from the class functions you submit, the overall evaluation procedure will raise an error. 
