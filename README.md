# Reducers-and-Time-Series-Charts
In Earth Engine, you need to run reduction operation when creating composites, calculating statistics, doing regression analysis etc. The Earth Engine API comes with a large number of built-in reducer functions (such as ee.Reducer.sum(), ee.Reducer.histogram(), ee.Reducer.linearFit() etc.) that can perform a variety of statistical operations on input data. You can run reducers using the reduce() function. Earth Engine supports running reducers on all data structures that can hold multiple values, such as Images (reducers run on different bands), ImageCollection, FeatureCollection, List, Dictionary etc. 

To create a chart of average NDVI values for a given farm over 1 year. Earth Engine API comes with support for charting functions based on the Google Chart API. Here we use the ui.Chart.image.series() function to create a time-series chart.

 
![time series](https://github.com/user-attachments/assets/25933b2d-896e-4356-b031-b5e7f99c1778)
