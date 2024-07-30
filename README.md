
# Exploratory Data Analysis Using EXCEL TO FULFILL BUSINESS CASE
*This is a fictional project created to show my extensive skillset in data and business analysis.

## **Introduction**
 

This project is a detailed analysis of a customer service data set obtained from Kaggele(https://www.kaggle.com/datasets/suraj520/customer-support-ticket-dataset) with some motifications by me. This data set contains:
Customer Age: The age of the customer.
Customer Gender: The gender of the customer.
Product Purchased: The most recent tech product purchased by the customer.
Date of Purchase: The date when the product was purchased.
Ticket Type: The type of ticket (e.g., technical issue, billing inquiry, product inquiry).
Ticket Subject: The subject/topic of the ticket.
Ticket Description: The description of the customer's issue or inquiry.
Ticket Status: The status of the ticket (e.g., open, closed).
Resolution: The resolution or solution provided for closed tickets.
Ticket Priority: The priority level assigned to the ticket (e.g., low, medium, high, critical).
Ticket Channel: The channel through which the ticket was raised (e.g., email, phone, chat, social media).
First Response Time: The time taken to provide the first response to the customer.
Time to Resolution: The time taken to resolve the ticket.
Customer Satisfaction Rating: The customer's satisfaction rating for closed tickets (on a scale of 1 to 5).In this Excel dashboard, several conclusions can be made by toggling through different fields.


##Modifications 
All tickets were set to "closed" to simulate the correct environment for the business case. The null dates of the resolution were set to Saturday, June 3rd. This was done using the find and replace tool.  


<img src=C: "\Users\abrow\OneDrive\Pictures\Screenshots\Screenshot 2024-07-29 182745.png?
ezimgfmt=rs:600x600/rscb10/ng:webp/ngcb9">

Below I have answered several key questions asked of me by the project manager as well as laid out a detailed step-by-step snapshot of the data cleaning and visualization process. This dashboard is made solely to provide information to stakeholders to support the business case shown.  

<img src= "https://expertprogrammanagement.com/wp-content/uploads/2017/06/Project-Business-Case-Example.png?ezimgfmt=rs:600x600/rscb10/ng:webp/ngcb9">

## **Questions**

Here are the questions the project manager asked I answer:
1. What percentage of cases are resolved?
2. What percentage of cases are completed over the weekend costing the company more in overtime hours?
3. What percentage of sales were lost the following year for every customer who had an issue?
4. What is the average customer service rating based on the original inquiry?
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
