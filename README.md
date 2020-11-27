# Analysis-to-test-for-hypothyroidism

###### Overview 

Nairobi Hospital :hospital: conducted a clinical camp to test for hypothyroidism. The data collected focused on Thyroid patients. 

###### Tasks

1. Build a model that determines whether or not the patient's symptoms indicate that the patient has hypothyroid.
    * Using decision trees
       - For this section, we are to use at least 2 out of the 3 advanced models we have studied: Random forests, Ada boosted trees, and gradient boosted trees.
       - Try and optimize each of the 2 models, making sure to document how you've set up your hyperparameters.
       - Identify which of the 2 models you trust most, and use your model to determine which features are most impactful in influencing the prediction
    * Using SVM:
       - Apply Polynomial, linear and rbf kernel function to build your SVM model 
       - Evaluate their performance and pick the kernel that performs the best. 
       - Tune your parameters to improve the performance of your model. 
       - Visualize the models you've created. Use any two features to build the models for this step.
       - Repeat the prediction using additional features. 
       - Compare the model you've just created with the 2-features version. 
       
The above steps are well executed in the attached colab notebook. The data set can be downloaded from the following link: [http://bit.ly/hypothyroid_data].
Python data science packages used include; Numpy, Pandas, matplotlib, seaborn and sklearn.
