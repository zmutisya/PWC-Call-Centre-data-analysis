### The Overview
This is a part of my virtual case experience on pwc call centre trends analysis offered by forage. The main objective of the analysis is to evaluate the call the center performance, efficiency and customer satisfaction. The extracted data is for period between 1/1/2021 and 31/3/2021.
## Tools used
* Pandas
* NumPy
* Tanleau
* 
## Exploratory Data Analysis (EDA)
The dataset has 5001 rows and the following 10 columns
* Call Id: Unique identifier for each call (object type).
* Agent: Name of the agent handling the call (object type).
* Date: Date of the call (object type).
* Time: Time of the call (object type).
* Topic: The topic of the call (object type).
* Answered (Y/N): Indicates whether the call was answered (object type).
* Resolved: Indicates whether the issue was resolved (object type).
* Speed of answer in seconds: Time taken to answer a call (float type).
* AvgTalkDuration: Duration of the call (object type, likely in "hh:mm:ss" format).
* Satisfaction rating: Customer satisfaction score (float type).
## The initial observation of the dataset
The column Call Id and Agent have the unique identifiers in the dataset.
There are no duplicates in the dataset.
![missing values](https://github.com/user-attachments/assets/56a1f794-9b9c-401c-9080-fa6ccbf8de6b)
* After the analysis the missing values are present in Speed of answer in seconds, AvgTalkDuration, and Satisfaction rating columns
* Object columns like AvgTalkDuration need to be converted to a suitable numeric or time-based format for analysis.
## Data cleaning
![datetime ](https://github.com/user-attachments/assets/e0985823-afe0-430c-ba41-cc294610675f)
Converted date and time to datetime types and AvgTalkDuration to seconds. This is necessary for effective data analysis
## Descriptive Data Analysis (DDA)
To summarize and describe the main features of the dataset, I conducted DDA to get total calls made to the call center which total to 4054
![Total calls](https://github.com/user-attachments/assets/5f055e2a-84fb-475e-b5d6-57dd0bbf5cff)
I also analysed the total number of unique callers at the call center to determine the total number of individual callers.
![unique callers](https://github.com/user-attachments/assets/fd071334-0b90-455e-ae73-46193e5f56a0)
## Performance metrics of the call center
The performance metric helped to measure the operational performance of the call center. To determine the operational performance I calculated total resolved calls which amount to 3646
![resolved calls](https://github.com/user-attachments/assets/31d3d212-ebf9-442d-b63b-7226f7a6815f)
I also calculated Call Resolution Rate for the call center which is 89.94%
![CRR](https://github.com/user-attachments/assets/8e2443d0-bd6d-4af1-9e92-4000408d4c2c)
Further I calculated the Total Abandoned calls where callers hung up before agents answered the calls. As a result of data cleaning the total abondoned calls totalled to 0
![abandoned calls](https://github.com/user-attachments/assets/4ef4d2b8-f05d-4dfd-a56a-9e8176e8cad1)
## Time based metrics
The time based metric analysis helped to provide insight into customer experience as well as the efficiency of the call center. To understand this I conducted average call duration which totalled to 224.92 seconds
![image](https://github.com/user-attachments/assets/60129845-3262-4aa4-973f-427ca2564e3e)
Average Hold Time for a single call which translated to 67.52 seconds
![image](https://github.com/user-attachments/assets/cb223aee-7615-42d7-b897-61e9d5286ca9)
SLA Adherence which measured the percentage of calls answered within the call center threshold of 90 seconds. This total to 0.70%
![image](https://github.com/user-attachments/assets/fef3ce8f-b45c-4a0b-85c1-73b8ca1fbce6)
Customer satifaction metric
This calculation helped calculate caller satisfaction which scored a mean of 3.4
![image](https://github.com/user-attachments/assets/0b9a6993-4add-4cf3-9d09-bfeb416f4a45)

## Dashboard visualization
To interact with the above insights [here](https://public.tableau.com/app/profile/zakayo.mutisya/viz/CallCenterOperationAnalysis/CallCenterOperationAnalysis)
![Call Center Operation Analysis (1)](https://github.com/user-attachments/assets/8c266040-dc42-499a-8aa7-c714d12fbd2d)


