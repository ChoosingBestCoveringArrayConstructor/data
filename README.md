This repository presents the training and test data used in the paper named as "An Approach for Choosing the Best
Covering Array Constructor to Use". All data (row) in the files are the average of five runs on different configuration space. The attributes are:

k: Number of configuration options   
t: Strength of covering array   
Qnum: Number of constraints   
Qlevel: Change between 0-10. The higher the level, the more the constraints. Qnum is calculated using this feature. This feature is not used in the study since it is directly correlated with Qlevel. 
Qlength: Length of the constraints i.e., number of configuration options in an invalid tuple. 
time: Time to constructor covering array. 
size: Size of constructed covering array. 
