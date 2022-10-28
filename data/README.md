# Information for States Identified

The current folder contains files which detail about the information of the states identified for each location using the approach we presented in our paper "A Dataset and Baseline Approach for Identifying Usage States from Non-Intrusive Power Sensing With MiDAS IoT-based Sensors"

- _State Summary Validation.csv_
  - The following file contains the number of states found for each location using our approach.
  - The validation information for each location has also been recorded in this file.

- _location_states.json_
  - The following file contains states identified for each location. The centers for each state have also been recorded in this json file.
  - From the 15 days in the released dataset for each location, first 7 days have been used to train the classification model. 
  - The states found using this trained model on the remaining days have been stored in the following JSON files, with the dates as keys and states identified as values.

- _f1_scores.json_
  - The following file contains the f1_score details of the classification model used in our approach for each location.
  - The file contains each date that has been tested with our model as key and the respective f1_score as value.
  
The experiments listed above were current as of October 28, 2022.

  
