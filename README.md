# Churn-Analysis-for-bank-using-PowerBI
![png-transparent-south-indian-bank-bse-finance-bank-logo-india-bank-thumbnail](https://github.com/Nikitasuryawanshi/Churn-Analysis-for-bank-using-PowerBI/assets/105000370/76ec82c0-8d82-449b-89a9-cdc337e46a0e)
# Business Requirement Document

## Data Dictionary
###### RowNumber—corresponds to the record (row) number and has no effect on the output.
###### CustomerId—contains random values and has no effect on customer leaving the bank.
###### Surname—the surname of a customer has no impact on their decision to leave the bank.
###### CreditScore—can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.
##### Credit score:
##### Excellent: 800–850
##### Very Good: 740–799
##### Good: 670–739
##### Fair: 580–669
##### Poor: 300–579

###### Geography—a customer’s location can affect their decision to leave the bank.
###### Gender—it’s interesting to explore whether gender plays a role in a customer leaving the bank.
###### Age—this is certainly relevant, since older customers are less likely to leave their bank than younger ones.
###### Tenure—refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.
###### Balance—also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.
###### NumOfProducts—refers to the number of products that a customer has purchased through the bank. 
###### HasCrCard—denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank.
  ###### 1 represents credit card holder
  ######  0 represents non credit card holder
###### IsActiveMember—active customers are less likely to leave the bank.
  ######  1 represents Active Member
  ######  0 represents Inactive Member
###### Estimated Salary—as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.
###### Exited—whether or not the customer left the bank.
  ###### 0 represents Retain 
  ###### 1 represents Exit
######  Bank DOJ — date when the Customer associated/joined  with the bank.



## Data Gathering:

Please use the following data assets to pull the data related to Bank customer and associated details.
###### ActiveCustomer 
###### Bank_Churn
###### CreditCard
###### CustomerInfo
###### ExitCustomer
###### Gender
###### Geography

## Churn Analysis:
Analyse the data and bring out few insights on the customer Churn.
It is advantageous for banks to know what leads a client towards the decision to leave the company.
Churn prevention allows companies to develop loyalty programs and retention campaigns to keep as many customers as possible.


# Insights:
## insights:

##### 1.We have a total of 10,000 customers, with 5,151 active customers and 4,849 inactive customers,Out of the total customers, 7,055 are credit card holders, while 2,945 do not hold credit cards.There are 2,037 former customers, and 7,963 are returning customers.
##### 2. Total Total Customer was higher for Active Member (5151) than Inactive Member (4849). 2019 in ActiveCategory  made up 17.22% of Total Customer.
##### 3. Average Total Customer was higher for Active Member (1,287.75) than Inactive Member (1,212.25).Total Customer for Active Member and Inactive Member diverged the most when the year was 2019, when Active Member were 131 higher than Inactive Member.
##### 4.The number of exit customers for credit card holders (1,424) was higher than for non-credit card holders (613).In Fair, there were 685 exit customers, the highest among all categories, and this number was 435.16% higher than in the Excellent category, which had the lowest exit customer count at 128.
##### 5.Across all five credit types, the number of exit customers ranged from 128 to 685.Exit customers are divided by gender with 44.08% being female and 55.92% being male.

![Bank Analysis](https://github.com/Nikitasuryawanshi/Churn-Analysis-for-bank-using-PowerBI/assets/105000370/20f80494-764a-4300-af2c-947ed682fb83)

