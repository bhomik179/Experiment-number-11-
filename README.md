# Experiment-number-11-

# Experiment 11 – Dataset Creation and Loading using Pandas

Name: Bhomik Keshi  
Roll Number: 25070123172  
Experiment Number: 11  

# Objective  
The objective of this experiment is to understand how datasets can be created and loaded using the Pandas library in Python. The experiment also focuses on learning how external datasets can be imported and analyzed using Python in a data analysis environment.

# Introduction  
Data analysis often requires structured datasets that can be processed and analyzed efficiently. Python provides powerful libraries such as Pandas that help in organizing and working with structured data. In this experiment, a dataset is first created manually and then converted into a Pandas DataFrame so that it can be represented in tabular form. After understanding dataset creation, an external CSV dataset is loaded to observe how real-world datasets are handled.

# Methodology  
The experiment begins by importing the required libraries such as Pandas and NumPy. After importing the libraries, a dataset is created using a dictionary containing different fields like roll number, gender, department, and CGPA. This dictionary is then converted into a Pandas DataFrame so that the information is displayed in a structured table format.

To understand how external datasets are used, Google Drive is mounted in the environment so that files stored in the drive can be accessed. After mounting the drive, a CSV file containing the Cars93 dataset is loaded using the Pandas `read_csv()` function. Once the dataset is loaded, it is displayed to observe its structure, rows, and columns.

# Understanding the Process  
The dataset creation process involves defining data in the form of key-value pairs and converting it into a DataFrame using a statement similar to `pd.DataFrame(data)`. When working with external datasets, Pandas allows CSV files to be loaded easily using a command similar to `pd.read_csv("filename.csv")`. These commands make it simple to organize, view, and analyze structured data.

# Result  
The dataset created using Python is successfully displayed in tabular form using a Pandas DataFrame. The external Cars93 dataset is also loaded successfully and displayed, showing multiple rows and columns representing different attributes of cars.

# Conclusion  
This experiment helped in understanding how datasets can be created manually in Python and how external datasets can be loaded using the Pandas library. It also demonstrated how Pandas DataFrames provide a convenient way to organize and view structured data, which is an essential step in data analysis and data science workflows.
