# Prosper Data Exploration

## Dataset
This Loan Data dataset from Prosper contains 113,937 loans with 81 variables representing features such a borrower's monthly income, credit grade, debt to income ratio, available credit on bank card and many others.
Further elaboration on variables can be found at [Prosper API Definition Page](https://www.prosper.com/Downloads/Services/Documentation/ProsperAPI_Objects_Details.html).

## Summary of Findings
Four income range categories ($25,000-49,999,$50,000-74,999,$75,000-99,999,$100,000+) account 85% of the total number of loans and  ~92% of the volume of the loans borrowed. Therefore, the focus of this analysis was on these categories only.
Based on the data available, the main reasons members applied for a loan was debt consolidation, home improvement and business respectively except for members in income range of $25,000-49,999 that prioritized business over the other two.
Members who belong to a higher income range category apply for larger loans and though the general tendency, considering the whole dataset, is to favor a 36month term for repayment of loan, the loans on the higher end are re-paid in 60 months.
The motivation behind borrowing larger volumes of loans can be partly due to the fact that those in higher income range enjoy a better APR.
APR is impacted by features such as monthly income, debt to income ratio and available credit on banking card. Higher monthly income and available credit, lower debt to income ratio lead to better (lower) APR. Those in higher income range perform better in these areas.
Debt to Income Ratio appears to be a deciding factor wether a member receives an optimum APR. Monthly income and available credit further improve or worsen APR. However, the impact differ for different Credit Grades. While for members with good credit increase in monthly income does not contribute to better APR considerably and available credit is a more deciding contributor, for those with a rather low credit grade the increase in monthly income makes a visible impact on lowering APR.

## Key Insights for the Presentation

The presentation starts with introducing the majority groups that are four income range categories ($25,000-49,999,$50,000-74,999,$75,000-99,999,$100,000+). How big of the place they take up in the dataset in terms of number and volume. Further the distribution of a number of features (quantitative: Original Loan Amount, Stated Monthly Income, Available Bankcard Credit, Debt to Income Ration, Borrower APR categorical: Term, Credit Grade and Desired Loans) is presented.
Further on the relationship between Borrower APR and Original Loan Amount, Stated Monthly Income, Available Bankcard Credit, Debt to Income Ratio is shown (correlation heat map and scatterplots).
In the end the average volume of loans across income ranges and in different categories (Term, desired loans and credit grade) are presented. Moreover, the relationship between Borrower APR and Stated Monthly Income, Available Bankcard Credit, Debt to Income Ratio across income range and credit grade can be seen at the last step.
