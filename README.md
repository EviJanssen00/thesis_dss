# Enhancing Employee Attrition Prediction 

This research has been developed for the partial fulfillment for the requirements for the MSc Data Science and Society at Tilburg University.
The study focuses on enhancing exisiting research on employee attrition prediction through the introduction of a new dataset with novel features.
Due to the sensitive nature of employee records, raw data and exploratory data analysis (EDA) results cannot be publicly shared. The features used in this study are described in the section below.

In *models* notebook the code for six ML models (DT, RF, GBM, XGBoost, CatBoost, LGBM) is developed for the baseline model (excluding novel features) and the extended model (including novel features).
In *error_analysis_agegroup* notebook a more detailed analysis of model performance controlled for AgeGroup is performed. 

---
## Features

Below is a list of the features in this dataset and their descriptions. 

### Novel Features
- **NumContractTypeChanges**: Total number of contract type changes over the employment period.
- **NumFunctionChanges**: Total number of function changes over the employment period.
- **NumLocationChanges**: Total number of location changes over the employment period.
- **NumOrganisationPartChanges**: Total number of organization part changes over the employment period.
- **SalaryIncreasesCount**: Total number of salary increases over the employment period.
- **YearsCurrentContractType**: Number of years in the current contract type.
- **YearsCurrentDepartment**: Number of years in the current department.
- **YearsCurrentFunction**: Number of years in the current function.
- **YearsCurrentLocation**: Number of years in the current location.
- **YearsCurrentOrganisationPart**: Number of years in the current organization part.

### Other Features
| **Feature Name**                 | **Description**                                                                 |
|-----------------------------------|---------------------------------------------------------------------------------|
| **AgeGroup**                     | Age group (11 categories: under 20, 20-24, 25-29, 30-34, 35-39, 40-44, 45-49, 50-54, 55-59, 60-64, 65+). |
| **Attrition**                    | Target feature indicating whether an employee has left the company (Yes/No).    |
| **CompanySize**                  | Size of the company based on number of employees (7 categories).                |
| **ContractType**                 | Type of contract (2 categories: Fixed Term, Indefinite Term).                   |
| **Country**                      | Country of residence of the employee (35 categories).                          |
| **Department**                   | Department where the employee works (22 categories).                           |
| **EmployeeType**                 | Type of employee (Regular, Intern, On-call).                                   |
| **FunctionLevel**                | Level of seniority (9 categories: Intern, Flex worker, Junior, General Level, Medior, Senior, Lead or Supervisor, Manager, Partner and C-level). |
| **Gender**                       | Gender of the employee (Male/Female).                                          |
| **Generation**                   | Employee's generation (6 categories: Generation Z, Generation Y, Pragmatic Generation, Generation X, Protest Generation, Silent Generation). |
| **Industry**                     | Industry in which the company operates (12 categories).                        |
| **ManualLabor**                  | Indicates if the job involves manual labor (Yes/No).                           |
| **MaritalStatus**                | Marital status (6 categories: Divorced, Living Together, Married, Registered Partnership, Unmarried, Widowed). |
| **MonthlySalary**                | Monthly salary based on work hours.                                            |
| **MonthsCurrentSalary**          | Number of months in current salary.                                            |
| **WorkHours**                    | Work hours per week according to the contract.                                 |
| **YearDateService**              | Starting year of the employment period.                                        |
| **YearsInService**               | Number of years in service.                                                    |
| **ZeroHourContract**             | Indicates whether the contract is a zero-hour contract (0/1).                  |

---
