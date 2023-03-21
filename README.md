# deep-learning-challenge

For this part of the assignment, you’ll write a report on the performance of the deep learning model you created for Alphabet Soup.

The report should contain the following:

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model?
What variable(s) are the features for your model?
What variable(s) should be removed from the input data because they are neither targets nor features?
Compiling, Training, and Evaluating the Model

Were you able to achieve the target model performance?
What steps did you take in your attempts to increase model performance?
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation


## Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. 
Using machine learning and neural networks, the goal is to use a binary classifier that can predict if an applicant will be a succssessful investment. 

With the use of the charity.csv that contains over 34,000 organizations that have recieved funding, a neural network will be created to find a model that is 75% accurate.

## Resource
The target of this model was

The features used for the model were:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special considerations for application
ASK_AMT—Funding amount requested

Note theses were broken down using get_dummies to get a total of 43 features

## Process
My initial model had nearly twice as many nodes than features. the second and third layers had an even 30 nodes. I did jump between relu and sigmoid layers for my trial. The trial with 100 epochs povided an average of 72 percent overall.

With my second Optimization model, I focused on changing the amount of nodes and the functions within each layer. Although I found some imporvement tinkering with adjusting the nodes to larger-to-smaller pattern adding a hidden layer and relying on relu as the main function, I only saw slight imporvement with 50 epochs while still holding a 73 percent overall. 

I decided
