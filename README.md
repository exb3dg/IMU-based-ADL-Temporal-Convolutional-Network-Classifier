# IMU-based ADL Temporal Convolutional Network Classifier
This study proposes a subject-adaptive causal temporal convolutional network (TCN) for IMU-based upper-limb ADL recognition using the U-Limb SoftPro dataset. A baseline causal TCN was used to identify deployment-relevant input settings through window, signal-channel, and anatomical-segment ablations. 

There's 9 .ipynb files, a majority of the code across the files is the same. As the ablation and adaptation tests were conducted the code changed slightly to run the different test and then use the best settings. An effort was made to check markdown descriptions of the code. However, markdowns might not be completely accurate due to the usage of older code in new tests (could be remaining from previous test).

Files include:

  a) 1 file for the window and step size evaluation 

  b) 2 files for the channel evaluation; LOO and 6 channel combination 

  c) 2 files for the body segment evaluation; arm combination and arm + torso combination 

  d) 1 file for the classifier scaling evaluation 

  e) 1 file for the classifier head adaptation 

  f) 1 file for the batch norm adaptiation 

  g) 1 file for the combined batch norm and classifier head adaptation 

You will need to download IMU data captured by the University of Zurich from the U-Limb dataset on Hardvard Dataverse: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/FU3QZ9
