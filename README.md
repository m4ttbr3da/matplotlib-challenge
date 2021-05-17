# matplotlib-challenge
## Background

![Laboratory](Images/Laboratory.jpg)

Using raw data from a fictitious company's (Pymaceuticals) most recent animal study, I analyzed data of 249 mice identified with SCC tumor growth that were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of the study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. I utilized Matplotlib to generate tables and figures needed for the technical report of the study, and prepared a top-level summary of the study results.

## Step-by-step

In completing my analysis, I followed the below steps:

* Before beginning the analysis, I checked the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.

* Used the cleaned data for the remaining steps.

* Generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generated a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows  the number of total mice for each treatment regimen throughout the course of the study.

* Generated a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

* Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculated the quartiles and IQR and quantitatively determined if there were any potential outliers across all four treatment regimens.

* Using Matplotlib, generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlighted any potential outliers in the plot by changing their color and style.

  **Note**: Use this [Matplotlib documentation page](https://matplotlib.org/gallery/pyplots/boxplot_demo_pyplot.html#sphx-glr-gallery-pyplots-boxplot-demo-pyplot-py) for help with changing the style of the outliers.

* Selected a mouse that was treated with Capomulin and generated a line plot of tumor volume vs. time point for that mouse.

* Generated a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plotted the linear regression model on top of the previous scatter plot.

* Looked across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Included these observations at the top of notebook.
