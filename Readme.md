Financal Inclusion Survey Data

The main dataset contains demographic information and what financial services are used by approximately 33,610 individuals across East Africa. This data was extracted from various Finscope surveys ranging from 2016 to 2018, and more information about these surveys can be found here:

FinAccess Kenya 2018
Finscope Rwanda 2016
Finscope Tanzania 2017
Finscope Uganda 2018
The data have been split between training and test sets. The test set contains all information about each individual except for whether the respondent has a bank account or not.

Your goal is to accurately predict the likelihood that an individual has a bank account or not, i.e. Yes = 1, No = 0.

About the data

You are asked to make predictions for each unique id in the test dataset about the likelihood of the person having a bank account. You will train your model on 70% of the data and test your model on the final 30% of the data.

Train.csv is 70% of the data, across the four East African countries (i.e. Kenya, Rwanda, Tanzania, and Uganda)
Test.csv is 30% of the complete dataset across the East African countries.
VariableDefinitions.csv is the full list of variables and their explanations.
SubmissionSubmission.csv is an example of what your submission file should look like. Note that the variable unique_id in the submission file is:
 uniqueid + " x " + country name
The order of the rows does not matter, but the names of the unique_id's must be correct. The column "bank_account" is your prediction of the likelihood of the user having a bank account.

Two or more countries could have the same unique_id, this is why your submission file needs to have uniqueid x country.