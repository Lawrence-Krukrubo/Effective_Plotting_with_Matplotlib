# Effective_Visualization_with_Matplotlib:

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
  
#### Summary Part 2:
We have seen how easy it is to call the **`plot()`** function on a pandas DataFrame to generate customisable plots. We also experienced the consistency of the matplotlib syntax,   both in generating and customizing plots. Next, we did some basic data exploration with pandas, by computing Statistical moments and exploring columns and index. Then we cleaned the data, dropped columns, renamed columns, changed data types and performed aggregations.

#### Part 2 Blog-Post:
The blog post for part two of this project can be found here in The DataSeries publication on [Medium](https://medium.com/dataseries/mastering-matplotlib-part-2-a5114433fa0). This article goes a long way to explain each code syntax and logic.


### Part 3:
Part 3 covers intermediate pandas concepts such as boolean-indexing, filtering with key words, and criteria-based-selections. 
Let's itemise these concepts fro clarity.

* **Indexing and Slicing DataFrame Columns:**
  * Selection via the dot-notation
  * Selection via Square Brackets
  * Selection with Methods:
    * The **`filter()`** method
    * The **`select_stypes()`** method
* **Indexing and Slicing DataFrame Rows:** 
  * **`set_index()`** and **`reset_index()`** methods
  * Using **`.loc[]`** and **`.iloc[]`** indexers
  * Slicing Rows lazily
  * Slicing Rows Lexicographically
* **Slicing DataFrame Rows and Columns**
* **Selecting via Integers and Labels.**
* **Speeding up Scalar Selections:**
  * Comparing **`.iloc[]`** and **`.iat[]`** indexers
  * Comparing **`.loc[]`** and **`.at[]`** indexers
* **Boolean Selection:**
  * Filter based on some criteria
  * Multiple Boolean with square-brackets and Ampersand(&)
  * Multiple Boolean with square-brackets and Vertical-bar(|)
  * Multiple Boolean with np.logical conditions
* **Binning**

#### Summary Part 3:
The good news is with this solid knowledge of pandas, we’re more than ready to explore real live data and create astounding visual plots with matplotlib from next week.
We’ve extensively covered indexing and slicing DataFrame columns, rows and both together. We’ve learnt how to combine integer and label selections, how to speed-up scalar selection and even done good with boolean selection and binning.

#### Part 3 Blog-Post:
The blog post for part three of this project can be found here in The DataSeries publication on [Medium](https://medium.com/dataseries/mastering-matplotlib-part-3-371b7e52e116). This article goes a long way to explain each code syntax and logic.


### Part 4:
Part 4 covers intro to EDA with visual plots. We communicate data inferences using deep insights to the Line plots and Area plots.<br>
Finally, we explore the matplotlib colors and play with its 148 unique colors available.

* **Line Plots:**
  * When to use Line plots
  * Annotating plots with the **`plt.text()`** method
  * Plotting multiple Line plots in same axis
  * Do-it-Yourself Exercise on Line plots
* **Area Plots:** 
  * When to use Area plots
  * Using a fontdict with Area plots
  * Stacked Area plots
  * Unstacked Area plots
  * Adjusting transparency or alpha of Area plots
  * Comparing stacked vs Unstacked Area plots
  * Do-it-Yourself Exercise on Area plots
* **Matplotlib Colours**
* Counting the unique colours of Matplotlib
* Plotting charts with random unique colours

#### Summary Part 4:
In this part, we have covered both Line and Area plots. These are quite similar and may be used interchangeably. Line plots are awesome for displaying continuous data points over time. Area plots are awesome for displaying cumulative totals or percentages over time.

#### Part 4 Blog-Post:
The blog post for part four of this project can be found here in The DataSeries publication on [Medium](https://medium.com/dataseries/mastering-matplotlib-part-4-e59799ae407d). This article goes a long way to explain each code syntax and logic.


### Part 5:
Part 5 covers EDA with visual plots. We deep-dive into Stacked and Unstacked Area-Plots.<br>
Understanding their intricate details, styling and customization steps.

* **Histograms:**
  * What are Histograms?
  * When to use Histograms.
  * Do-it-Yourself problem exercises
* **Unstacked Histograms:** 
  * When to use Unstacked Histplots.
  * Using a fontdict with Histplots.
  * Adjusting transparency or alpha of Unstacked Histplots.
  * Do-it-Yourself problem exercises.
* **Stacked Histograms**
  * When to use Stacked Histplots.
  * Adjusting transparency or alpha of Stacked Histplots.
* **Customizing Histograms**
  * Customizing bins with **`np.histogram()`** function.
  * Adjusting x-ticks to align with bins.
  * Adjusting xlim to reset Histplots on the Canvas.
  * Changing colours and x-tick labels.
* **Interpreting Histograms**
  * Understanding the dynamics of each bar of the Unstacked Histplot.
  * Understanding the dynamics of each bar of the Stacked Histplot.
  * Understanding the markings on the y-axis
  * Understanding count and frequency distribution
    
#### Summary Part 5:
In this part, we have covered both Stacked and Unstacked Histplots. These may be used interchangeably, but a solid understanding of the internal properties of each is important to create visually appealing and communicative Histplots. Histplots are awesome for displaying the frequenvy distribution of numerical values and can distinctively display the split of frequencies among variables per bin.

#### Part 5 Blog-Post:
The blog post for part four of this project can be found here in The DataSeries publication on [Medium](https://medium.com/dataseries/mastering-matplotlib-part-5-2e7375e52f2b). This article goes a long way to explain each code syntax and logic.
 
### License:
This Repo and all its documents abide under the **MIT** License attached in the root directory.
