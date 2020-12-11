# Activity-Recognition


For dataset, visit the website https://data.4tu.nl/articles/Channel_state_information_WiFi_traces_for_6_activities/12692816

Main goal is to classify the human activties using multi-class classifiers Random Forest, Linear SVM, Decision Tree and Gaussian Naive Bayes. Also deploy deep learning technique
LSTM to improve the accuracy.

HOW TO USE:
This dataset consists of data gathered over 6 days. The first three days are all different 
participants performing 6 activities (waving, sitting, falling, clapping, jumping and walking).
The other three days consist of two participants repeating 5 activities (waving, sitting, 
falling, clapping and walking). Each activity was captured over 50 trials (each of 5 seconds).
Trials were continuous, in the sense that there are no fixed start and end points to activities.
This was done to create a more variable dataset that captured activities at different start and
end points.
This dataset consists of two folders: "dat" and "mat" (see FOLDER LAYOUT). "dat" is the raw data,
whereas "mat" contains the extracted data (using the Linux CSI tool by D. Halperin). The two
folders are in essense the same and it is recommended to use the "mat" folder (as this no longer
requires data extraction). However, the "dat" folder is added for verification. 
"visualisation_program.m" can be used to preview specific traces. Change the following variables
in the code: folder, day, participant, activity and trial (line 12-16) to view specific CSI traces. 
