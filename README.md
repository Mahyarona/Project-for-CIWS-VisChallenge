# GUI developed for Cyberinfrasructure for Intelligent Water Supply Data Visualization Challenge

This repository introduces an algorithm developed as an APP in Gepgraphical User Interface (GUI) of **MATLAB** for [Cyberinfrastructure for Intelligent Water Supply Data Visualization Challenge](https://github.com/UCHIC/CIWS-VisChallenge). The App analyzes and classifies the high temporal resolution signal pulse of single house residential water usage into eight different categories including *Dishwasher, Bath, Leak, Clothes Washer, Faucet. Shower and Toilet, Outdoor Irrigation,* and *Other*.

This App and its results could be used to visualize and analyze high resolution water use data that would be useful for both water users and water providers. The advantage of the developed GUI is that it is easily understandable and may provide actionable information. For example, homeowner can see their water use visually and may change their behavior based on the information shown in this GUI. 

## What do you expect to see as the result of this APP?


## APP Description
The goal of developing this App is to first detect the signals and then estimate and disaggregate the volume and duration of residential water usage into common water usage categories (i.e., the eight categories mentioned above). The proposed algorithm detects the signals . Even though this algorithm may not be as accurate as other algorithms such as Hidden Markov Model in litreture, it is faster than those of algorithms in terms of computational time. This README document is prepared in three different parts:

  1. How to prepare the datasets for the App
  2. How does the proposed algorithm cluster the signals into aformentioned categories
  3. Summary of steps to run the APP


### 1. How to prepare the datasets for the App
To run the APP, users only need to import the data (i.e., in CSV format file) in **.mat** format and define a period for the anlaysis. To convert data from .csv into .mat, the user needs to import the .csv file using the collowing icon of the Matlab software and then save it as **Data**. 
<img src="https://github.com/Mahyarona/Project-for-CIWS-VisChallenge/blob/master/images/ImportData.jpeg" width="400" height="400"

For analysis period, a user can define the starting and ending time using **pop of menu** in the APP.


### 2. How does the proposed algorithm cluster the signals into aformentioned categories
First, the data must be converted to **TimeTable** format. 

### 3. Summary of steps to run the APP
The APP is developed in MATLAB and a user just need to (1) import the data in **.mat** format using *import* push button, (2) define the time period for which he/she wants to see results using *pop up menu*, and (3) run the APP using *Run model* button to get results. 

## Contact Information
For information about the GUI or if you have general questions, contact Mahyar Aboutalebi at m.aboutalebi@aggiemail.usu.edu
