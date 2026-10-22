# MMA3001-Project
## Instructions
First download the ZIP file and extract to a location of your choosing.

Next, open Google Colab and upload these files to the main /content/ directory.

Next, import and open "Prediction_Demo.ipynb" in google colab.

Then, press "run all" and input your engine data as prompted. An example input CSV file has been provided, where sensor data can be added individually. The corresponding ranges that each sensor was trained on is provided in the column headers to assist in this process.

You will then be provided a list of estimated RUL's and a warning issued if RUL is less than or equal to 20.

Accepted Inputs:

The computational solution accepts engine operating data from a CSV or whitespace-delimited text file. Each observation must contain 26 numerical columns: an engine identifier, an operating cycle number, three operating settings and 21 sensor measurements. Engine identifiers and cycle numbers must be positive integers, and each engine-cycle combination must be unique. The operating settings and sensor measurements must be consistent with the NASA C-MAPSS dataset. 

## AI Statement

Generative AI was used to aid in the development of these files. 
All code has been verified by a human as fit for purporse.
