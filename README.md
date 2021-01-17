
### This is for Udacity project reviewer:

I submitted my Github Repo, But I could not submit my BlogPost via the system. The below url is the link for my BlogPost in Medium:

https://jgolizadeh.medium.com/airbnb-properties-in-seattle-c281518c8b5b

Thanks

# AirBnB_Seattle_DataAnalysis

This project aims to analyse data provided by AirBnB website for the city of Seattle in USA. It can also be used to analyse data from other cities on AirBnB website. 

### Motivation
we use the **CRISP-DM process(Cross Industry Standard Process for Data Mining)**  to answer the questions asked about the AirBnB data which can be used for their data analysis. 

### Libraries
There are several questions asked in the notebook file and they are answered step by step using different libraries such as Matplotlib visualizations,seaborn, Pandas dataFrames and sklean(scikit-learn) library.

### Models
There are 2 models used for prediciting price of the properties using sklearn library. they are

1. Ridge Regression
2. RandomForest Regresser

### Results
We have provided almost 60% r-squared score for test data and 90% score for training data. they can be improved by providing more data for prediction(larger data)as the 
number of columns used for predicition are high after we make categorical variables dummies. 

The notebook file Data_Analysis_airbnb contains all the python code for analysis. we have also provided the three data files listings,calendar and reviews on the repository. 

### Business Questions
In the code we have trided to answer the following questions:

1. What features most influence on the price of the properties?

2. How many properties are available during the Year? How prices change during the calendar period?

3. which streets in Seattle host more guests than other streets? What is the average price of these popular streets? 


### Conclusion

There are lots of other questions which can be answered using this data and also improve our prediction...
The listings data is used for predicting the price of the properties, but our test and train data predictions do not match and we think that because of the large columns (~1700 columns), the number of the rows(the size of the data) should be much bigger in order to get better predictions. 

### Acknowledgement

Many Thanks to **Udacity** for providing me this opportunity to work on this data and all the support.

This project is open for public and I appreciate any comments and any developments that can help to provide better results from analysing the data. 


