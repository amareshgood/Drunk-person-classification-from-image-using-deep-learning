# Drunk-person-classification-from-image-using-deep-learning
Sober or Drunk Classification Problem

The Sober or drunk classification problem is solved by 2 category with two different feature extraction methods (VGG16, ResNet50 ) and 3 different classification methods(Logistic Regression, MLP classifier, Decision Tree) and results are recorded as below. In this problem, only two outputs are considered that is sober or drunk.
1st category is without Data augmentation, the dataset is loaded and two different features are extracted entire dataset and classified with 3 classifiers. Results shows that the model accuracy is not high. 
Data contains the hand images to recognize the sober, therefore the hand images are removed and again features are extracted and results are recorded. The graph shows that the results are increased by removing the hand images but still the models are overfit, and also Type II error occurs as FP value is increased compared the TP value. Results are shown in the code
Therefore, in 2nd category the data augmentation is performed over the given dataset to avoid the Type II error. Same procedure is followed as in the 1st category with data augmentation. Results shows that the Type II error reduced drastically but the model still overfits. 

