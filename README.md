# Predicting Student Pass Fail using Classification Models
This project was created in <a href="https://jupyter.org/">Jupyter Notebook</a> for Data Visualization purposes
## Goal of the Project
To build classification models (logisitic regression & decision tree) that help predict if a student will pass or fail depending on multiple categories that apply to each student. Our dataset is comprised of 649 students (rows) and 33 categories (columns) for each student. We will be splitting the dataset into a testing and a training dataset to avoid any influence or bias from the training dataset onto the testing dataset when the models are being trained. 

**The Python packages used for this project:**

<b> Scikit-learn</b>
<p><a href="https://scikit-learn.org/stable/">scikit-learn</a>
The purpose of this guide is to illustrate some of the main features that scikit-learn provides. It assumes a very basic working knowledge of machine learning practices (model fitting, predicting, cross-validation, etc.). Please refer to our installation instructions for installing scikit-learn.

Scikit-learn is an open source machine learning library that supports supervised and unsupervised learning. It also provides various tools for model fitting, data preprocessing, model selection and evaluation, and many other utilities. </p>
<ul>
  <li> <b>pandas</b>
    <p>pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.

pandas is a NumFOCUS sponsored project. This will help ensure the success of development of pandas as a world-class open-source project, and makes it possible to donate to the project.</p>
  </li>
   <li><b> NumPy</b>
  <p><a href="https://numpy.org/">NumPy</a> is the fundamental package for scientific computing with Python. It contains among other things:

- a powerful N-dimensional array object

- sophisticated (broadcasting) functions

- tools for integrating C/C++ and Fortran code

- useful linear algebra, Fourier transform, and random number capabilities

- Besides its obvious scientific uses, NumPy can also be used as an efficient multi-dimensional container of generic data. Arbitrary data-types can be defined. This allows NumPy to seamlessly and speedily integrate with a wide variety of databases.

NumPy is licensed under the BSD license, enabling reuse with few restrictions.</p>
</li>
  <li><b>graphviz</b><p><a href="https://www.graphviz.org/">Graphviz</a>is open source graph visualization software. Graph visualization is a way of representing structural information as diagrams of abstract graphs and networks. It has important applications in networking, bioinformatics,  software engineering, database and web design, machine learning, and in visual interfaces for other technical domains. </p></li>
   <li><b>matplotlib</b><p><a href="https://matplotlib.org/">Matplotlib</a> is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms. Matplotlib can be used in Python scripts, the Python and IPython shells, the Jupyter notebook, web application servers, and four graphical user interface toolkits.</p></li>
  <li><b>itertools</b><p>This module implements a number of iterator building blocks inspired by constructs from APL, Haskell, and SML. Each has been recast in a form suitable for Python.

The module standardizes a core set of fast, memory efficient tools that are useful by themselves or in combination. Together, they form an “iterator algebra” making it possible to construct specialized tools succinctly and efficiently in pure Python.</p></li>
  <li> os</li>
</ul>

## Source of Dataset
The Student Performance Dataset was sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Student+Performance).
The dataset can be found in the current repository under /student/student-por.csv and has been split into:
- student-por-test.csv
- student-por-train.csv
