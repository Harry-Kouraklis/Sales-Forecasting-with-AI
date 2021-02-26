# Sales-Forecasting-with-AI
Walmart sales forecasting making use of the [FB Prophet](https://facebook.github.io/prophet/) algorithm. 

Dataset was provided by the Univerisy of Nicosia through the Kaggle ["M5 Forecasting"](https://www.kaggle.com/c/m5-forecasting-accuracy) competition. 

The data, covers stores in three US States (California, Texas, and Wisconsin) and includes item level, department, product categories, and store details. In addition, it has explanatory variables such as price, promotions, day of the week, and special events.

The Jupyter Notebook of this repo provides a detailed data analysis of all the above information while it makes use of the [FB Prophet](https://facebook.github.io/prophet/) algorithm that, taking into account its ease of use, appears to be a viable approach even in the most demanding forecasting challenges.

The algorithm was parallelized on 2 CPUs (on Google Colab) using the  [multiprocessing](https://docs.python.org/2/library/multiprocessing.html) package from Python.
