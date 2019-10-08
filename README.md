# Clean and analyze employee exit surveys
## Description
In this project we'll work with these two datasets containing the exit surveys from employees of the Department of Education, Training and Employment (DETE) and the Technical and Further Education (TAFE) institute in Queensland, Australia. These can be found here:
- [Department of Education, Training and Employment (DETE)](https://data.gov.au/dataset/ds-qld-fe96ff30-d157-4a81-851d-215f2a0fe26d/details?q=exit%20survey)
- [Technical and Further Education (TAFE)](https://data.gov.au/dataset/ds-qld-89970a3b-182b-41ea-aea2-6f9f17b5907e/details?q=exit%20survey)

The goal of this project is to answer the following questions:
- Are employees who only worked for the institutes for a short period of time resigning due to some kind of dissatisfaction? What about employees who have been there longer?
- Are younger employees resigning due to some kind of dissatisfaction? What about older employees?

We'll use different techniques to clean and transform the data contained in the datasets, including:
- Vectorized string methods to clean string columns
- The `apply()`, `map()`, and `applymap()` methods to transform data
- The `fillna()`, `dropna()`, and `drop()` methods to drop missing or unnecessary values
- The `melt()` function to reshape data
- The `concat()` and `merge()` functions to combine data