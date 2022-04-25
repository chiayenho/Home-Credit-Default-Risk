# Home-Credit-Default-Risk

Team members: Yu Chun Peng, Chien-Chu Hsu, Chia-Yen Ho, Devansh Bhasin

### Background & Context*
It has always been a challenging task for financial institutions to determine the financial strength of a potential customer to repay the loan amount within a defined time period. With the right approach, financial organizations can avoid losses and make huge profits.

Home Credit is an international non-bank financial institution, focusing on installment lending primarily to people with little or no credit history. Home Credit presented a Kaggle challenge to identify who is able to repay the loan based on loan application, demographic and historical credit behavior data, and other alternative data.


### Problem Statement
There are some people who don't have a specific credit history or even a bank account, but they need a loan for some reasons. However, without adequate credit history, it may be difficult for Home Credit to provide loans to these individuals, as these loans can be highly risky. In this case, some lenders even tend to exploit borrowers by demanding exorbitant interest rates, putting those borrowers in an unfair and dangerous situation.

Another scenario is when the loan applicant does have a credit history, but the records are scattered across different organizations, and reviewing this historical data can be time- consuming. Especially as the number of applicants increases, this will become a serious problem for Home Credit.

For these cases, we will try to build models to predict how capable each applicant is of repaying a loan, thus the process can be simplified and effective for both the Home Credit and applicants. This is a classification problem where the label is a binary variable. 0 represents the applicant will repay the loan on time, while 1 represents that the applicant will have difficulty repaying the loan.


**Our models and results**
- XGBoost.ipynb
- Catboost.ipynb
- Logistic+LightGBM.ipynb
- Blending Different Models.ipynb
- Best Submission.csv

**Write-up files**
- Presentation Slides.pdf
- Project Analysis Report.pdf

Dataset: https://www.kaggle.com/c/home-credit-default-risk/overview
