## Module : Programming for Data Analysis GMIT

**

Student : Michelle Moran , G00387856

## **

Project : The Types of Feeding among Mothers in Ireland
**
**NB Points to note :

 - Jupyter notebook was used to create this project it contains live code, equations , and visualizations and text
 - In this notebook , I have had to import all packages in each code cell in order for it to output. Please take note of this. I have had a number of issues with packages and notebook. The anaconda package has been reinstalled a number of times.
 - All references for material used in this project are detailed in the main notebook "Project 2020  Feeding Choices and supports for Irish Mothers 2019 "

**
**

Description : 

Using the National Maternity Experience Survey  as a reference , I examined the results for the topic of Feeding among mothers in Ireland. This survey was completed by mothers :

 - Who gave birth in October/November 2019
 - Attended one of the 19 participating maternity hospitals, or home birth services
 - Women 16 years of age or older
 - Held a postal address in the Republic of Ireland

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

**
NB: The support variables data was based on a rating sytem marking from 1-5 , where 5 was positive .

Next I looked at creating my own data based on the survey results for each of my choosen variables and to investigate their likely distribution types.

The package used was Numpy.Random : Choice  where the probabilities of each variable was used to calculate the data for the variable, to be similar to the survey results. 

A combination of the matplotlib and seaborn packages are used to visualised the dataset , to investigate the relationships between the variables. 





