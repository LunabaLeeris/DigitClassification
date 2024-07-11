# DigitClassification
A Machine Learning Model implemented using Soft Max Regression that predicts the digit

Data set was taken from kaggle  
[https://www.kaggle.com/datasets/khushikhushikhushi/dog-breed-image-dataset](https://www.kaggle.com/datasets/karnikakapoor/digits)

There are a total of 10 (0 - 9) classifications with a total data of 10,000

# SUMMARY OF RESULTS
-Given the configurations on the main.ipynb (a = .0000027, f = 100000)
it took atleast 10,0000 iterations to achieve a 99% accuracy on the given dataset

-Training took 1 hour at most on my thinkpad laptop collectively

-The model is bad at classifying handwritten data, this may be due to the data set being 
 too computer-like

# SUGGESTIONS FOR IMPROVEMENT
-Some of the calculations are redundant such as getting the transpose
 also some of the implementation for the code, such as the helper functions for transforming the 
 image, is not thoroughly analysed for it's not the focus of the experiment. These areas may have
 potential optimisations for faster training.

-I learned it later that dividing the parameters and theta by a factor affects the relative distance between
the predictions accross all classifications. This is also called the Temperature of the model. An image classification
should have low to none temperature. This is a key area that will be addressed once I touch this project again

# LEARNINGS
-Computers don't like large numbers!

# DEPENDENCIES
1. tensorflow
2. pillow
3. numpy

# HOW TO USE
-Adjust the configurations accordingly

-Use train_softmax_regression() to train for parameters

-Use display_predictions() to display predictions of images on the directory of your liking
