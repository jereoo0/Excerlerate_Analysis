# Excelerate User and Opportunity Analysis
This report provides a comprehensive analysis of user participation and opportunity enrollment on the Excelerate platform, an experiential learning platform designed to help users develop career-ready skills through personalized experiences and internships

## Table of Contents
- [Overview](#overview)
- [Objective](#objective)
- [Data Sources and Methodology](#data-sources-and-methodology)
- [Datasets Overview](#datasets-overview)
- [Data Cleaning Process](#data-cleaning-process)
  - [User Data](#user-data)
  - [Opportunity Data](#opportunity-data)
- [Key Questions Addressed](#key-questions-addressed)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)
- [Contact](#contact)

## Overview
Excelerate is an experiential learning platform established in 2022, offering personalized experiences and internships to help users and learners build the skills needed for a rewarding future in the job market.

## Objective
This report provides comprehensive insights into user participation and enrollment onto opportunities on the Excelerate platform. It includes an interactive dashboard showcasing key demographic insights, user engagement trends, and segmentation, enabling stakeholders to make data-driven decisions.

## Data Sources and Methodology
- **Data Sources:** [Excelerate](https://engage.4excelerate.org/mod/assign/view.php?id=20052)
- **Analysis Tools:** Google Sheets, Power BI
- **Datasets Used:** <a href="https://docs.google.com/spreadsheets/d/1P3dnXnI5BMkyCgmHQrIKEzlM-NQW0HIQzHEn-q6OTQY/edit?usp=sharing">Opportunity Data</a> ,
                     <a href="https://docs.google.com/spreadsheets/d/1srVuN2re-WXXSHsvZmdSXHoKKDJl_djUsbqIOXBDvYA/edit?usp=drive_link">User Data</a> 
- **Dashboard Link:** <a href="https://1drv.ms/u/c/0c31997b4c1e9f35/Eb0g3AzStGhIlqklpl1-65YB_IKrFn6sf9uqLSUVMpe6gQ?e=ERXoxM">Dashboard</a> 

## Datasets Overview
- **User Dataset:** 27,527 records with columns covering PreferredSponsors, Gender, Country, Degree, Sign Up Date and Time, City, isFromSocialMedia
- **Opportunity-wise Dataset:** 20,323 records with columns covering Profile Id, Opportunity Id, Opportunity name, Opportunity category, Opportunity end date and time, Gender, City, State, Country, Graduation date(YYYY MM), Current student status, Current/Intended major, Status description, Apply date and time, Opportunity start date and time, Reward amount, Badge Id, Badge name, Skill points earned, Skills earned

## Data Cleaning Process
### User Data
- Remove duplicates using data clean up feature on google sheets. (No duplicates were found)
- Corrected Sign up date column to date/time format and split date and time into separate columns
- Deleted 36 rows of data, they were either null or empty and did not provide any information on demographics (Country, Gender, Degree, 
  City and Zip code) All these accounts were either created on 29th November 2022 at 10:24 difference in seconds  or 14th December 2022 
  at 8:42 difference in seconds. Isfromsocialmedia column was also blank.
- Made corrections to misspelt city names which resulted in multiple occurrences of the same cities but different spellings. Also 
  corrected instances where the user country was India but the city was Saint Louis which is in the United States (81 instances). There 
  was also the occurrence of Hyderabad, a city in both India and Pakistan. Changed Hyderabad in Pakistan to Hyderabad (P) to create a 
  distinction between the two cities in different countries. (30 instances)
- Deleted zip code column because the data was too messy and the city column provided the same information.
- Standardized columns to enusre consistence and clarity 

### Opportunity Data
- Remove duplicates using data clean up feature on google sheets. (No duplicates were found)
- Corrected date/time column formats and split dates and time into separate columns. 
- Deleted zip code column because the data was too messy and the city column provided the same information.
- Made corrections to misspelt city names which resulted in multiple occurrences of the same cities with different spellings. Also 
  corrected instances where the user country was India but the city was Saint louis which is in the United States (81 instances). There 
  was also the occurrence of Hyderabad, a city in both India and Pakistan. Changed Hyderabad in Pakistan to Hyderabad (P) to create a 
  distinction between the two cities in different countries. (30 instances) Changed instances where country was United states  but city  
  Hyderabad  was which is a city in India (3 instances).
  Standardized columns to enusre consistence and clarity 


## Key Questions Addressed
- How many users have signed up and enrolled in opportunities?
- What are the top 10 countries and cities by user sign-ups?
- Which opportunities are the most popular and most completed?
- What are the demographics of enrolled users?
- What are the most gained skills on Excelerate?
- How much scholarship funding has been awarded?

## Key Findings
- **27,526 users** signed up on the platform, with **11,481 enrolling** in opportunities.
- **20,322 total enrollments**, primarily in **internships (15,360 enrollments).**
- **$2.726 million** in scholarships awarded across completed opportunities.
- **Data Visualization** is the most enrolled opportunity (5,687 enrollments, 835 completions).
- **India** leads in user sign-ups (11,927 users) and enrollments (9,135).
- **Saint Louis, USA** has the highest city-level engagement (970 users, 2,671 enrollments).
- **Gender statistics** of user sign-ups (61.17% Male, 38.33% Female) and enrollment (Male 60.23%, Female 39.39%) indicate a gender gap.
- **Graduate and undergraduate students** dominate the platform, with low engagement from high school students.
- **Critical thinking skills** are the most gained skills.
- **Social media reach** of the platform is nearly evenly split, 50.19% of users answered True to "isfromsocialmedia" while 49.81% answered false. Analysing social media reach by demographics reveals inconsistencies in the effectiveness of social media campaigns.
- **Current/Intended major** of enrolled users reveals the the platform attracteds students in **STEM fields.** 

## Recommendations
- **Increase female engagement** by tailoring opportunities with scholarships as incentives.
- **Prioritize internships**, given their high demand. **Review engagement opportunities** due low user interaction.
- **Expand social media campaigns globally** to increase reach and engagement on the platform.
- **Increase social media campaigns in high-performing regions** (Asia, Africa, North America), to further increase the platforms presence in regions. 
- **Review, tailor and market opprtunities to high school students** to boost their presence.
- **Diversify offerings** to attract non-STEM students.

## Conclusion
This analysis provides valuable insights into Excelerate’s user engagement and opportunity enrollment trends. Strategic actions such as improving gender diversity, intensifying social media campaigns, and refining content offerings will help maximize the platform's impact and future growth.


**Introduction to Excleterate User and Opportunity Analysis**
![Screenshot 2025-02-15 195334](https://github.com/user-attachments/assets/1a9de1e6-750e-4cf1-bd54-700895ee5158)
                      
 **Opportunities by Demographics**
![Screenshot 2025-02-15 163425](https://github.com/user-attachments/assets/3cbbe0fe-9534-45c2-8c9c-10f53bf21c2f) 

 **Opportunities Analysis**                                
![Screenshot 2025-02-15 163446](https://github.com/user-attachments/assets/4ab22404-b894-4b4c-a8a4-a9d09c30961a)
                                     
**Dates**
![Screenshot 2025-02-15 163547](https://github.com/user-attachments/assets/831e07ef-4230-4bc3-938f-1fec5ad76904)
                                              
**User Educational Info and Skills earned**
![Screenshot 2025-02-15 163531](https://github.com/user-attachments/assets/0340e969-7d33-487e-9215-e42d51ed6614)
                                

## Contact
For inquiries, reach out to me @jeremyasamoah123@gmail.com. 

