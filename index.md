---
layout: default
title: Learn_python
nav_order: 1
has_children: true
---
# [header1](header1.md) 
## [header1](header1.md) 
### [header1](header1.md) 

# Home

## What is python?

Write some stuff about python here

## How to download and install Python

## Which IDE should i use?

## Intro to Python


### Scatterplot




Seaborn is an library that extends Matplotlib to create highly sofisticated statistical visulisations from Pandas data structures using minimal code. Below you will see examples of a heatmap, and a subset of histograms (For more examples check out Seaborn:statistical data visulisation example gallery at https://seaborn.pydata.org/examples/index.html)

<p align="center"> <img src="https://user-images.githubusercontent.com/94447127/168817370-1c623b25-cfe6-4906-bf95-d974da18c311.png" width="400" height="400"> </p>
<p align="center"> <img src="https://user-images.githubusercontent.com/94447127/168819351-4791adae-1242-4ad8-ac40-60e22364b445.png" width="450" height="350"> </p>

### Scatterplot

  `scatterplot()` is used to plot data and visualise the relationship of the values in the form of a scatter, with each point in the scatter representative of an observation in the dataset.
  
 In order to create a seaborn scatterplot in python you will need to import the following packages:
  
  ```python
  import seaborn as sns
  import matplotlib.pyplot as plt
   ```
 Now we can take the data of 10 large dogs (in age = years, weight = kg) and create a pandas datafames:
  ```python
  Years = [1, 10, 9, 3, 5, 4, 1, 6, 4, 6,]
  Weight = [39, 45, 32, 58, 44, 41, 47, 52, 55, 32]
  ```
 These df can now be plotted onto a scatter to compare how age may relate to a dogs weight across large dog breeds:
  
  ```python
  sns.scatterplot(x = Years,
                  y = Weight)
  
  plt.show()
  ```
  
  
  
### Countplot
  `countplot()` takes a categorical list and returns bars representative of the number of list entries per category.
  
  
