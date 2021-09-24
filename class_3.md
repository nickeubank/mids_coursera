# Class Three: Loading and manipulating data


## WEEK ONE

(Drew and Genevieve: exceptions, tracebacks, and I/O)

## WEEK TWO

- Theme: Welcome to pandas
- Learning objectives: 
    - Understand why we need pandas
    - Be familiar with indices and index alignment, though also in general we will emphasize avoiding them

### Working with tabular data of mixed types (pandas)

- **Why pandas?**
  - Heterogenous tables!
  - Easier to work with tabular data 
- **Series**
  - Just a vector with a set of row labels called an index. 
  - Subsetting and indexing: `iloc[]` (like numpy) and `loc[]` (uses labels). 
- **DataFrames**
  - Collection of Series. 
  - Summary and descriptive functions (head, describe, etc.)
  - Subsetting ([modeled after this?](https://www.practicaldatascience.org/html/pandas_dataframes.html))
- **Computation on DataFrames**
  - Performing operations on columns and creating new columns
  - Calculating counts, min, max, means, etc.
  - Working with categorical vs numerical vs textual data

## WEEK THREE

### Loading and cleaning data

- **Data Formats / Loading Data**
  - JSON, tabular (csv, tsv), plaintext v. binary, etc.
- **The views/copies disaster**
- **Cleaning**
  - Missing data representations / `pd.isnull()`
  - NaNs, Infs, Null/None, and placeholder values
  - Replacing values
-  **Exporting data to files**

### Defensive Programming for Data Analysis

- To err is human
- Tests in ds code
- Style matters: PEP8 (needed? ask D&G)
- Data version control concepts that can be depoyed programmatically 
  - Saving and updating preprocessing scripts/modules
  - Always save your raw data

## WEEK FOUR

### Data Manipulation

- **Merging**
- **Groupby**
- **Worked example showing the usefulness of Pandas on real data**
