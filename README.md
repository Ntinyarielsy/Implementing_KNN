# CSE 6363 - Machine Learning Fall 2023
## Assignment Algorithm: K Nearest Neighbor

- project summary.
- Installation and set ups.


### Project summary
The project requires us to build a KNN model to predict the gende of a person (Male or Female) depending on the input features.
We are provided with a dataset [original data](Data1P_05_105_06_106.xlsx) that we will perform some data cleaning on it.We will be performing a number of data cleaning processes like missing value imputations, data transposations, encoding among others.
A knn model classifier will be developed to predict gender and a program will be written to allow input of varios parameters.
We will also use numpy and math libraries only to get predictions, calculate accuracy and confusion matrix.

### Set up and running cde 

Create a python environment 
```
python -m venv dts
```
Run the following code to activate the virtaual environment
```
 source dts/Scripts/activate

```
Install the required packages and libraries
```
pip instal -r requirement.txt

```

Note:
- When you install e.g pandas it come with other libraries like numpy.

Other specification I worked with
- python 3.11
- VSCODE editor 1.82.2
- windows 10
- terminal: Gitbash


Open `knn.ipynb` notebook and run it on the activated virtual environment