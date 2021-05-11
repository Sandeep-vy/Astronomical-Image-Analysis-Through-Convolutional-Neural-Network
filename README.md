# CCN
The project is about analyzing and training a model to recognize astronomical images with good accuracy.

I recommend to read this before seeing the commited folders for better understanding.

==>Galaxy_Classifiers folder contains only galaxy classifier models which is only used to classify the galaxies into elliptical, lenticular and spiral galaxies.
Galaxy_Classifier folder has 
1) AlexNet model for classification
2) Custom CNN model for classification.
3) Testing of galaxy classifier model is also present which tests the accuracy of classifier models.

Note: Before seeing Variants_of_created_models please see Z_predictors folder and its files for better understanding.

==>Variants_of_created_models folder contains other architectures of CNN with different hyperparameters(like epochs, batchsize, dropout, learning rate, optimizer, different arrangement of layers) which performs the same task of classification and Redshift predictions.
Variants_of_created_models folder has
1) Custom CNN model for classification -> variant 1 
2) Custom CNN model for Redshift prediction -> variant 1 (see Z_predictors folder before seeing this file)
3) InceptionV3 model for Redshift prediction -> variant 1 (see Z_predictors folder before seeing this file)
4) VGG16 model for Redshift prediction -> variant 1 (see Z_predictors folder before seeing this file)
5) Resnet50 model for Redshift prediction -> variant 1 (see Z_predictors folder before seeing this file)
6) Custom CNN model for Redshift prediction -> variant 2 (see Z_predictors folder before seeing this file)

==>Z_predictors folder contains only Redshift predictor models which is only used to predict the redshift of galaxis
Z_predictors contains
1) Custom CNN model for Z prediction.
2) InceptionV3 model for Z prediction.
3) Resnet50 model for Z prediction.
4) VGG16 model for Z prediction.
5) Xception model for Z prediction.




