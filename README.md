## LSTM for Seizure Prediction

# Anticipating Seizures using LSTM networks
This repository contains all research work done for analyzing and predicting seizures, by classifying <strong>*raw*</strong> EEG data between preictal and interictal brain activity with *LSTMs*. The work was done using Jupyter Notebooks, containing 2 notebooks, one being the methodology used for segmenting and preparing data for the models, and the other notebook focusing on extracting train/val/test datasets for the different model architectures to train and test with. 

##### The work here makes use of the CHB-MIT dataset, available <a href="https://physionet.org/content/chbmit/1.0.0/">HERE</a>

#### Features and Labels used with different time periods, <a href="https://drive.google.com/drive/folders/1Ef7OBt9xA1_YE0Bj-eeshrAALw0JjxMp?usp=sharing">visit here</a>
#### (*Temporary*) Since this is a recent work, permission is needed for accesing data on Google Drive

##### PLEASE NOTE: current data is available on a restricted access google drive. Data on the drive is divided in the following way : *preictal_period -> _subwindowSize -> _numTimesteps_perWindow* 
    This is done in exception to using an ANN, which does not work with timesteps, *preictal_period -> _subwindowSize -> _ANN* 

## In order to work with these notebooks, the following libraries are required: 
* tensorflow version > 2.0.0
* mne
* numpy
* sklearn
