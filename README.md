# What will be my new recruit's salary?

The goal of this project is to build a model that would help predict salaries for a particular job/role based on known salary data. This dataset was scrapped from one of the job boards and is a quite simplified version of the real world job market.

The project is designed as such that with just a few tweaks it can also be used to implement a much more complex dataset. As we know how  data is growing at such a rapid rate, thus to make it scalable in future, the data has been hosted on AWS. 

The entire process has been automated starting from pulling the data from AWS cloud, implementing the model to storing the results and visualizing the key variables affecting the salary prediction. These key variables can then be used by the companies to decide on the compensation and salaries for the new hires.

## Technologies/Libraries used:
* AWS RedShift
* Pandas
* NumPy
* Psycopg2
* Seaborn
* Matplotlib
* Scikit-learn
* Lightgbm

## Models implemented:
* Ridge Regression
* Linear Regression
* Light Gradient Boosting
