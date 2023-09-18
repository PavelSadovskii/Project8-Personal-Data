# Project Description

This project focuses on data transformation to protect the personal data of customers for the insurance company "Though the Flood." The goal is to develop a data transformation method that makes it difficult to recover personal information while maintaining the quality of machine learning models.

## Tools and Libraries

The following tools and libraries were used for this project:

- Python
- NumPy
- Pandas
- Sklearn

## Project Steps

### Step 1: Loading Data

#### Import Required Libraries and Modules

### Step 2: Matrix Multiplication

#### Generate a Random Square Matrix

#### Check the Matrix for Invertibility

### Step 3: Conversion Algorithm

#### Algorithm

So, the algorithm will be as follows:

1. Generate a random square matrix of dimension = the number of columns in features (number of features).
2. Check the generated matrix for invertibility.
3. Calculate 'a' and 'w' for initial parameters.
4. Calculate 'a'' and 'w'' for new parameters.
5. Check if there is a difference between the new and original parameters using the R2 metric.

### Step 4: Algorithm Check

#### Program the Algorithm

#### Calculate the Results

#### Evaluate the Results

## Conclusion

In this project, we successfully developed a data transformation algorithm to protect the personal data of customers while maintaining the quality of machine learning models. The algorithm involved generating a random square matrix, checking its invertibility, and applying it to the features. The R2 metric was used to compare the performance of models before and after transformation.

The results showed that the quality of the linear regression model did not change significantly when using the transformed features, demonstrating the effectiveness of the data transformation method in preserving data privacy while maintaining model accuracy.
