# Project1
Student Loan Debt Analysis 2020-2021

## Description
This project provides an in-depth analysis of student loan debt in the U.S. for the academic year 2020-2021. Using data from Kaggle, we explore trends in loan amounts, recipients, distribution by school type, and geographic distribution.

## Data Resources
### Kaggle
https://www.kaggle.com/datasets/thedevastator/the-schools-that-create-the-most-student-debt
This tab provides assumptions and definitions for the Loan Volume Reports.

Data Source:Â Common Origination and Disbursement (COD) System
Data Refresh Schedule:Â Data will be refreshed each quarter for at least seven prior quarters to account for adjustments. After the adjustment period, the data will be final.

Assumptions
1. Loans are included in the columns RECIPIENTS, # OF LOANS ORIGINATED, $ OF LOANS ORIGINATED, # OF DISBURSEMENTS, and $ OF DISBURSEMENTS if the period begins date of the loan falls within the award year reported on the spreadsheet and the first disbursement of that loan falls within that quarter. Disbursements occurring prior to the award year are counted in quarter 1 and disbursements occurring after the end of the award year are counted in quarter 4. For the Year-To-Date data, all numbers are cumulative.
2. Disbursements are included in the columns # OF DISBURSEMENTS and $ OF DISBURSEMENTS if the loan was included in the loan origination counts and the dates of the disbursements were less than or equal to the last day of the quarter reported on this spreadsheet. For fourth quarter reports it is the cumulative number of disbursements as of the date the report is created in order to include any late disbursements. Disbursements for the second, third, and fourth quarters are cumulative from the beginning of the award year.
3. Consolidation loans are not included in either query
4. A school appears on the report only if at least one loan originated at that school qualifies for inclusion on the report.
5. Loans with a current loan status of canceled are excluded from both queries.
6. Disbursements in history with an amount of zero are not counted in the number of disbursements.

Field Name:

OPE ID

School

State

Zip Code

School Type

Recipients

"# of Loans Originated"

"$ of Loans Originated"

"# of Loans Disbursed"

"$ of Loans Disbursed"

### US Zip Codes Database
https://simplemaps.com/data/us-zips

### U.S. Regions

https://www2.census.gov/geo/pdfs/maps-data/maps/reference/us_regdiv.pdf

### API
geoapify



## Example of Findings

![image](https://github.com/wemlaztdj/Project1/assets/19890554/146e98cc-bb7b-4809-911f-ae1d9ba7eb53)


![image](https://github.com/wemlaztdj/Project1/assets/19890554/236ea933-e22d-4623-948d-dd00b8ad54e4)


## Installation

1. Clone this repository.
2. Install required libraries using `pip install -r requirements.txt`.
```bash
pip install -r requirements.txt
```
## Contributing

Tianxiao Cao

Peter Gruskin

Mu Li

Michael Roberts


