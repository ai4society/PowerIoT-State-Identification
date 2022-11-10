# PowerIoT-State-Identification
Repository for details about the dataset shared in our paper "A Dataset and Baseline Approach for Identifying Usage States from Non-Intrusive Power Sensing With MiDAS IoT-based Sensors"
1. The _code_ folder contains the python notebook with documentation of the different methods used in our approach.
2. The _doc_ folder contains our publication.
3. The _data_ folder contains \
  a. _location_states.json_: file contains the details about the states identified for each location and the respective centers for each state. \
  b. _State Summary Validation.csv_: Validation details of the identified states for each location.
4. The _leaderboard_ folder contains \
  a. _f1_scores.json_: This file contains the model performance for each test date in all the locations of the released dataset. \
  b. _paper_f1_scores.json_: The f1_score details of the test dates presented in our paper can be found in this file. \
  c. The step-by-step details to reproduce the results presented in our paper can be found here
5. The _metadata_ folder contains the metadata for both power and harmonics datasets
6. The _results_ folder contains the graphs with the identified states using our approach for each location in the release dataset. 


# Obtaining the dataset
Please fill the following Google form to get a link to the dataset - https://forms.gle/cHJdq7a56GuAEd4N6 \
Additional data for more days for the same locations presented in our paper from January-August 2022 can be requested for research purposes by contacting the authors.

# Citations
If you are using this data, please cite.
```
@misc{https://doi.org/10.48550/arxiv.2209.00987, 
  doi = {10.48550/ARXIV.2209.00987},
  url = {https://arxiv.org/abs/2209.00987},
  author = {Muppasani, Bharath and Anand, Cheyyur Jaya and Appajigowda, Chinmayi and Srivastava, Biplav and Johri, Lokesh},
  keywords = {Signal Processing (eess.SP), Artificial Intelligence (cs.AI), Machine Learning (cs.LG), FOS: Electrical engineering, electronic engineering, information engineering, FOS: Computer and information sciences},
  title = {A Dataset and Baseline Approach for Identifying Usage States from Non-Intrusive Power Sensing With MiDAS IoT-based Sensors},
  publisher = {arXiv},
  year = {2022},
  copyright = {Creative Commons Attribution Non Commercial No Derivatives 4.0 International}
}
```
'''
@inproceedings{midas-forecasting,
author = {Bharath C Muppasani and C J Anand and Chinmayi Appajigowda  and Biplav Srivastava  and Lokesh Johri},
title = {Power Forecasting and Anomaly Detection with MIDAS IoT-based Sensor},
year = {2022},
booktitle = {DOI: 10.13140/RG.2.2.17358.33600},
}
'''


# License
Creative Commons Attribution 4.0 International

This is a collaborative work with Tantiv4 and University of South Carolina, Columbia.

[![AIISC-Logo-drawio.png](https://i.postimg.cc/CMWQWrzV/AIISC-Logo-drawio.png)](https://postimg.cc/XXkL58f2)
