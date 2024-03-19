LOAN DEFAULTER PYTHON PROJECT
About Dataset
This case study aims to give us an idea of applying EDA in a real business scenario. In this case study, apart from applying the techniques that we have learnt in the EDA module, we will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.

1.	Feature Selection 
2.	Feature Engineering 
3.	Missing value imputation 
4.	Binning 
5.	Variable Derivation 
6.	Variables segmentation 
7.	Data Exploration 
8.	Behaviour observation 
9.	Insight Derivation 
10.	Visualization

Data Analysis
1)	Object Datatype

1.	NAME_CONTRACT_TYPE- Most of the customers have taken cash loan customers who have taken cash loans are less likely to default

2.	CODE_GENDER – Most of the loans have been taken by female default rate for females are just ~7% which is safer and lesser than male

3.	NAME_TYPE_SUITE - Unaccompanied people had taken most of the loans and the default rate is ~8.5% which is still okay

4.	NAME_INCOME TYPE – The safest segments are working, commercial associates and pensioners

5.	NAME_EDUCATION_TYPE- Higher education is the safest segment to give the loan with a default rate of less than 5%

6.	NAME_FAMILY_STATUS- Married people are safe to target, default rate is 8%

7.	NAME_HOUSING_TYPE- People having house apartment are safe to give loan with default rate at 8%

8.	OCCUPATION_TYPE- Low skilled labours and driver are highest defaulter and accountancy are less defaulter core staff, mangers and Laboral are safe to target with default rate of less than 8% -10%

9.	WEEK_APPAR_PROCESS_START- Transport type 3 is highest defaulter, others, business entity type 3, self-employed are good to go with default rate of 10%

2)	Float64, int64

Univariate Numeric Variables Analysis
1.	Most of the loans were given for the goods price ranging between 0 to 1 ml
2.	Most of the loans were given for the credit amount of 0 to 1 ml
3.	Most of the customers are paying annuity of 0 to 50k
4.	Mostly the customers have income between 0 to 1 ml
Bivariate Analysis
1.	AMT_CREDIT and AMT_GOODS PRICE are linearly corelated, if the AMT_CREDIT increases the defaulters are decreasing
2.	People having income less than or equals to 1 ml, are more like to take loans out of which who are taking loan of less than 1.5 million, could turn out to be default we can target income below 1 million loan amounts greater than 1.5 million 
3.	People having children 1to 5 are safer to give loan 
4.	People who can pay annuity of 100k are more likely to get loan that upto less than 2 mill
Analysis on Merge data
1.	For repairing purpose customer applied previously and it also has the greatest number of cancelations.
2.	Most of applicant who were cancelled or refuse previously paid their loan in time 
3.	Previous offers which where unused have max number of default despite having high salary 

Recommendation
1)	Bank should target the customers –

1.	Having low income i.e. Below 1 ml
2.	Working in others, business entity types 3, self-employed org. Type
3.	Working as accountants, core staff, managers and laborers
4.	Having house/apartment and are married and having children not more than 5
5.	Highly educated
6.	Preferably female
7.	Unaccompanied people can be safer - default rate is ~8.5%

2)	Amount segment recommended -
1.	The credit amount should not be more than 1 ml
2.	Annuity can be made of 50k (depending on the eligibility)
3.	Income bracket could be below 1 ml
4.	80-90% of the customer who were prev. Cancelled/refused, are repairers. Bank can do the analysis and can consider to give loan to these segments
Precautions 
1.	Org. Transport type 3 should be avoided
2.	Low-skill labourers and drivers should be avoided
3.	Offers previously unused and high-income customer should be avoided 
