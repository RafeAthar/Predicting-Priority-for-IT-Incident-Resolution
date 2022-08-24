# Predicting-Priority-for-IT-Incident-Resolution
Assigning priority to IT incidents for resolution based on previous assigned priorities. 

This task was assigned in the selection process of an AI company. The details provided were as follows:

"The support analyst received an IT incident report and they have to assign resolution priority for this incident but sometimes it is difficult to make this assignment and often it is very subjective.
Resolution priority of IT Incident will drive further reaction and resolution time SLA from operational teams who will be involved as they have to prioritize and queue many incidents for resolution order.
For reference we have 5 priorities for Incidents:
1.	Global Crisis resolution time 4 Hours
2.	Major Incident resolution time 24 hours
3.	Minor application or critical individual user problem — resolution time 72 hours
4.	Non critical user problem — resolution time 5 business days
5.	User request/how to — resolution time 10 business days

We have incidents data (CSV) extracted into 2 files, first file is for training and second file is for testing. These two files contain incident number and all other fields related to incidents including Priority. The number of records is more than 40k.
Using this data, we would like to predict priority class for new upcoming incidents based on data related to this incident. Attach the results of prediction."


'train.csv' contains the features along with assigned priority. 
'test.csv' contains cases to which priority has to be assigned.
'Shaikh_Rafe_Prediciton.ipynb' contains code for EDA and prediction.
'Shaikh_Rafe_Submission.csv' contains predicted/assigned priorities to cases given in test.csv.


