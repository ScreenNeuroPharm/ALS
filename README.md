# ALS


> The repository contains the data and the functions needed to reproduce the analysis reported in the article "Developmental circuit instability in ALS: from transient hyperexcitability to network collapse".

## Details
All uploaded scripts work with either a .mat format. 
To reproduce our analysis is necessary to convert the ```.txt``` format file in ```.mat``` format file using the function ```TxT2Mat.m``` in the folder Utility. 
All electrophysiological recordings are sampled at 10 KHz. 
```TxT2Mat.m``` function allows obtaining for each electrode (60 or 120) the peak train .mat file. 
Peak_train file is a sparse vector that reports the spike occurring, saving the spike amplitude.

### Code folder architecture:
- NB_detection folder:
    * burstFeaturesAnalysis: functions to detect the network bursts and obtain the network burts feautures

- Computational_model folder:
    

- Machine_learning_model folder: 


- Utilities folder:
    * Txt2Mat: function to convert ```.txt``` format file in ```.mat``` format file

### Data folder architecture:
- Astrocyte folder:

- Electrophysiological_Data folder:
    * Chemical_stimulation subfolder:
    * Electrical_stimulation:
    * Spontaneous_activity: These data are divided by DIVs (14, 21, 28), and the name of each experiment classifies the type (ALS or WT).

- Imaging folder:


