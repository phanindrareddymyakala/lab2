# MLOps-Project
# Pneumonia Onset Prediction in ICU Patients
# Overview
This repository contains code to build a machine learning model that can predict the onset of pneumonia in ICU patients 48 hours before the actual diagnosis. The model is trained on the freely available eICU critical care dataset.

# Installation
To install the dependencies, run:

~~~
pip install -r requirements.txt
~~~
# Data
The eICU critical care dataset is hosted by MIT Laboratory for Computational Physiology and can be accessed after signing a DUA and completing required CITI training on human subjects research. The data contains over 200k admissions across multiple ICUs in the US.

The features used include demographics, vital signs, and lab test results. The target variable is a diagnosis of pneumonia based on ICD-9 codes.

# Results
The best performing model are in progress on the test set. The most important features were found to be respiratory rate, WBC count, and temperature.

# Contributing
Contributions to improve the model performance or implementation are welcome! Please open an issue or PR.

# License
The eICU dataset is subject to DUA restrictions. All other code in this repository is under the MIT license.
