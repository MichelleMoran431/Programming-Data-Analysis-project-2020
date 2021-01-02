## Module : Programming for Data Analysis GMIT



**Student : Michelle Moran , G00387856

**Files included : 

Project notebook : Project 2020 Feeding Choices and Supports for Irish Mothers 2019.ipynb

 - reference material - National Maternity Experience Survey results.pdf
  




## **Project 2020  Feeding Choices and supports for Irish Mothers 2019 


### NB Points to note :

 - Jupyter notebook was used to create this project it contains live code, equations , and visualizations and text
 - In this notebook , I have had to import all packages in each code cell in order for it to output. Please take note of this. I have had a number of issues with packages and notebook. The anaconda package has been reinstalled a number of times.
 - All references for material used in this project are detailed in the main notebook "Project 2020  Feeding Choices and supports for Irish Mothers 2019 "


### Problem Statement ( see reference file PROGDA PRoject(2).pdf)

#### 1. Choose a real-world phenomenon that can be measu are and for which you could collect at least one-hundred data points across at lease different variables


Using the National Maternity Experience Survey  as a reference , I examined the results for the topic of Feeding among mothers in Ireland. This survey was completed by over 6000  mothers :

 - Who gave birth in October/November 2019
 - Attended one of the 19 participating maternity hospitals, or home birth services
 - Women 16 years of age or older
 - Held a postal address in the Republic of Ireland
 
 I collected 500 data points across different measureable variables i.e I took 500 mothers from different ages and hospitals.
 
 #### 2. Investigate the types of variables involved, their likely distributions and their relationships with each other

From these results , I stimulated my own dataset looking at 500 random mothers , specifically looking at the types of feeding choosen and the supports given to the mother both at home and in hospital. To see if there was a relationship between them.

The following are the variables examined : 

 1. AgeProfile -20,25,30,35,40
 2. Ethnicity - 
 NB: 1- White Irish ,2- Roma, 3- African, 4 - Chinese, 5- Arabic, 6- Asian, 7 - Mixed , 8 - Other
 4. FeedingChoices  - 
    NB: 1- Breast,  2- Combined , 3- Artifical
 5. Hospitals - 19 participating
 6. Hospital FeedingSupport
 7. Home FeedingSupport
 8. Breastfeeding6months

**NB: The support variables data was based on a rating sytem marking from 1-5 , where 5 was positive .


#### 3. Synthesise/simulate a dataset as closely matching their properties as possible 

Next I looked at creating my own data based on the survey results for each of my choosen variables and to investigate their likely distribution types.

Packages used : 

Numpy.Random : Choice  where the probabilities of each variable was used to generate the data for the variable and to try to be similar to the survey results.
NP.Random generates arrays of pseudo-random numbers. A Random Seed was use to ensure the same set of data was outputed everytime the code was ran.

A combination of the matplotlib and seaborn packages are used to visualised the dataset , to investigate the relationships between the variables. using the following plots :

1. displots - Facetting histograms by subsets of data
2. Density plots - looking at the distribution of numeric variables. using Kernel density estimate to show the probability density function of the variable.

Variable relationships representation visually : 

1. AgeProfile vs Feeding Choices
2. HospitalFeedingSupport vs Feeding Choices
3. Relationship between Hospital FeedingSupport /Feeding Choices/Age Profile
4. Relationship between Home FeedingSupport /Feeding Choices and AgeProfile
5. HomeFeedingSupport vs Feeding Choices
6. HomeFeedingSupport vs Breastfeeding6months
7. Ethnicity vs FeedingChoices
8. Examining the co-relations between the variables - using heatmap






