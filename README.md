# Data-Cleaning project 1

**Data Cleaning**
<p> Data cleaning, also known as data cleansing or data scrubbing, is the process of identifying and correcting errors and inconsistencies in raw data sets to improve data quality. The goal of data cleaning is to ensure that data is accurate, complete, consistent, and usable for analysis or decision-making.</p>
<p> Data cleaning processes work to address common data quality issues such as duplicates, missing values, inconsistencies, syntax errors, irrelevant data, and structural errors.</p> 

**Goal**
Clean a raw dataset by handling missing values, duplicates and incorrect data.

**Key Requirements**
<ul>
  <li> Identify missing or null values </li>
  <li> Remove duplicates</li>
  <li> Correct data formats (dates,numbers,test)</li>
</ul>

**Key Skill**
<ul>
  <li> Date cleaning</li>
  <li> Excel or Python basics</li>
  <li> Data preparation </li>
</ul>

#### Summary
<p> Upon inspecting the dataset for missing values, 309 missing entries were identified in the CouponCode column.</p>
<p>These were imputed using the most frequently occurring value  "FREESHIP" as the mode replacement strategy.</p>
<p>Additionally, the numeric suffixes attached to SAVE10 and WINTER15 were stripped, standardizing them to SAVE and WINTER respectively for consistency across the column.</p>
