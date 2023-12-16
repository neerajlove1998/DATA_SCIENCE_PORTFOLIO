
## Flight Data Analysis

##### We have dataset contains information about US Flights data 2008, Contains data around 10,48,576.

###### Step-by-step process for flight data analysis

* Importing libraries needed

    Importing data by using to following Liabraries
    * import os
        ###### The "import os" statement is use for interacting with the operating system
          
    * import re
        ###### The "import re" statement is use for working with regular expressions

    * import numpy
        ###### The "import numpy" statement is use for numerical computing
     
    * import pandas
        ###### The "import pandas" statement is use for data manupulationa and analysis

    * import matplotlib
        ###### The "import matplotlib" stetement is use for creating visualisation

    * import seaborn
        ###### The "import seaborn" statement is use for creating statistical data visualization

* Loading dataset

     ###### Load the dataset using the pandas library.
  
* Data Overview

     ###### We provide the dimensions of the dataset (number of rows, number of columns).

* Data Cleaning

     * Handling missing values :
          ###### calculates the number of missing values for each variable and calculates the filling factor as a percentage. It then sorts the variables based on the filling factor in ascending order.
       
     * Date and Time Extraction
          ###### Convert separate year, month, and day columns into a single 'Date' column using the `pd.to_datetime()` function.
          ###### Function use to convert the 'HHMM' string to `datetime.time`
          ###### Function use to combines a date and time to produce a `datetime.datetime`
          ###### Function use to combine two columns of the dataframe to create a datetime format
       
* Descriptive and Exploratory Data Analysis

     * Carriers' Delay Profile
          ###### Extracting statistical parameters from a groupby object
          ###### Dataframe creation with statitical infos on each airline

     * Carriers' Delay Categorization (on time, small delay, large delay)
          ###### Using seaborn to visualize the distribution of delays for each airline.

![](https://github.com/neerajlove1998/Flight-Data-Analysis/blob/master/download.png)
