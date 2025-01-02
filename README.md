## The Overview
This is a part of my virtual case experience on pwc call centre trends analysis offered by forage. 
## Objective
The main objective of the analysis is to evaluate the call the center performance, efficiency and customer satisfaction. The extracted data is for period between 1/1/2021 and 31/3/2021.
## Tools 
* Python: Data cleaning, EDA and DDA
* Libraries: Pandas, NumPy, Matplotlib and Seaborn
* Tableau: Interactive visualization
## Data Collection
The data used in this project is extracted from Kaggle platform. Here is the [dataset](https://github.com/zmutisya/PWC-Call-Centre-data-analysis/blob/master/Call_Center_Dataset.csv) The dataset has 5001 rows and the following 10 columns
* Call Id: Unique identifier for each call.
* Agent: Name of the agent handling the call.
* Date: Date of the call.
* Time: Time of the call.
* Topic: The topic of the call.
* Answered (Y/N): Indicates whether the call was answered.
* Resolved: Indicates whether the issue was resolved.
* Speed of answer in seconds: Time taken to answer a call.
* AvgTalkDuration: Duration of the call.
* Satisfaction rating: Customer satisfaction score.
## Data Quality Check 
* Check for missing values
* Check for duplicates
* Check data types
Here is the [code](https://github.com/zmutisya/PWC-Call-Centre-data-analysis/blob/master/call_centre_metric_interpretation.ipynb)
My initial observation of the dataset is that;
* The column Call Id and Agent have the unique identifiers.
* There are no duplicates in the dataset.
* The dataset contains missing values in the three columns
    * Speed of answer in seconds
    * AvgTalkDuration
    * Satisfaction rating 
* AvgTalkDuration datatype need to be converted to a suitable numeric or time-based format for better analysis.
## Key Questions
* What is the Call Resolution Rate(CRR) once a call is received?
* What is the Average Call Duration(ACD) when the call is reveived?
* What is the Abondonment Rate before the call is received?
* What is the Average Hold Time(AHT) before the call is received by an agent?
* How well does the team adhere to the Service Level Agreement(SLA)?
* What is the Customer Satisfaction Rate (CSR)?  
## Exploratory Data Analysis(EDA) and Descriptive Data Analysis (DDA)
The key objective of the EDA and DDA is to understand the dataset structure, identify relationship among the key metrics and provide clear overview of the key metrics while answering the key questions. Here is the [code](https://github.com/zmutisya/PWC-Call-Centre-data-analysis/blob/master/call_centre_metric_interpretation.ipynb) for the EDA and DDA
## Tableau Dashboard
I have created a Tableau dashboard for the above analysis namely Call Center Operation Analysis to visualize and address the key questions. To interact with the above insights [here](https://public.tableau.com/app/profile/zakayo.mutisya/viz/CallCenterOperationAnalysis/CallCenterOperationAnalysis)
![Call Center Operation Analysis (1)](https://github.com/user-attachments/assets/8c266040-dc42-499a-8aa7-c714d12fbd2d)


