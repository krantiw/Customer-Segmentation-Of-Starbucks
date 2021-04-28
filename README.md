# Customer-Segmentation-Of-Starbucks
Using Supervised and Unsupervised learning


# Data Scientist Nanodegree
## Project: Data Scientist Capstone


--------
1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## 1. Installation <a name="installation"></a>

- Python versions 3.*.
- Python Libraries:
    - Pandas.
    - Scikit-learn.
    - numpy.
    - time.
    - matplotlib.
    - seaborn.

## 2. Project Motivation <a name="motivation"></a>
In this project, I will try to find how Starbucks customers use the app, and how well is the current offers system. I will also see who should the app target in promotions. The data sets used in this project contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. From it, we can understand the costumers' behavior and it might help us make better decisions.  
The problem we have here is that we don't want to give any customer our offers. We want to give only those who we think will be able to complete the offer. Giving an offer to someone we know he/she probably will not be able to complete it is a waste of time and resources that can be given to someone who we know will complete it. I will approach this problem by first cleaning up the data, then doing some exploratory analysis and see who are my most valuable customers after that I will create a model to help us predicting feature customers and which type of offer should we give them.  
My goal for this project is predicting which kind of offers, Buy One Get One Free (BOGO), Discount or informational is better to give a current customer by only knowing his/her age, gender, income and the amount they are paying.  

## 3. File Descriptions <a name="files"></a>  
There is one notebook file that have all the work related to the above questions. The data is not available but I showed the data frames and it have some of the data in it. Markdown cells were used to assist in walking through the thought process for individual steps.


## 4. Results <a name="results"></a>  
From that analysis I did in this project. I found out that most favorite type of offers are **Buy One Get One** (BOGO) offers and **Discount** offers. I digged deep to see who and what type of customers we have and noticed that **Females** tend to complete offers more than males with **56%** completion of the offers they received. Where **Males** completed only **43.18** from the offers they received. But our current data shows that we gave **males** more offers since they have more transactions than females with total number of **72794** transactions, where **females** only had **49382** transactions. In conclusion, the company should give more offers to **Females** than **Males** since they have more completed offers. And they should focus more on **BOGO** and **Discount** offers since they are the one that tend to make customers buy more.  
  
The main findings of the code can be found [here](https://alioh.github.io/DSND-Capstone-Project/).

## 5. Licensing, Authors, Acknowledgements<a name="licensing"></a>
The data was given by Starbucks and Udacity. Feel free to ask me anything about the code [@alioh](https://alioh.com)
