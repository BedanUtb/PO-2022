# PO-2022
# Advanced_programming
## Scenario
Company you work for is currently using the external company to generate a paycheck overview for whole fiscal year including all benefits, overtimes and even a meal benefit in cash. This al lis coming as a proffesional looking piece of paper per worker and the target is to motivate the employees using this. But – is costs company a bunch of money and time collecting the data for external supplier not mentioning the fact that sending these data including sensitive information is very risky these days.. So you decide to programme it and save your company money and time!


## Requirements
1. The progremm will generate the paycheck for all employees who are in company for whole fiscal year or longer (because there will be displayed some benefits which are directly conditioned by at least one year of employment)
2. The number of cash money given in meal cards will be counted
3. Employee should be able to see total number of benefits for whole year
5. Sick days are counted as well as mothers day and fathers day gift card value
6. Employees who are on maternity leave will not be counted
7. Output should be in word format as a number of documents (one document per employee)
8. Programme should be directly connetcted to the database so no direct input from HR is needed 


## Used Technologies
- Python
- Django framework
- SQL
- python-docx
- Microsoft SQL Management Studio


## Questions
- How will be sensitive data handled ? 
  - The sensitive data will be collected only in purpose to serve this document and after getting from the database will be encrypted in an csv file. After generating all files (around 900 pcs) the file will be deleted automatically. 
- Who will be able to see the output of program? 
  - Only the employees of HR who are incharge of paychecks. All proces will be secured and no other person from outside will get an opportunity to see what is not suposed to see. 
- Who will have access to the programm?
  - Only an administrator of the database who is also a programmer of this software. 
- How will be chechked / ensured that the data are correct?
  - There will be randomly selected 30 exaples which will be checked by HR and also the test function will be developed which will select the records with the most significant deviation


## Time plan
##### Eva Bedanova

Hours | #5 | #10 | #15 | #20 | #25 | #30 | #35 | #40 | #45 | #50 | #55
--- | --- | --- | --- |--- |--- |--- |--- |--- |--- |--- |---
Analysis | X | X | X | X |   |   |   |   |   |   |  
Design |   |   | X | X | X |   |   |   |   |   |  
Development |   |   |   | X | X | X | X | X | X | X |  
Testing |   |   |   |   |   |   |   | X | X | X | X
Deployment |   |   |   |   |   |   |   |   |   |   | X



