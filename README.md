Machine Learning in Physics

Author: Ammiel Peters

Project Supervisor: Dr. Rakesh Moulick

A project report submitted in partial fulfillment of the requirements for the award of the degree of Bachelor of Technology in Computer Science and Engineering (2023) from Sikkim Manipal Institute of Technology.

Abstract

This project discusses the applications of machine learning in the field of space and laboratory plasma. Solar data was collected to establish various relations, and Langmuir probe data was analyzed for laboratory plasma. The project explores the use of ML for image recognition, data classification, and predicting physical properties, while also discussing challenges like data requirements and overfitting.

Project Structure

This project is divided into three main analyses:

Electron and Plasma Interaction (electron_plasma_interaction.py)

Goal: Predict missing values from a dataset concerning beam electron and plasma interaction to calculate the kinetic energy percent retrieval.

Methods: A Decision Tree was used to predict missing values, and a 6th-degree Polynomial Regression was applied to find the best-fit line for the data.

Sunspot Data Analysis (sunspot_data_analysis.py)

Goal: Analyze sunspot data to find correlations between sunspot numbers and the electron density/temperature at various altitudes (500 km to 2000 km) from 2012 to 2022.

Methods: Linear Regression was used to find correlations between the parameters.

Langmuir Probe Data Analysis (langmuir_probe_analysis.py)

Goal: Analyze the I-V (current-voltage) characteristics from a Langmuir probe to diagnose laboratory plasma.

Methods: A 7th-degree Polynomial Regression was used to find the best possible fit for the experimental data points.

How to Run

The analysis scripts are written in Python. You will need the following libraries to run them:

pandas

scikit-learn

numpy

matplotlib

You can install them using pip:

pip install pandas scikit-learn numpy matplotlib

Then, run each Python script individually to see the analysis and resulting plots. Note that the scripts may require specific data files (.csv, .txt) as described in the project report.

Project Report

The complete thesis can be found in the file Project Report(Thesis Paper).docx.
