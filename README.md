# NumPy Learning

This repository contains my learning journey with **NumPy**, starting from the basics and gradually moving toward array manipulation, numerical analysis, vector operations, and working with NumPy files.

## What I Learned

### Phase 1 — NumPy Basics

In the first phase, I learned the fundamentals of NumPy:

* Creating 1D and 2D NumPy arrays
* Understanding the difference between Python lists and NumPy arrays
* Performing operations on NumPy arrays
* Comparing basic performance between Python lists and NumPy arrays
* Creating arrays using:

  * `np.zeros()`
  * `np.ones()`
  * `np.full()`
  * `np.random.random()`
  * `np.arange()`
* Understanding vectors, matrices, and tensors
* Understanding array properties:

  * `shape`
  * `ndim`
  * `dtype`
  * `size`
* Reshaping arrays using `reshape()`
* Flattening arrays using `flatten()` and `ravel()`
* Transposing arrays using `.T`

### Phase 2 — NumPy Array Operations

In this phase, I practiced manipulating and working with arrays:

* Array slicing
* Negative indexing
* Selecting rows and columns from 2D arrays
* Sorting arrays using `np.sort()`
* Sorting along rows and columns using `axis`
* Filtering arrays using conditions
* Boolean masking
* Fancy indexing
* Using `np.where()`
* Conditional replacement with `np.where()`
* Merging arrays using `np.concatenate()`
* Checking array shape compatibility
* Adding rows using `np.vstack()`
* Adding columns using `np.hstack()`
* Deleting elements using `np.delete()`

### Phase 3 — Advanced Operations & Business Example

I applied NumPy concepts to a small restaurant sales analysis example.

I learned how to:

* Represent business data using NumPy arrays
* Analyze data using `np.sum()`, `np.min()`, `np.max()`, and `np.mean()`
* Calculate total sales for different years
* Calculate minimum and maximum sales
* Calculate average sales for each restaurant
* Use `np.cumsum()` for cumulative sales
* Visualize numerical results using Matplotlib
* Perform vector addition and multiplication
* Calculate dot products using `np.dot()`
* Calculate vector angles using NumPy's mathematical functions
* Calculate vector magnitudes using `np.linalg.norm()`
* Apply functions to arrays using `np.vectorize()`
* Perform numerical calculations across an array using broadcasting

### Phase 4 — Saving, Loading & Visualization

In the final phase, I learned how to work with NumPy arrays as files.

I practiced:

* Creating different types of NumPy arrays
* Saving arrays using `np.save()`
* Loading arrays using `np.load()`
* Working with `.npy` files
* Visualizing NumPy array data using Matplotlib
* Creating a modified version of an image array
* Displaying NumPy array data as an image

## Main NumPy Concepts Covered

```text
NumPy Arrays
     ↓
Array Properties
     ↓
Array Creation
     ↓
Reshaping & Transposing
     ↓
Indexing & Slicing
     ↓
Filtering & Boolean Masking
     ↓
Sorting & Merging
     ↓
Array Manipulation
     ↓
Numerical Operations
     ↓
Vector Operations
     ↓
Business Data Analysis
     ↓
Visualization
     ↓
Saving & Loading .npy Files
```

## Repository Structure

```text
Numpy-learning/
│
├── phase1.ipynb
├── phase2.ipynb
├── phase3.ipynb
├── phase4.ipynb
│
├── array1.npy
├── array2.npy
├── array3.npy
└── numpy-logo.npy
```

## Goal

The goal of this repository is to document my progress while learning NumPy and build a strong foundation for **Data Science and Machine Learning**.

This repository will be updated as I continue learning new concepts and applying them to practical examples.
