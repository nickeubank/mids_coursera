# Class Two: Data Manipulation in Python

## Overall learning objectives (mapped to specialization learning objectives):
- Manage and manipulate real-world datasets for data science applications
- Convey the results of programming analyses through data summaries and plots
- Describe the components and packages of the Python ecosystem

## WEEK ONE

- Theme: Welcome to arrays and matrices, the foundational data structures for computation
- Learning objectives: 
  - Understand why arrays are key to data science; 
  - learn basics of subsetting and manipulating arrays

### Overview

- Data science stack: Python -> numpy -> pandas

### Data structures for computation (numpy)
- **Why numpy**
  - Easier to use for computational programming
  - Faster than equivalent operations using Python lists
  - Wide array of mathematical functions available in the library
  - Integrates nicely with many other computational and plotting packages
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

## WEEK TWO

- Theme: Welcome to pandas
- Learning objectives: 
    - Understand why we need pandas
    - Be familiar with indices and index alignment, though also in general we will emphasize avoiding them
    - Understand the plotting ecosystem in Python
    - Understand the graphics of grammar
    - Be able to do basic plots in altair

### Working with tabular data of mixed types (pandas)

- **Why pandas?**
  - Heterogenous tables!
  - Easier to work with tabular data 
- **Series**
  - Just a vector with a set of row labels called an index. 
  - Subsetting: `iloc[]` (like numpy) and `loc[]` (uses labels). 
- **DataFrames**
  - Collection of Series. 
  - Summary functions
  - Subsetting ([modeled after this?](https://www.practicaldatascience.org/html/pandas_dataframes.html))

### plotting data

- **The Python Plotting Ecosystem**
  - matplotlib, seaborn, plotnine, altair
- **Grammer of Graphics**
- Common types of plots:
  - Line, scatter, bar (histogram), heatmap
- Saving your plots for sharing or reuse

## WEEK THREE (too ambitious?)

- Theme: Your data is never perfect. Here's how we can clean and manipulate it for insights. 		
- Learning objective: 
  - Prepare data for analysis 
  - Never trust your data too much
  - clean, merge, and manipulate data		

### More Python

- Loading data / data formats
- Missing data representations / `pd.isnull()`
- The views/copies disaster

### Data Manipulation

- Cleaning
- Merging
- Groupby

## WEEK FOUR 

*(If need to spread out week 3, we can move some of this to course 4)*

- Theme: Big Data
- Learning objectives
  - Understand why loops are slow in Python
  - Be able to recognize vectorized code
  - Understand what makes big data big


### Performance

- Loops and vectorization
- Parallelism and its limits

### Big Data

- What makes big data big (e.g. memory hierarchy)
- Big data strategies (e.g. chunking)
- Tools for big data: dask
