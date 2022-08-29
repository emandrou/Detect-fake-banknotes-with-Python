**SCENARIO**

You are a Data Analyst consultant in a company specializing in data. Your company has obtained a management service within the National Organization for the Fight against Counterfeiting (ONCFM).

This institution aims to put in place methods for identifying counterfeit euro banknotes. They therefore call on you, a data specialist, to set up a model that would be able to automatically identify the real ones from the counterfeits. And this simply from certain dimensions of the banknote and the elements that compose it.

Here are the ONCFM specifications:

    • length: the length of the ticket (in mm); 

    • height_left: the height of the ticket (measured on the left side, mm); 

    • height_right: the height of the ticket (measured on the right side, in mm); 

    • margin_up: the margin between the upper edge of the ticket and the image of this one (in mm); 

    • margin_low: the margin between the lower edge of the ticket and the image of this one (in mm); 

    • diagonal: the diagonal of the banknote (in mm).

**THE DATA**

You have access to this data, extracted directly from the company's database to CSV files. Here are the files at your disposal:

•	Billets

•	billets_production

**SKILLS ASSESSED**

•	Perform a linear regression

•	Perform a logistic regression

•	Perform predictive analysis

•	Operate automatic classifications to partition data

**YOUR MISSIONS**

*MISSION NO. 1*

•	Data Exploration

      o	Data preparation

      o	Data cleaning (Linear Regression to treat missing values)

•	a brief description of the data (univariate and bivariate analyses)

•	apply a classification algorithm, then analyse the result obtained:

      o	Supervised
      
          	Logistics Regression
          
          	K-NN
          
      o	Non - Supervised
      
          	K-Means

*MISSION NO. 2*

•	Counterfeit detection program: 

       o	Model the data using logistic regression. Thanks to this, you will create a program capable of making a prediction on a banknote, that is to say, to determine whether it is a real or a fake banknote. 
