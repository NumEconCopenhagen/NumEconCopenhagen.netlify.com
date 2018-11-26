---
title: "Course plan"
---

On this page you find:

1. [The schedule](#schedule)
2. [Deadlines](#deadlines)
3. [Descriptions of each week](#descriptions)

<br>

## <a name="schedule"></a>1. Schedule 

<br>

{{< csvtable src="https://docs.google.com/spreadsheets/d/1f9qFOIj1gybzNqqtVoj3m1M-n7AKYesdkxSPKERy2Qw/export?format=csv" col_start="0" col_end="3">}}

<br>

## <a name="deadlines"></a>2. Deadlines

<br>

{{< csvtable src="https://docs.google.com/spreadsheets/d/1T3g-ltqZNWU_92QEdgSbyzlpUROkMUjVQkqzv6xGDD0/export?format=csv" col_start="0" col_end="1">}}

<br>

## <a name="descriptions"></a>3. Descriptions of each week 

### Week 1: Introduction

**Lecture:** You will be introduced to working with Python 3 (Anaconda, Jupyter Notebook, VS Code). In order to show the power of numerical methods, we will: 1) solve a consumer problem, 2) simulate an AS-AD model.

**Class:** Work on DataCamp courses (free access will be provided):

1. Intro to Python for Data Science
2. Intermediate Python for Data Science
3. Python Data Science Toolbox (Part 1)
4. Python Data Science Toolbox (Part 2)

### Week 2: Fundamentals: Primitives

**Lecture:** You will be given an in-depth introduction to the **fundamentals of Python** (objects, variables, operators, classes, methods, functions, conditionals, loops). You learn to discriminate between different **types** such as integers, floats, strings, lists, tuples and dictionaries, and determine whether they are **subscriptable** (slicable) and/or **mutable**. You will learn about **referencing** and **copying**. You will learn a tiny bit about **floating point arithmetics**.

**Class:** Continue to work on DataCamp courses

### Week 3: Fundamentals: Optimize, Printi and Plot

**Lecture:** You will learn how solve simple numerical optimization problems (**scipy.optimize**) and report the results both in text (**print**) and in figures (**matplotlib**). You will learn how to save your results for later use (**pickle**).

**Class:** Continue to work on DataCamp courses

### Week 4: Fundamentals: Random Numbers and Simulation

**Lecture:** You will learn how to use a random number generator with a seed and produce simulation results (numpy.random, scipy.stats). You will also learn to calcuate the expected value of a random variable through Monte Carlo integration. You will finally learn how to make your figures interactive (ipywidgets).

**Class:** Problem Set 1: Solving the Consumer Problem

### Week 5: Fundamentals: Workflow and Debugging

**Lecture::** You will be learn how to write modules and run scripts from a terminal (in VS Code). You will learn how to structure and comment your code, and document it for later use. You will learn how to share your code with others through Git. Finally, we will discuss debugging, both pre-emptively (print, asserts, try/except) and when everything is on fire (debugger). We will also discuss the importance of a variables scope (local, global, non-local).

**Class:** Problem Set 2: Finding the Walras Equilibrium in a Multi-Agent Economy 

### Week 6: Working with Data: Load/Save and Structure Data

**Lecture:** You will learn to load data from both offline (e.g. CSV or Excel) and online sources (e.g. DST or FRED). You will learn about pandas series and dataframes and how to structure and index your data. 

**Class:** Problem Set 3: Loading and Combining Data from Denmark Statistics

### Week 7: Working with Data: Basic Data Analysis

**Lecture:** You will learn how to work with you data and produce summary statistics (tables, historgrams, Lorenz curves etc.). You will learn to estimate simple statistical models on your data (linear regression) and see a *machine learning* example.

**Class**: Problem Set 4: Analyzing Data form Denmark Statistics

### Week 8:  Data Analysis Project

**Lecture:** Supervision on your data analysis project

**Class:** Work on your data analysis project

### Week 9: Algorithms: Searching and Sorting

**Lecture:** You will learn how to write pseudo code and a bit about computational complexity (big-O notion). You will learn learn about functional recursion and some illustrative search (sequential, binary, tree, hash) and sorting (bubble, insertion, quick) algorithms.

**Class**: Problem Set 5: Writing Your Own Searching and Sorting Algorithms

### Week 10: Algorithms: Solving Equations

**Lecture:** You will learn about working with matrices and linear algebra (scipy.linalg), including solving systems of linear equations. You will learn to find roots of linear and non-linear equations both numerically (scipy.optimize) and symbolically (sympy).

**Class**: Problem Set 6: Solving the Solow Model + feedback on your data analysis project

### Week 11: Algorithms: Numerical Optimization

**Lecture:** You will learn to solve non-convex multi-dimensional optimization problems using numerical optimization with multistart and nesting (scipy.optimize). You will learn simple function approximation using linear interpolation (scipy.interp). 

**Class**: Problem Set 7: Solving the Consumer Problem with Income Risk

### Week 12: Further Perspectives: The Need for Speed

**Lecture:** You will learn how to time your code and locate its bottlenecks. You will learn how to alleviate such bottlenecks using techniques such as iterators, comprehensions, vectorization and parallelization. You will be introduced to how  to use the Numba library to speed-up your code. You will hear about the fundamental computational costs of mathematical operations and memory management (caching), and see how to call programs written in C++ (ctypes) for optimal speed.

**Class**: Problem Set 8: Comperehension, Vectorization and Numba

### Week 13: Further Perspectives: R and MATLAB

**Lecture:** Two guess lectures will introduce you to the programming languages R and MATLAB.

**Class:** Work on your model analysis project

### Week 14: Further Perspectives: Julia

**Lecture:** A guest lecture will introduce you to the (up-and-coming) programming language Julia.

**Class**: Feedback on your model analysis project
