# [Course : Data Analytics Visualization Lab (ADL601)](https://drive.google.com/file/d/161F1ADE5tG6hq_4epCpiciHqv8opUMfl/view?usp=drive_link)
Lab Instructor : [Lifna C S](mailto:lifna.cs@ves.ac.in)

## Lab Outcomes (LO's)
At the end of the course, students will be able to
1. Explore various data analytics Libraries in R and Python.
2. Implement various Regression techniques for prediction.
3. Build various time series models on a given data set.
4. Design Text Analytics Application on a given data set.
5. Implement visualization techniques to given data sets using R .
6. Implement visualization techniques to given data sets using Python.

## Lab Experiments
| No | Name of Experiment | LO's |
| :--: | ------------------ | :----: |
| 1. | [Getting introduced to data analytics libraries in Python and R](https://github.com/LifnaJos/ADL601-Data-Analytics-and-Visualization-Lab/blob/main/README.md#experiment---1-getting-introduced-to-data-analytics-libraries-in-python-and-r) | LO1 |
| 2. | [Simple Linear Regression in Python.](https://github.com/LifnaJos/ADL601-Data-Analytics-and-Visualization-Lab/blob/main/README.md#experiment---2-simple-linear-regression-in-python) | LO2 |
| 3. | Multiple Linear Regression in Python | LO2 |
| 4. | Time Series Analysis in Python | LO3 |
| 5. | Implementation of ARIMA model in python | LO3 |
| 6. | Implementation of Time series Decomposition and ACF and PACF | LO3 |
| $ 7. | Design Text Analytics Application on a given data set. | LO4 |
| 8. | Set Up a D3.js Environment, Select Elements in D3, Modify Elements in D3,Data Loading in D3 | LO5, LO6 |
| 9. | Create a World Map with d3.js |LO5, LO6 | 
| 10. | Event Handling with D3.js | LO5, LO6 |
| 11. | Two visualization experiments in python using different Libraries. | LO5, LO6 |

**Note** : $ - Newly added experiment to map LO4

## References
1. Data Analytics using R, Bharati Motwani, Wiley Publications
2. [Python for Data Analysis: 3rd Edition, WesMcKinney, Publisher(s): O'Reilly Media, Inc.](https://bedford-computing.co.uk/learning/wp-content/uploads/2015/10/Python-for-Data-Analysis.pdf)
3. Better Data Visualizations A Guide for Scholars, Researchers, and Wonks, Jonathan Schwabish, Columbia University Press

## Useful Links
1. [Three Things You C-an do to Make Your Data Tables More Visual By Jonathan Schwabish](https://cupblog.org/2021/03/16/three-things-you-can-do-to-make-your-data-tables-more-visual-by-jonathan-schwabish/)
2. [Five Charts You’ve Never Used but Should By Jonathan Schwabish](https://cupblog.org/2021/01/04/five-charts-youve-never-used-but-should-by-jonathan-schwabish/)
3. [https://www.geeksforgeeks.org/data-visualization-with-python](https://www.geeksforgeeks.org/data-visualization-with-python)
4. [https://www.coursera.org/specializations/data-science-python](https://www.coursera.org/specializations/data-science-python)
5. [https://www.geeksforgeeks.org/data-visualization-in-r/](https://www.geeksforgeeks.org/data-visualization-in-r/)
6. [https://towardsdatascience.com/introduction-to-arima-for-time-series-forecasting-](https://towardsdatascience.com/introduction-to-arima-for-time-series-forecasting-)

# Experiment - 1: Getting introduced to data analytics libraries in Python and R

* Lab Outcomes (LO): Explore various data analytics Libraries in R and Python. (LO1)

## Task to be performed :
1. Explore Top-5 Data Analytics Libraries in Python (w.r.t Features & Applications)
2. Explore Top-5 Data Analytics Libraries in R (w.r.t Features & Applications)
3. Install 2 Libraries each for Python and R
4. Perform simple experiments on the 2 identified libraries each for Python and R
5. Prepare a document with the Aim, Tasks performed, Program, Output, and Conclusion.

## Tools & Libraries to be explored
* Python Libraries: [TensorFlow](https://www.tensorflow.org/), [NumPy](https://numpy.org/), [SciPy](https://scipy.org/), [Pandas](https://pandas.pydata.org/), [Keras](https://keras.io/), [scikit-learn](https://scikit-learn.org/stable/), [PyTorch](https://pytorch.org/tutorials/beginner/pytorch_with_examples.html), [Scrapy](https://www.zenrows.com/blog/scrapy-python#parse-html-content), [BeautifulSoup](https://realpython.com/beautiful-soup-web-scraper-python/), [PyBrain](https://www.tutorialspoint.com/pybrain/pybrain_quick_guide.htm)

* R Libraries: [dplyr](https://www.listendata.com/2016/08/dplyr-tutorial.html), [tidyr](https://tidyr.tidyverse.org/), [readr](https://readr.tidyverse.org/), [stringr](https://cran.r-project.org/web/packages/stringr/vignettes/stringr.html), [ggplot2](https://r-statistics.co/Complete-Ggplot2-Tutorial-Part1-With-R-Code.html), [lubridate](https://cran.r-project.org/web/packages/lubridate/vignettes/lubridate.html), [jsonlite](https://cran.r-project.org/web/packages/jsonlite/vignettes/json-aaquickstart.html), [Shiny](https://shiny.posit.co/r/getstarted/shiny-basics/lesson1/index.html), [tseries](https://www.simplilearn.com/tutorials/data-science-tutorial/time-series-forecasting-in-r), [Prophet](https://medium.com/dropout-analytics/intro-to-prophet-r-7f650f86adc7)

## Outcome :
* Identified the Data Analytics Libraries in Python and R
* Performed simple experiments with these libraries in Python and R

# Online Resources
* [Top Python Libraries for Data Science - Simpli Learn](https://www.simplilearn.com/top-python-libraries-for-data-science-article)
* [Top Libraries in R for Data Science - Towards Data Science](https://towardsdatascience.com/top-r-libraries-for-data-science-9b24f658e243)

# Experiment - 2: Simple Linear Regression in Python
## Lab Outcomes (LO): 
* Implement various Regression techniques for prediction. (LO2)
## Task to be performed :
1. List the packages to be used for Simple Linear Regression in Python
2. Download the dataset from UCI Repository / Kaggle Dataset

   -- Load data into Google Colab

   -- Display the summary of the dataset
3. Check whether the data meets the assumptions

   -- Normality : Check whether the dependent variable follows a normal distribution

   -- Lineartiy : Check the relationship between the independent and dependent variable
4. Perform Linear Regression Analysis using the identified package
5. Visualize the results with a graph
-- Draw the Simple Linear Regression line to the plotted data
-- Add the equation for the Regression Line on the graph
6. Repeat the steps 2 to 5 using R libraries
7. Prepare a Colab Notebook with the Aim, Tasks performed, Program, Output, and Conclusion and upload the Notebook in your Github Repositiry.
8. Prepare a handwritten wrtieup with Aim, Theory and Conclusion.

## Tools & Libraries to be explored
* Python Libraries: scikit-learn, matplotlib, numpy, pandas
* R Libraries: lm, ggplot2, dplyr, broom, ggubr

## Theory to be written:
1. What is Linear Regression?
2. Write the equation for Simple Linear Regression.
3. Problem Statement : The iodine value (x) is the amount of iodine necessary to saturate a sample of 100 g of oil. Fit the simple linear regression model for the following data
   ![SLR_Problem](https://github.com/LifnaJos/ADL601-Data-Analytics-and-Visualization-Lab/blob/main/Experiments/SLR_Problem.png)

## Outcome :
* Understood the concept of Simple Linear Regression
* Explored the packages in Python and R
* Performed Simple Linear Regression using the Libraries in Python and R

# Online Resources
* [Linear Regression in Python](https://realpython.com/linear-regression-in-python/)
* [Linear Regression in R](https://www.scribbr.com/statistics/linear-regression-in-r/)
* [R packages for Regression](https://subscription.packtpub.com/book/data/9781788627306/1/ch01lvl1sec18/r-packages-for-regression)

# Experiment - 3: Multiple Linear Regression in Python
## Lab Outcomes (LO): 
* Implement various Regression techniques for prediction. (LO2)
## Task to be performed :
1. List the packages to be used for Multiple Linear Regression in Python
2. Download the dataset from UCI Repository / Kaggle

   -- Load data into Google Colab

   -- Display the summary of the dataset
3. Create a model and fit it
4. Get the values : Coefficient of Determination, Intercept and Coefficients
5. Predict the response
6. Visualize the results with a graph
-- Draw the Simple Linear Regression line to the plotted data
-- Add the equation for the Regression Line on the graph
7. Repeat the steps 2 to 6 using R libraries
8. Prepare a Colab Notebook with the Aim, Tasks performed, Program, Output, and Conclusion and upload the Notebook in your Github Repositiry.
9. Prepare a handwritten wrtieup with Aim, Theory and Conclusion.

## Tools & Libraries to be explored
* Python Libraries: scikit-learn, matplotlib, numpy, pandas
* R Libraries: lm, ggplot2, dplyr, broom, ggubr

## Theory to be written:
1. Why do we need to study Multiple Linear Regression?
2. Write the equation for Multiple Linear Regression.
3. Problem Statement : 

## Outcome :
* Understood the concept of Multiple Linear Regression
* Explored the packages in Python and R
* Performed Multiple Linear Regression using the Libraries in Python and R

# Online Resources
* [Multiple Linear Regression in Python](https://medium.com/machine-learning-with-python/multiple-linear-regression-implementation-in-python-2de9b303fc0c#id_token=eyJhbGciOiJSUzI1NiIsImtpZCI6Ijg1ZTU1MTA3NDY2YjdlMjk4MzYxOTljNThjNzU4MWY1YjkyM2JlNDQiLCJ0eXAiOiJKV1QifQ.eyJpc3MiOiJodHRwczovL2FjY291bnRzLmdvb2dsZS5jb20iLCJhenAiOiIyMTYyOTYwMzU4MzQtazFrNnFlMDYwczJ0cDJhMmphbTRsamRjbXMwMHN0dGcuYXBwcy5nb29nbGV1c2VyY29udGVudC5jb20iLCJhdWQiOiIyMTYyOTYwMzU4MzQtazFrNnFlMDYwczJ0cDJhMmphbTRsamRjbXMwMHN0dGcuYXBwcy5nb29nbGV1c2VyY29udGVudC5jb20iLCJzdWIiOiIxMTY5OTk1OTExNjUwODAzMTk4MTMiLCJoZCI6InZlcy5hYy5pbiIsImVtYWlsIjoibGlmbmEuY3NAdmVzLmFjLmluIiwiZW1haWxfdmVyaWZpZWQiOnRydWUsIm5iZiI6MTcwNjU4NTUxNiwibmFtZSI6IkxpZm5hIEMgUyIsInBpY3R1cmUiOiJodHRwczovL2xoMy5nb29nbGV1c2VyY29udGVudC5jb20vYS9BQ2c4b2NLbTgzQUMxckdISjg3NFk0eWpCb0NPWGlETjNqVVBBdGVDLU1iWUpaX29vWHc9czk2LWMiLCJnaXZlbl9uYW1lIjoiTGlmbmEiLCJmYW1pbHlfbmFtZSI6IkMgUyIsImxvY2FsZSI6ImVuIiwiaWF0IjoxNzA2NTg1ODE2LCJleHAiOjE3MDY1ODk0MTYsImp0aSI6IjE4ZWFlYWEzOGUxOTM5NjQ3ZjRlZjQ1Njg1OTlkNjc1MmFhMDYxNTEifQ.xbvxkBvYaEsuP4xpkNN20LbuBgapMr-vEO71c0bXGetEgN6eXY21QaqPjgkL1zdvYoSM71QVs_wPm79KqgQYaIp_qRcvE9X6GbeY9GPEZb_FiADPSPB2uN8Nf_hALprH0kuP-zBhn0KDBJL3eP16cyrVYg668zeN953QdRXsTkiF-7_SZ08GeiJmKfeQ_p5s2TN-4-kCS3JzPiFMAsuojhz4VJxbPfzMnMgU2eU_rTojmMfD6eTvcDvUrzq_LVL7eDnIvQM9bUW_jt49wcWnBtmXZM4ZpzsmOaQCINDAtsxycv16z4dJO93fclU_YTkMwdUjShGO7uKKINqNbKPK5w)
* [Multiple Linear Regression in Python](https://www.geeksforgeeks.org/ml-multiple-linear-regression-using-python/)
* [Multiple Linear Regression in R](https://www.datacamp.com/tutorial/multiple-linear-regression-r-tutorial)
* [R packages for Regression](https://subscription.packtpub.com/book/data/9781788627306/1/ch01lvl1sec18/r-packages-for-regression3)

## Acknowledgements
* This material was prepared as a part of the Course - **Data Analytics and Visualization Lab** offered by the  Department of Artificial Intelligence & Data Science, (VES Institute of Technology - An Autonomous Institute, Affiliated with the University of Mumbai) to the Third Year Artificial Intelligence & Data Science Students.
