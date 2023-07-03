Here is the binary text classifier. It is trained specifically on the subtitles indices (word_indexes) and the caption indices (cap_indexes). 
It has a simple binary output and classifies whether or not a particular item contains comic mischief or not. Upon testing it has an accuracy of ~73%
Given that it is a basic model with a simple output, it may be a good place to start experimenting with Priviledged information.

the training data: training_features_binary_allCaps.json
the testing data: test_features_binary_allCaps.json

training the model: training_classifier_model.ipynb
        To run the training you will need the training data 
testing the model: testing_classifier_model.ipynb
        To run the testing notebook you will need to have the testing data and mymodel directory 

