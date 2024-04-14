# Analyzing College Affordability using a Distributed Data Science Pipeline - MSADS508 
## College Affordibility Classification 

<p align ="center">
<img src = "/images/IMG_0037-ANIMATION.gif" width = "50%" height = "auto">
</p>

### Installation

To use this project, first clone the repo on your device using the commands below:

`git init`

`git clone https://github.com/dsklnr/CollegeAffordability.git`

### Contributor(s)    
* [Ben Ogle]
* [Logan Van Dine] 
* [Jacqueline Vo]  

**Company Name:** AffordableU Foundation  
**Company Industry:** Non-Profit Education Assistance  
**Company Size:** 11-50

### Methods  
* Data Exploration
* Data Visualization  
* Pre-processing    
* Statistical modeling  
* Data modeling metrics  

### Technologies  
* Python (AWS Sagemaker)  
* SQL Transformations  
* AWS (Sagemaker, Athena, S3)  
* Powerpoint    

### Abstract 
The future prospects and basic needs of students aspiring to pursue higher education are increasingly affected as college tuition costs have dramatically grown over recent years. This study aims to analyze the historical trends of college tuition costs to provide valuable insights and personalized guidance to high school students looking to enroll in college.

### Problem Statement
AffordableU Foundation is dedicated to providing the opportunity of a higher education to more students around the United States. Since most students view the cost of college tuition to be the largest obstacle, finding universities in their region or state that are affordable options is necessary. Higher education leads to more opportunities, which can increase the quality of life for many individuals. Additionally, the tangible skills that come from higher education enable low-income individuals to pursue higher-earning careers that can further provide monetary and educational support to their families.

AffordableU Foundation is interested in increasing the number of people who hold college degrees because it will lead to a better future for society. Having a society of individuals with different backgrounds, who are skilled workers will mold a society that can provide citizens with a higher quality of life. Additionally, having a skilled workforce ultimately benefits employees, employers, and consumers.

### Goals 
1. Predictive Analytics: Predict Universities that will have a high ROI for graduating high school seniors
2. Prescriptive Analytics: Identify Universities that are deemed affordable

### Non-Goals 
While our aim remains to increase the number of high school graduates attending prestigious universities, it is not within the scope of this project to guarantee any outcomes to students nor any predicted statistics of top universities. Furthermore, there is no guarantee that the assisted student will be accepted into any university. Additionally, this project does not guarantee that the predicted tuition rate will be the definitive rate in the future as this project is not affiliated with any university enrollment committee being studied.

### Data Sources 
Data will be stored on AWS service S3 Bucket that will communicate with AWS Sagemaker. The five files will be uploaded to S3 bucket.

* Kaggle Inc. College data: csv file 58,123 rows and 33 columns
https://www.kaggle.com/datasets/ryusonoda/u-s-university-dataset-from-2001-to-2022

* TuitionTracker Net Price after Grants and Scholarships: csv file with 3,240 rows and 36 columns  
https://www.tuitiontracker.org/

* TuitionTracker Sticket Price: csv file with 3,240 rows and 123 columns  
https://www.tuitiontracker.org/

* U.S. Department of Agriculture Poverty Estimates: csv file with 3,195 rows and 34 columns
https://www.ers.usda.gov/data-products/county-level-data-sets/county-level-data-sets-download-data/

* U.S. Department of Agriculture Unemployment: csv file with 3,277 rows and 100 columns
https://www.ers.usda.gov/data-products/county-level-data-sets/county-level-data-sets-download-data/
