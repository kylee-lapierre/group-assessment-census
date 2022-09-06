# 2019 Company Survey Data and Statistics

Companies record and hold lots of data that can give us an insight into how some companies run, the overall demographics of companies, as well as what technologies they may use. This project reviews and attempts to answer questions brought about from the 2019 Company survey hosted and provided by the United States census Bureau. We will look into relationships between sex, ethnicity, company revenue, and employee counts at firms across the U.S., minority ownership within different industries, different firm sectors by counts of company owners, as well as technology characteristics of companies.

This project was led by Alistair Marsden, Erick Sanmartin, Jerad Ipsen, and Kylee LaPierre.

## Questions
-	Does race or sex of business owners have a relationship with that business’s size, revenue, ownership structure, or access to technology?
-	What race demographics are prevalent in specific industries?
-	Does an owner’s racial and gender composition have a bearing on the number of owners a business has?
-	Is company access to certain technologies is related to their revenue or size, does gender within the industry has an impact on production factors; and is there a correlation between a company’s size, industry, and revenue?

## Data Sets

https://www.census.gov/data/developers/data-sets/abs.2019.html, the U.S. census Bureau’s data on a 2019 company survey recording data on owner demographics, industry and business information, as well as use of technology.

## Data Extraction
>A complete ETL report can be found under Census-Project-Report.pdf.

The data set used was extracted from the Census Bureau website using an API call through python, which was brought in as JSON and read into a pandas data frame. Each member individually worked in a .ipynb file where each member had their own process for transforming including renaming columns, replacing values provided by the API, and filtering out unnecessary rows. Each individual process can be found in the python notebook files provided in the repository.

## Results

> Our results can be found in our project report under Census-Project-Report.pdf.

# References

-	U.S. Census Bureau. (2021, October 14). Annual Business Survey (ABS) apis. Census.gov. Retrieved September 2, 2022, from https://www.census.gov/data/developers/data-sets/abs.2019.html
