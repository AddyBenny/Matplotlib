# Matplotlib
05_matplotlib

In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.

The following analyses were performaned:

- I check the data for duplicate mice and removed any data associated with that mouse ID.
- summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
- A bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows  the number of mice per time point for each treatment regimen throughout the course of the study.
- A pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.
- The final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
- Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.
- A line plot of time point versus tumor volume for a single mouse treated with Capomulin.
- A scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.
- The correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.
- Three observations or inferences that can be made from the data.

Tools Used: Pandas, Numpy, Matplotlib, jupyter notebook.
