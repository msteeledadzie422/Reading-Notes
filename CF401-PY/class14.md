# Data Visualization

1. What are the key differences between Matplotlib, Seaborn, and Bokeh libraries in terms of their features and use cases? Provide an example of a specific visualization that is more suitable for each library.
      matplotlib is probably the single most used Python package for 2D-graphics. It provides both a very quick way to visualize data from Python and publication-quality figures in many formats.
    
      Seaborn is a library for making statistical graphics in Python. It builds on top of matplotlib and integrates closely with pandas data structures.
      Seaborn helps you explore and understand your data. Its plotting functions operate on dataframes and arrays containing whole datasets and internally perform the necessary semantic mapping and statistical aggregation to produce informative plots. Its dataset-oriented, declarative API lets you focus on what the different elements of your plots mean, rather than on the details of how to draw them.

      Bokeh is an interactive visualization library that targets modern web browsers for presentation. It is good for:
      * Interactive visualization in modern browsers
      * Standalone HTML documents, or server-backed apps
      * Expressive and versatile graphics
      * Large, dynamic or streaming data
      * Easy usage from python (or Scala, or R, or...)


2. In the Seaborn library, what are the main functions to create relational, categorical, and distribution plots? Briefly explain the purpose of each type of plot and provide an example use case.
      The seaborn function displot() supports several approaches to visualizing distributions. Seaborn also tries to promote techniques that are powerful but less familiar, such as calculating and plotting the empirical cumulative distribution function of the data.
      
      Several specialized plot types in seaborn are oriented towards visualizing categorical data. They can be accessed through catplot(). These plots offer different levels of granularity. At the finest level, you may wish to see every observation by drawing a “swarm” plot: a scatter plot that adjusts the positions of the points along the categorical axis so that they don’t overlap.
      
      Some seaborn functions combine multiple kinds of plots to quickly give informative summaries of a dataset. One, jointplot(), focuses on a single relationship. It plots the joint distribution between two variables along with each variable’s marginal distribution.


3. Discuss the role of the Seaborn Cheat Sheet in a Python developer’s workflow. What are some key sections or elements featured in the cheat sheet that can help a developer quickly reference Seaborn functionalities?
      The Seaborn cheatsheet would allow a developer to quickly reference a few ways they might be able to plot data, and to quickly implement that as desired. 

      I think the Figure Aesthetics and the Plot options (Categorical, Regression, Distribution, and Matrix) would be very helpful immediate reference points whenever it is necessary to briefly confirm something before implementation.
