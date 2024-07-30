
# Exploratory Data Analysis Using EXCEL TO FULFILL BUSINESS CASE
*This is a fictional project created to show my extensive skillset in data and business analysis.

## **Introduction**
 

This project is a detailed analysis of a customer service data set obtained from Kaggele.  In this Excel dashboard, several conclusions can be made by toggling through different fields. Below I have answered several key questions asked of me by the project manager as well as laid out a detailed step-by-step snapshot of the data cleaning and visualization process. This dashboard is made solely to provide information to stakeholders to support the business case shown below.  

<img src= "https://expertprogrammanagement.com/wp-content/uploads/2017/06/Project-Business-Case-Example.png?ezimgfmt=rs:600x600/rscb10/ng:webp/ngcb9">
## **Questions**
I went into this analysis with a few questions on the forefront.
1. What Countries are being represented?
2. What is the Gender breakdown of Respondents?
3. What programming languages are most common?
4. How popular is python overall?
5. What is the Work location distribution for Respondents?
6. How varied are the salaries versus experience?

## **Process**
I used Python Jupyter Notebook to load the data in csv format.  I then set out to systematically address all questions presented initially to gain some insigths from this survey data.  Using Pandas, I created a dataframe and made the display more user-friendly.  After formatting the data, I went back and created some visuals using seaborn and matplotlib.

<img src= "https://github.com/BrianHarrisCodes/Project/blob/main/Portfolio_Projects/2_Survey_EDA/images/age_bar.png">


## **Data Source**

The data was located here: [https://insights.stackoverflow.com/survey/](https://www.kaggle.com/datasets/suraj520/customer-support-ticket-dataset)

## **Conclusion**

Most of the respondents for the Survey were in the United States. I was curious as to how popular the Python coding language was and it was in the top five. There was a fairly even distribution between hybrid and remote work location. Much less were reporting in-person employment, but that is more common with developers. Some errors did present themselves when examining the compensation data in the survey.  I'm not sure if any limits were set but I did see several entries where it stated that the developers were receiving millions in US converted Currency. That would seem to be a topic to follow-up with the administrators responsible for the survey.


## **Acknowledgements**
Stackoverflow for making a robust survey dataset with minimal null value issues.


##### © Brian Harris 2023
