

# AutoML Web Application
[Videolink:](https://drive.google.com/file/d/1Y_bdPdQAjOBzpyb_usbklB7Ax_uQ5RG5/view?usp=share_link)
This is a web application built using Flask to perform exploratory data analysis (EDA) and automate the machine learning pipeline using the flaml library.

# Features
The web application has the following features:


Perform exploratory data analysis on the uploaded dataset.
Train, optimize and output the best machine learning model using flaml.

# Requirements
The following are required to run the application:

Python 3.8 or higher.
Flask
pandas
pandas_profiling
scikit-learn
flaml



> **Install the required libraries pip install -r requirements.txt.**

Run the application python app.py.
Usage
Launch the application using the steps above.
Upload your dataset in CSV or Excel format.
Choose your desired output format (CSV or Automl).
If you select the Automl option, the web application will perform the following:
Split the dataset into dependent and independent variables.
Determine the type of problem (regression or classification).
Train and optimize a machine learning model using flaml.
Display the best machine learning model's details in a table.

**Limitations**

The application only supports CSV and Excel file formats.
The application only trains and optimizes the model using flaml. There are no options to change the model parameters.
