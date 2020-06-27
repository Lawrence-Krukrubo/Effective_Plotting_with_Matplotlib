# Effective_Plotting_with_Matplotlib:

Matplotlib is the most widely used if not the most popular data visualizing library in Python.
It was created by `John Hunter(1968 - 2012)`. Who was a neurobiologist and was part of a reseach Team that was analyzing electrocorticography(ECOG) signals.

The Team was using a proprietary software for the analysis, however they only had one license, and so were taking turns in using it.
So in order to overcome this limitation, john set out to replace this proprietary software with a MATLAB based version that could be utilized by him and his Team mates and that could be extended by multiple investigators.

As a result, matplotlib was originally developed as an ECOG visualization tool. And just like MATLAB, matplotlib was equipped with a scripting interface quick and easy generation of graphics, represented by pyplot.

<p align="center">
  <img width="700" height="300" src="https://github.com/Lawrence-Krukrubo/Immigrations_Data_Visualization_with_Matplotlib/blob/master/matplotlib-data-visualization2.jpg?raw=true" alt="Charts">
</p>

## Features:
This repo features a detailed intro to Matplotlib and its distinct layers and attributes. 
It also explores various plots nad syntaxes of Matplotlib. Further exploration of Matplotlib and other libraries in the Python ecosystem are made, for example:- using pandas library with matplotlib.

## Dependencies:
To follow along with these exercises as seen in the Notebooks above, kindly install and import the following:-

* `import matplotlib as mpl`
* `import matplotlib.pyplot as plt`
* `from matplotlib.backends.backend_agg import FigureCanvasAgg as FigureCanvas`
* `from matplotlib.figure import Figure`
* `import numpy as np`
* `import pandas as pd`
* `from sklearn.linear_model import LinearRegression`
* `from sklearn.preprocessing import PolynomialFeatures`
* `import matplotlib.patches as mpatches`
* `!pip install pywaffle`
* `from PIL import Image`
* `from wordcloud import WordCloud, STOPWORDS`
* `import seaborn as sns`
* `import folium`
* `from folium import plugins`
* `from mpl_toolkits.mplot3d import Axes3D`

## Structure:

### Part 1:
Part 1 covers the following concepts as seen in the attached Part 1 Notebook:-

* **Matplotlib History**
* **Matplotlib Architecture**
  * The Back-end layer
  * The Artist layer.
  * The Scripting layer.
* **Plotting with Matplotlib layers**
* **Exploring Matplotlib Styles**

#### Summary Part 1:
We have learnt the history of matplotlib, it was originally created as an ECOG visualization tool by John Hunter(1968–2012). We’ve also gone through the architecture of matplotlib. Comprising of the Back-end layer (FigureCanvas, Renderer, Event), the Artist layer (FigureArtist) made up of both primitive and composite objects and we also explored the Scripting layer, popularly known as the matplotlib.pyplot layer. We also plotted the Gaussian chart in both the Artist and Scripting layers, then we visualized the 26 plotting styles of matplotlib

#### Part 1 Blog-Post:
The blog post for part one of this project can be found here in The DataSeries publication on [Medium](https://medium.com/dataseries/mastering-matplotlib-part-1-a480109171e3). This article goes a long way to explain each code syntax and logic.


### Part 2:
Part 2 covers the matplotlib-pandas interactiobn via the **`plot()`** function. We see how easy it is to plot data from a pandas DataFrame using the **`plot()`** function.
Part 2 also covers the following:-

* **Exploring Matplotlib-Pandas**
  * Calling the plot() function on a DataFrmae to generate different plots
* **Basic Data Exploration with Pandas**
  * Computing summary Statistics
  * Exploring the index and columns
* **Cleaning Data in Pandas**
  * Understanding axis=0 and axis=1
  * Dropping unwanted columns
  * Renaming column headers
  * Converting column data types
  * Computing aggregations on columns.
  
#### Summary Part 2:**
We have seen how easy it is to call the **`plot()`** function on a pandas DataFrame to generate customisable plots. We also experienced the consistency of the matplotlib syntax,   both in generating and customizing plots. Next, we did some basic data exploration with pandas, by computing Statistical moments and exploring columns and index. Then we cleaned the data, dropped columns, renamed columns, changed data types and performed aggregations.

#### Part 2 Blog-Post:
The blog post for part two of this project can be found here in The DataSeries publication on [Medium](). This article goes a long way to explain each code syntax and logic.
  
### License:
This Repo and all its documents abide under the **MIT** License attached in the root directory.
