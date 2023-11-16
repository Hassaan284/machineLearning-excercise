# machineLearning-excercise
Text Classification/regression – peer reviews

Description of the Excersie:

This task is to implement a ML solution for text classification/regression (long texts). It uses
a dataset of ML paper peer reviews from the International Conference of Learning
Representation (in the years between 2017 and 2020) [1,2].
Specifically, you will use as input a text document concatenating: the title of the paper, the
abstract of the paper, the review comments, the final acceptance/rejection comment. Such
input should be used to predict the following attributes:

• Acceptance status (‘Accept’ or ‘Reject’)
• Review score (Integer number between 1 and 10).

Note that for the latter attribute you can choose whether to use multiclass classification or
regression. You can choose whether to predict both features simultaneously or separately.
Additionally, the dataset is provided with a further attribute, the reviewer confidence score
(an integer number between 1 and 5), which is optional to use. If you want to explore the 
data further, a separate dataset with the text field split into the original fields “review
comments”, “paper title”, “paper abstract” and “final acceptance/rejection comment” can be
provided upon request.

Data set:
exclusions_dataset_task1.csv
