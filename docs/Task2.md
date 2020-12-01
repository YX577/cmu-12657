[Task 1](Task1.md) | [Task 3](Task3.md) | [Resources](Resources.md) | [Main Page](https://mushimu.github.io/12657-project/)

## Task 2. Familiarize with RCM output format, Python commands and libraries to extract data

In this task, you will learn some basics of the Python programming language that will help you extract the data from the netCDF format used commonly to store climate simulation runs.

----

## Learning Objectives

1. Learn basic data structures and commands in Python
2. Familiarize with the netCDF data format
3. Learn how to load and use the different libraries for Python needed to manipulate netCDF format
4. Code simple functions to extract data from the runs files.
5. Extract data for a single location
6. Store extracted data (for instance, precipitation on a specific time period) in friendlier data formats (for instance, csv to use in Excel)

----

## Data required for this task

- WRF Control Output: Downloaded from Canvas

- WRF PWG Output: Downloaded from Canvas

- Task 2 Jupyter Notebook (Python): Downloaded from Canvas

----

## Basic data structures and commands in Python

There are three major data structures:

- Lists
```python
fruits = ['apple', 'grapes', 'orange']
```

- Tuples
```python
fruits = ('apple','grapes', 'orange')
```
- Dictionaries
```python
fav_fruits = {'Anne':'apple','Julie': 'grapes', 'Erin': 'orange'}
```

The difference between the three types lies on how you access the data stored and what type of operations you can perform on each.

The following website contains tutorial-like activities that will help you learn the basics of Python data structures and other commonly used libraries such as NumPy and Pandas.

If you have never taken any course in Python, then please complete the following sections of this external tutorial:

- [Variables and Types](https://www.learnpython.org/en/Variables_and_Types)
- [Basic Operators](https://www.learnpython.org/en/Basic_Operators)
- [String Formatting](https://www.learnpython.org/en/String_Formatting)
- [Functions](https://www.learnpython.org/en/Functions)
- [Dictionaries](https://www.learnpython.org/en/Dictionaries)
- [Modules and Packages](https://www.learnpython.org/en/Modules_and_Packages)
- [Numpy Arrays](https://www.learnpython.org/en/Numpy_Arrays)
- [Pandas Basics](https://www.learnpython.org/en/Pandas_Basics)

----

## The NetCDF format

The Network Common Data Form (netCDF) is a framework to store scientific data in the form of arrays.

Various characteristics make the netCDF the chosen data format for storing scientific data (Centre for Environmental Data Archival, N.D.):

- **Self-describing**: every file has an associated metadata that tells information about what is stored in the file, for instance: name of variables, units of measure, map projection used in the model simulation, etc.

- **Portable**: data written in one specific operative system/platform can be read on other platforms, so it is easy to share with the community.

- **Sliceable**: a small subset of a large dataset may be accessed efficiently, without reading all the preceding data.

- **Appendable**: data can be added to a file without altering or redefining its structure

If you want to know more about the netCDF format, navigate through the following website but is not required.

[UCAR Unidata: What is a netCDF?](https://www.unidata.ucar.edu/software/netcdf/docs/faq.html)

---

## Extracting data for a single location from climate model output

Download the jupyter notebook from Canvas.

Run the jupyter notebook on your computer carefully reading each cell content to understand what the code does.

---

## Quiz

Take the [quiz](https://forms.gle/5oPVSyvJEyKXPEao6) to mark this task as complete.

----

## References

- Centre for Environmental Data Archival, N.D., Overview of NetCDF. Retrieved December 30th, 2018 from http://www.ceda.ac.uk/static/media/uploads/ncas-reading-2015/05_netcdf_overview.pdf
