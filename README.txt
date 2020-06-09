------------------------------------
PERSONAL DATA DETECTION VIA METADATA
------------------------------------


CONTENT
------------------------------------
-Python code: 2 Jupyter Notebook files containing the code to be run
	main.ipynb
	functions.ipynb

-Datasets.
	-In the "Datasets" folder, you can find the 5 datasets outlined in the paper with their corresponding labels file. These are used to train and test the models.
	-In the "Dataset Info" folder, you can find a document with the sources used for the public data and an example Oracle SQL query to extract the raw data from a Database.


PREREQUISITES
------------------------------------
In order to run the code, you need to have Python 3 and Jupyter Notebook installed in your machine.
The easiest way to do this is install the Anaconda platform: https://www.anaconda.com/distribution

The following Python packages are also necessary:
-Pandas: https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html
-NumPy: https://pypi.org/project/numpy/
-Fasttext: https://pypi.org/project/fasttext/
-Scikit-learn: https://scikit-learn.org/stable/install.html


RUNNING THE CODE
------------------------------------
You only need to execute main.ipynb in order to perform any experiments. The instructions on how to do this are found in the notebook.
2 main blocks are provided:
	-Basic execution: Allows the user to load a dataset, train a model, create predictions on another dataset and evaluate the performance.
	-Advanced options: Parameter/hyperparameter sweeps and optimization.

Advanced users might want to add or modify the functions in functions.ipynb, but this is not necessary


VERSIONING
------------------------------------
v1 - 31-Mar-2020