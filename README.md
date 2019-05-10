# US WildFires 1992 - 2015  

#### Final Project for MAT 400: Introduction to Statistical Machine Learning  

This project is using the [1.88 Million US Wildfires](https://www.kaggle.com/rtatman/188-million-us-wildfires) dataset from Kaggle. Using the size, time, and location of wildfire I am looking to train statistical models to predict the cause of the fire. There are 13 cause classes in the dataset, though two are removed since missing and unidentified are both classes, leaving 11 classes. This represents a multi-class classification problem lending itself to a tree and or boosting approach. After exploratory data analysis we fit a number of models, some of which provide decent results. In general the models are able to accurately predict fires from the more frequent classes, but struggle when making classifications on the less common.


#### Final Report
Since the dataset contained 1.88 million entries the runtime for the model fitting was *very* long. Since it took <10 minutes for the `Rmarkdown` document to `knit` we chose to write the report in a jupyter notebook since all of the code did not need to be run every time we render the document.   


[Link to the Jupyter Notebook](https://nbviewer.jupyter.org/github/andrewdnolan/US_WildFires/blob/master/FIRES_REPORT.ipynb)

The report was also exported as an html document which can be previewed here:

[Link to the HTML preview](http://htmlpreview.github.io/?https://github.com/andrewdnolan/US_WildFires/blob/master/FIRES_REPORT.html)
