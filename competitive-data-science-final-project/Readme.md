Starting since the first week you have been working on the final project: the "1C" competition. Now it's time to wrap up all you have done and submit your predictions and your code.

This is a peer-reviewed project. While we will evaluate the quality of your predictions directly and provide you the score of your solution on the Private LB, we also believe that assessing the other people's code and receiving feedback for your solutions is a great way to learn.

We hope that the most dedicated of you very soon will win a real competition on Kaggle or other sites. Others may be involved in setting up and conducting your own competition on Kaggle Inclass or even on Kaggle's main page or, may be, on other competition platforms. Because of that, we want the submission of your solution to be in the format, required on Kaggle to claim the winning prize. Note, that your solution basically should be provided in two parts: the code and the documentation. Beside that, your code should reproduce your exact final submission file.

The guideline for the documentation: https://www.kaggle.com/wiki/WinningModelDocumentationTemplate
The guideline for the code: https://www.kaggle.com/wiki/ModelSubmissionBestPractices
We want to slightly specify the above guideline for the code to better suit our needs:

You should do parts which require assessing intermediate results in a jupyter notebooks. This parts include EDA, investigation for data leaks, hyperparameter optimization.
You can do model training / prediction either in Jupyter notebook or in python source code files.
Important moments

Follow this guidelines to simplify life for you and for the fellow learner. This is a must.

The solution runs without errors. Specify required libraries and their versions in the first notebook cell or in requirements.txt -- https://pip.readthedocs.io/en/1.1/requirements.html This will save a lot of time for other students, assessing your project.
Serialize the trained model to disk. This enables code to use the trained model to make predictions on the test data without re-training the model (which is typically much more time-intensive).
Step-By-Step Assignment Instructionsless 
This is a peer-reviewed project. Everyone who submits an assignment must review at least three other submissions to ensure everyone receives a grade; however, many learners complete more to help their peers who are still waiting.

Submit your code. It could be done on "My submission" tab. Upload your notebook or archive with code files. Keep it simple and provide an instruction about how to run the code and how to produce submission file. Reviewers should be able to run it smoothly and without errors, so please make your code clear. When you ready to submit your solution, click the "Submit" button.
Give feedback to your peers. You are required to give feedback to at least 3 peers to complete this project. You can begin giving feedback to other students as soon as you submit. Click the tab to get started. Feel free to provide additional reviews beyond the 3 required!
Read feedback from your peers. Your peers will also begin reviewing your project as soon as you submit. You will receive an email notification of each new review. Only you will be able to see the feedback you receive. If you find someone’s review helpful, click the "This review is helpful" button to thank the reviewer.
Browse other projects. You can browse through all of the submitted projects, even if you don't plan to review each one. Click the like button if you think someone did a great job on their project.
Review criterialess 
Before preparing to submit the assignment, pay attention to the following criterions. Try to complete most of them and present results in a form that can be easily assessed.

Clarity

The clear step-by-step instruction on how to produce the final submit file is provided
Code has comments where it is needed and meaningful function names
Feature preprocessing and generation with respect to models

Several simple features are generated
For non-tree-based models preprocessing is used or the absence of it is explained
Feature extraction from text and images

Features from text are extracted
Special preprocessings for text are utilized (TF-IDF, stemming, levenshtening...)
EDA

Several interesting observations about data are discovered and explained
Target distribution is visualized, time trend is assessed
Validation

Type of train/test split is identified and used for validation
Type of public/private split is identified
Data leakages

Data is investigated for data leakages and investigation process is described
Found data leakages are utilized
Metrics optimization

Correct metric is optimized
Advanced Features I: mean encodings

Mean-encoding is applied
Mean-encoding is set up correctly, i.e. KFold or expanding scheme are utilized correctly
Advanced Features II

At least one feature from this topic is introduced
Hyperparameter tuning

Parameters of models are roughly optimal
Ensembles

Ensembling is utilized (linear combination counts)
Validation with ensembling scheme is set up correctly, i.e. KFold or Holdout is utilized
Models from different classes are utilized (at least two from the following: KNN, linear models, RF, GBDT, NN)