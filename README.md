# Lending Club Case Study
> Lending Club is a lending platform that helps customers lend money at an interest rate based on banking standards. In this case study, we will analyze past lending data to make a data-driven decision before giving loans to customers who are highly likely to default (charge off). There are key factors that will help identify a potential defaulter.


## Table of Contents

* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

- The project is focused on EDA (Explaratory Data Analysis) skills. As a data scientist, what are you supposed to do with past data so that businesses can take data-driven decisions and improve their finances with an increase in profits and a reduction in losses?
The lending platform, when it receives an application for a loan, has to make a decision about whether to give the loan to the customer or not based on their profile. Potentially two risks are associated with the lending service decision:
    - If customer is likely to pay loan, but lending service decided to reject it's application. which incur a loss to the lending business as they lose the interest they can earn from lending a loan to a customer.
    - If a lending service decides to give a loan to a customer and the customer is likely to default or charge off, then the business has to bear the financial loss.
- The dataset is from a lending platform with 39717 rows and 111 columns.


## Conclusions

- Avoid Term loans for the tenure of 60 months.
- Avoid loans for small businesses with DTI > 11.50
- Avoid loans for debt consolidation with DTI  > 14.75
- Avoid loans which are not verified. Almost 44% of the loans are not verified. This could be a reason for the defaulters.
- Avoid loans with DTI > 13.5 and issued during the months April-July & Oct-Dec.
- Avoid loans issued for Home Ownership as MORTGAGE and DTI>14. 
- Avoid loans with type Grade C & DTI>14.
- Avoid loans with type Grade F with loan amount > 16K.
- Avoid loans with type Grade G with loan amount < 18K.
- Avoid loans when employment tenure is 7 years & annual income is [627K-938K].
- Avoid loans with state NE as they have highest Defaulted rate of loans


## Technologies Used

- Python - version 3.7
- Pandas - version 1.4
- Matplotlib - version 3.0
- Seaborn - version 0.12
- Numpy - version 1.24


## Acknowledgements

- [Matplotlib official documentation](https://matplotlib.org/stable/index.html)
- [Pandas official documentation](https://pandas.pydata.org/docs/)
- [Seaborn official documentation](https://seaborn.pydata.org/)
- [Numpy official documentation](https://numpy.org/doc/)
- Project based on EDA analysis
    - [Exploratory data analysis python](https://www.digitalocean.com/community/tutorials/exploratory-data-analysis-python).
    - [EDA - Step by Step Process](https://towardsdatascience.com/exploratory-data-analysis-in-python-a-step-by-step-process-d0dfa6bf94ee)
    - [Guide to EDA using python](https://www.analyticsvidhya.com/blog/2022/07/step-by-step-exploratory-data-analysis-eda-using-python/)

## Contact

Created by [@Vasista-Eranki, @gautamsbh] - feel free to contact us!
