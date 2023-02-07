**GLOBAL LAY_OFF**

Globally, tech companies are battling the recession. Consumer spending is slowing down, central banks are raising interest rates, and the foreign exchange rate is strong, all of which point to a potential recession, and IT companies have already begun to lay off staff. Due to the current economic downturn, Meta laid off 13% of its staff or more than 11,000 workers. Upon completion of my data alaysis training, this dataset from Kaggle.com was choosen to analysis using Microsoft Excel.

**CONCERNING THE DATASET**

The dataset, a Comma Separated Format (CSV) file retrieved from Kaggle (https://www.kaggle.com/datasets/swaptr/layoffs-2022) covers layoffs of workers across numerous businesses from COVID-19 until the present. The dataset has nine columns: business name of the firm, location of the layoff, industry of the firm, total number of workers laid off), percentage laid off of employees, date of the layoff, stages of funding), Country, and funds raised by the firms.

 ![Screenshot (238)](https://user-images.githubusercontent.com/124578882/217106406-fb7f3f3c-a7ab-474f-9a03-1b5c859bd6ce.png)

**ESSENTIALS OF DATA CLEANING**

Businesses that desire to dominate their markets must understand where to obtain the data they want and how it all relates. However, they must ensure that their data sets are clean before beginning to analyze data. Data cleansing is undoubtedly important, and smart businesses are aware of this. Large amounts of data, sometimes stored in hard-to-use forms, are typically included in datasets. Data analysts must first ensure that the data is adequately equipped and follows the established set of criteria. The greatest problems are data scarcity and inconsistent formatting, and data cleaning addresses these issues. Data cleaning is the process of locating faulty, incomplete, inaccurate, or irrelevant data, fixing the flaws, and ensuring that any future instances of these problems will be automatically corrected. Data analysts spend 60% of their time organizing and cleaning up data, according to Appen!

Here are a few of the most popular stages and techniques for data cleaning:
•	Dealing with missing data
•	Standardizing the process
•	Validating data accuracy
•	Removing duplicate data
•	Handling structural errors
•	Getting rid of unwanted observations

Some stepes taken by me to clean this dataset
Firstly, I alighted all using Ctrl+A and converting the dataset to a table format using Ctrl+T and formatting the table.

![Screenshot (239)](https://user-images.githubusercontent.com/124578882/217318580-2097c967-d7cd-4288-83b7-df02c89b74f1.png)

-Arraigning the industry(firms) in ascending order


-Removing duplicate values


-Change data type for Percentage laid_off to percentage format


-Inserting some columns named Total b4 layoff, Total after layoff, Year, Month, Day, Month which =IFERROR (D2/E2, 0); =IFERROR(J2-D2,0); =YEAR(F2); =MONTH(F2); =DAY(F2); also using the IFS function  on Microsoft excel respectively on the table


-Changing the data type of funds raised from general to Currency format after which I summarized the table to pivot table.



**DATA VISUALIZATION**

There are about 245,117 personnel who were laid off from 1,489 companies, across 55 different countries, amongst 28 industries. Below are few visualizations;


**Top 10 industries by fund raised**


A column chart indicates the top 10 industries by fund raised. The media industry takes the lead with $501,984B while the transportation, Consumer, Real Estate, Finance, Food, Retail, Healthcare Travel, and others takes 256,593; 117,853; 96,859; 88,7541; 79881; 49,195; 39,859; 28572; 23,975 in Billion dollars respectively.
 
![Screenshot (243)](https://user-images.githubusercontent.com/124578882/217312498-3445779c-aca2-4bba-8a7c-b190f31ca7f8.png)



**ANNUNAL FUND RAISED**

Even though there were much more firm layoffs in 2022 than in previous years, 74% of the total funds were raised.

![Screenshot (244)](https://user-images.githubusercontent.com/124578882/217312717-c37637fd-2b5e-4331-a420-1e61a9e2fe77.png)


**Top Companies** 


Out of One thousand four hundred and eighty-nine (1489), Netflix, Meta, Uber, Tesla and Tencent are the top five (5) companies

![245](https://user-images.githubusercontent.com/124578882/217313148-9c80d0fc-6476-46e9-a067-369f45633389.PNG)


**COMPANY’S STAGE LAY-OFF**


As known that every individual, organization and companies are all in stages. Companies can be classified into different stages such Acquired, IPO, Private Equity, Seed, Series A, B, C, D, E, F, G, H, I, J while company’s stage wasn’t captured in the dataset. Below is a chart showing the top five (5) stages of companies by lay-off.

![247](https://user-images.githubusercontent.com/124578882/217313819-3ae22e8c-2745-4f96-baea-c91848f67fcc.png)


**Initial Public Offering (IPO) Funding Stage:** The procedure for launching a first-ever public offering of corporation shares.

**Series C:** Firms look for more investment to enable them to develop new products, enter new markets, or even purchase other successful startups.

**Series D:** are often financed by venture capital companies. Due in large part to the fact that so few firms make it to this point, the amount raised and valuations vary greatly.


A draft of the dashboard 
![Screenshot (247)](https://user-images.githubusercontent.com/124578882/217316548-ce63f8d0-4a70-4398-981d-bc4787204c66.png)

Finally, on this dashboard, all the data can be seen at a glance. Since this is my first project involving data analysis, I would really appreciate feedback and suggestions from professionals.


![Screenshot (248)](https://user-images.githubusercontent.com/124578882/217316719-1034e847-916e-4954-9ba0-2b085cd6215a.png)


**In conclution** 

After carefully evaluating the provided dataset and having a thorough understanding of the conditions, it was discovered that the United States of America, which has the most companies and industries, is also leading other companies in terms of layoffs.
