# Lending Club Case Study
**Problem Statement:**
You work for a consumer finance company which specialises in lending various types of loans to urban customers.

When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

**Analysis:**
1. Grade B has very high defaulter count. 
This could indicate borrowers with average credit scores 
So borrowers with this grade should be assessed properly before approving their loan.

2. Short term loans  ( 36 months) have more defaulters.
Company should encourage borrowers to take long term loans and educate them about this.

3. Borrowers who have been employed for more than 10 years contribute to most number of defaulters.
Higher employment length should not be given a lot of weightage when approving loans.

4. Year 2011 has the maximum defaulters indicating recessions.
Any recession / financial challenges in a year should be predicted the company.
Stricter regulations should be implemented in such years for approving a loan.

5. Quarter 4 and December month has the maximum defaulters.
This could indicate more financial burdens and holiday spending.
Company should assess any loans approved more carefully in Q4

6. Borrowers with annual income b/w 20000 and 60000 form the most number of defaulters.
 So, the company should prioritise people with more income when providing loans to avoid risk.

7. People with very high debt-to-income form the highest number of defaulters. 
There should be stricter cut off of dti ratio of the borrowers.

8. Surprisingly, lower loan amounts form highest % of defaulters.
 Generally, smaller loans are provided to people with lower credit score, which could be a reason for the loan not getting paid.
Borrower’s credit score should be assessed carefully and financial education should be provided.

9. Loans with a monthly installment of less than 200 USD have the most defaulters. 
This could again indicate lower credit score borrowers and verify the above point.

10. Higher loan amounts tend to have worse grade which can imply bad credit scores, high-risk browser profile. 
So the company should carefully assess lending high amount to borrowers with bad LC grade.

11. Higher loan amounts have more counts and are verified more. 
This could explain more verified defaulters ass higher loans tend to be riskier and  are verified easily by the company. Stricter regulations need to be implements for higher loan amounts

12. Higher interest rates are for larger term ( 60 months) and have worse LC grade.
Bad LC grade should be considered as an important factor when approving loans.

13. There are borrowers with annual income lower than 60000, taking loans of 30000 or more which is risky and must be assessed
Stricter cut offs should be applied on loan amounts based on the annual income of borrowers.

14. As the loan amount increases, interest rate increases, but the most number of defaulters have extremely low loan amount. 
This could indicate defaulters with very low credit scores.
Credit score should be considered an important factor.

15. For good grade i.e A, there are more non verified defaulters than verified ones, but for remaining ones the number of verified defaulters is more than that of non verified.
Verification should not be considered an important factor for bad LC grade borrowers.

16. Loan amount and annual income also have a positive correlation but its less than 0.5 which is a concern
Stricter cut offs for loan amount needs to be implemented


