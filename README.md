# Project for CT4101 Machine Learning module
Title: Predicting whether the Body Mass Index is healthy or not without knowing height or weight.

Purpose: To investigate whether the Body Mass Index can be correctly classified as 'too low', 'healthy' or 'too high' from factors other than height and weight.

Dataset: National Health and Nutrition Health Survey 2013-2014 (NHANES) Age Prediction Subset

Source: https://archive.ics.uci.edu/dataset/887/national+health+and+nutrition+health+survey+2013-2014+(nhanes)+age+prediction+subset 

To run this model: Simply download the CSV file found in the source link (if unable to access it from this repository) and change file path in 'ReadData.ipynb' to match the file path on your device for the CSV.

Features (as listed by authors of the data set): 
- SEQN = Respondent Sequence Number {Continuous}
- age_group = Respondent's Age Group (senior/non-senior) {Categorical}
- RIDAGEYR = Respondent's Age {Continuous}
- RIAGENDR = Respondent's Gender {Continuous} 
- PAQ605 = If the respondent engages in moderate or vigorous-intensity sports, fitness, or recreational activities in the typical week {Continuous}
- BMXBMI = Respondent's Body Mass Index {Continuous}
- LBXGLU = Respondent's Blood Glucose after fasting {Continuous}
- DIQ010 = If the Respondent is diabetic {Continuous}
- LBXGLT = Respondent's Oral {Continuous}
- LBXIN = Respondent's Blood Insulin Levels {Continuous} 

Note: 
RIAGENDR: 1 represents Male & 2 represents Female
PAQ605: 1 represents that the respondent takes part in weekly moderate or vigorous-intensity physical activity & 2 represents that they do not