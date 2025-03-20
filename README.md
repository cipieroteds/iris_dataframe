***Project: Database Conversion from Array to DataFrame***

*Description* 

This project loads the Iris dataset from sklearn, transforms the data from an array format into a pandas DataFrame, adds more descriptive column labels, and replaces numeric classification values with the corresponding species names. 

*Technologies Used*

Python 

Pandas 

NumPy 

Scikit-learn 

*Code Structure*

Loading the dataset: The Iris dataset is loaded using datasets.load_iris(). 
Data conversion: The array containing the flower data is transformed into a DataFrame. 
Class conversion: The array containing the flower classifications is also transformed into a DataFrame. 
Data concatenation: The two tables are merged to form a single DataFrame. 
Column renaming: The columns are renamed with the actual names of the flower features. 
Replacing numeric classes: The numeric values in the classification column are replaced with the corresponding species names. 
Class count: Displays the count of each species in the dataset. 

*How to Run* 

Make sure you have Python installed (version 3.7 or later). 
Install the required libraries if you haven't already: pip install pandas numpy scikit-learn 
  

Run the Python script in your preferred environment (Jupyter Notebook, VS Code, etc.). 

*Example Output*

The final output of the DataFrame will look something like this: 

![image1](https://github.com/cipieroteds/iris_dataframe/blob/main/image.JPG)


