## SF-crime-data-analysis-and-modeling

<a href="https://github.com/joshlingy/SF-crime-data-analysis-and-modeling/blob/master/SF crime data analysis and modeling.ipynb">Highly recommended to click this link to see more detail of what I have done about this project!</a>
** Please reload it if something went wrong on the page.**


<p align="center">
  <img src="https://github.com/joshlingy/SF-crime-data-analysis-and-modeling/blob/master/graphs/8-Clsuters.png">
  <img src="https://github.com/joshlingy/SF-crime-data-analysis-and-modeling/blob/master/graphs/12-Clsuters.png">
</p>

# Analysis: 
I use both dataframe and spark SQL to solve problems. The report analysis the SF crime report and get some information via OLAP like what is the top 3 most dangerous district then visualizing by using matplotlib. Visualization is one of the most important parts of the analysis because the report should be readable from people who have no data analysis background. The trend will be showing from the work and the police officers can get useful information to increase efficiency.

* SF crime(2003 to 2018) dataset with a size of over 500 million rows by descriptively exploring trends and information contained in the SF.

* Insights are drawn so that the analysis can help the SF government and police department develop tactics and adjust problematic measures to better control criminal activities.

* Larceny/Theft is the most criminal activities happened in 2003 - 2018.

* The district 'Southern' , 'Northern', 'Mission' are the three most dangerous districts.

* There are many crime activities on Sundays in the downtown area, I suggest visitors should avoid going there.
 
# Feature Engineering with Spark

To scale the feature engineering to a large dataset, the data was partitioned and automated feature engineering was run in parallel
using Apache Spark with PySpark. 

![](graphs/spark-logo-trademark.png)
