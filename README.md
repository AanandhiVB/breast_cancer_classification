# breast_cancer_classification

## Breast Cancer Classification

**Objective**

Prepare a Jupyter Notebook (recommended - Google Colab) to build, train and evaluate a Machine Learning model on the given dataset. Please read the instructions carefully.

**Dataset**

Dataset - https://drive.google.com/file/d/1AnRf3cl-MflHd4JVK07Az3UdvemNRU4a/view?usp=sharing. This breast cancer database was obtained from the University of Wisconsin Hospitals, Madison from Dr. William H. Wolberg. 

**Attribute Information**
| Columns | Description |
|--|--|
| Sample code number                   | id number |
| Clump Thickness                      | 1 - 10    |
| Uniformity of Cell Size              | 1 - 10    |
| Uniformity of Cell Shape             | 1 - 10  |
| Marginal Adhesion                    | 1 - 10 |
| Single Epithelial Cell Size          | 1 - 10 |
| Bare Nuclei                          | 1 - 10 |
| Bland Chromatin                      | 1 - 10 |
| Normal Nucleoli                      | 1 - 10 |
| Mitoses                              | 1 - 10 |
| Class                                | <ul><li>2: benign</li><li>4: malignant</li></ul>


**Perform the following tasks:**

**PART - A**
1. **Import Libraries/Dataset**
     
     - Download the dataset
     - Import the required libraries

2. **Data Visualization and Exploration**

    - Print at least 5 rows for sanity check to identify all the features present in the dataset and if the target matches with them
    - Print the description and shape of the dataset
    - Provide appropriate visualization to get an insight about the dataset
    - Try exploring the data and see what insights can be drawn from the dataset

3. **Data Pre-processing and Cleaning**

     - Do the appropriate preprocessing of the data like identifying NULL or Missing Values if any, handling outliers if present, skewed data etc. Apply appropriate feature engineering techniques for them
     - Apply the feature transformation techniques like Standardization, Normalization, etc. You are free to apply the appropriate transformations depending upon the structure and the complexity of your dataset
     - Do the correlational analysis on the dataset. Provide a visualization for the same

4. **Data Preparation**

     - Do the final feature selection and extract feature and target variables
     - Split the dataset into train and test sets

**Part - B**
1. **Model Building**

    - Perform Model Development using at least any three ML models, separately: 
		- Decision Tree, K-Means, KNN, Hierarchical Clustering, Naive Bayes
    - Train the model and print the training accuracy and loss values

2. **Performance Evaluation**

     - Print the confusion matrix. Provide appropriate analysis for the same
     - Do the prediction for the test data and display the results for the inference
