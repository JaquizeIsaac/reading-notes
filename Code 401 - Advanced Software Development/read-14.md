# Class 14 Reading Notes

> What are the key differences between Matplotlib, Seaborn, and Bokeh libraries in terms of their features and use cases? Provide an example of a specific visualization that is more suitable for each library.

    [Matplotlib](https://matplotlib.org/stable/tutorials/index): Features a low-level library for creating static, animated and interactive visualizations in Python. Use cases are customizable line graphs showing time-series data.

     [Seaborn](https://seaborn.pydata.org/tutorial.html): Built on top of Matplotlib, this provides a high-level interface for making your graph look cool. Use cases are heatmaps that show correlation between different feature of a dataset.

    [Bokeh](https://mybinder.org/v2/gh/bokeh/bokeh-notebooks/master?filepath=tutorial%2F00%20-%20Introduction%20and%20Setup.ipynb): Deisgned for creating interactive plots that can be embedded in web applications. That one interactive dashboard that your teach probably used online to show real-time data.

> In the Seaborn library, what are the main functions to create relational, categorical, and distribution plots? Briefly explain the purpose of each type of plot and provide an example use case.

    Relational Plots (sns.relplot()):

    Purpose: Show relationships between two numeric variables.
    Example: Scatter plot for analyzing the correlation between study hours and exam scores.
    Categorical Plots (sns.catplot()):

    Purpose: Visualize distribution of categorical data.
    Example: Box plot comparing total bills for different days of the week.
    Distribution Plots (sns.distplot()):

    Purpose: Visualize distribution of a single variable.
    Example: KDE plot showing the distribution of total bills.
    These functions help you explore and visualize data relationships, categorical distributions, and variable distributions in a concise manner.

> Discuss the role of the Seaborn Cheat Sheet in a Python developer’s workflow. What are some key sections or elements featured in the cheat sheet that can help a developer quickly reference Seaborn functionalities?

    The Seaborn Cheat Sheet serves as a quick reference for Python developers working with Seaborn. Key sections include:

    Relational Plots: Quick examples of scatter plots and line plots.
    Categorical Plots: Reference for box plots, violin plots, and swarm plots.
    Distribution Plots: Examples of histograms and kernel density estimates (KDE).
    Regression Plots: Quick guide for linear models and regression plots.
    Developers can swiftly reference these sections to implement common Seaborn functionalities, making the cheat sheet a valuable tool for efficient data visualization in Python.
