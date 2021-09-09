# Class Two: Data Manipulation in Python

## Overview

- Data science stack: Python -> numpy -> pandas

## numpy

- **Vectors**
  - Why vectors? (for science, need multiple measurements of any outcome!)
  - What is vector? (single-typed, concept of order)
  - Vector math / operations (modelled [after this?](https://cm4ss.com/html/intro_to_vectors.html))
  - Subsetting vectors (by index, by logicals) (modelled [after this?](https://cm4ss.com/html/manipulating_vectors.html))
  - Editing vectors
  - Views v. copies
- **Matrices**
  - Why matrices? (often we want to measure different outcomes for the same units of analysis, so we can stack vectors to make a matrix)
  - Matrix math ([modeled after this?](https://cm4ss.com/html/intro_to_matrices.html))
  - Subsetting matrices: just 2 dimensional extension of vectors ([modeled after this?](https://cm4ss.com/html/manipulating_matrices.html))

## pandas

- **Why?**
  - Heterogenous tables! 
- **Series**
  - Just a vector with a set of row labels called an index. 
  - Subsetting: `iloc[]` (like numpy) and `loc[]` (uses labels). 
- **DataFrames**
  - Collection of Series. 
  - Summary functions
  - Subsetting ([modeled after this?](https://www.practicaldatascience.org/html/pandas_dataframes.html))

## plotting data

- **The Python Plotting Ecosystem**
  - matplotlib, seaborn, plotnine, altair
- **Grammer of Graphics**

## More Python

- Loading data / data formats
- Missing data representations / `pd.isnull()`
- The views/copies disaster

## Data Manipulation

- Cleaning
- Merging
- Groupby