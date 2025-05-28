# 🏥 Healthcare Data Analytics Project

This repository presents a healthcare data analysis project using synthetic patient records. It focuses on exploring demographic patterns and test result distributions to simulate real-world data insights. The project showcases Excel data cleaning and Tableau dashboard creation, with planned integration of SQL queries.

This project utilizes a single synthetic dataset that includes: **Patient demographics** (age, gender, blood type), **Admission/discharge details**, **Test results** (numerical values), and **Provider and department data**. The data has been cleaned and standardized to improve accuracy and consistency for visualization and future SQL querying.

## Tools and Technologies Used

- **Excel** – Data cleaning and preprocessing  
- **Tableau** – Data visualization and dashboard building  
- **SQL (Coming Soon)** – For data exploration, segmentation, and KPI creation

## Excel Cleaning Highlights

- Standardized text using `PROPER`, `TRIM`, and `CLEAN`  
- Removed prefixes like Mr., Ms., Dr. for consistency  
- Rounded numerical fields for cleaner visual output  
- Removed duplicates and normalized provider names using:  
  `=IF(K2="UnitedHealthcare", "United Healthcare", K2)`  
- Ensured consistent column types for Tableau integration

## Tableau Dashboard Features

This dashboard presents a visual summary of healthcare patterns with the following elements:

- **Pie charts** – Blood type and gender distribution  
- **Box plots** – Length of stay per test result  
- **Bar charts** – Test result trends by age and gender  
- **KPI cards** – Average test results, total patients, and more  

Dashboard screenshots are included in the repository.  
* Tableau Public link coming soon.*

## Planned SQL Integration

A future SQL analysis section will include:

- Patient segmentation by age, gender, and department  
- Calculation of average test results  
- KPI creation, such as abnormal test rates and average length of stay  
- Joining and aggregating healthcare tables for department-level insights  

SQL scripts will be added to `sql_analysis.sql` once completed.

## Project Structure

- **healthcare_data_cleaned.xlsx** – Cleaned dataset with Excel formulas  
- **tableau_dashboard.twbx** – Interactive Tableau workbook  
- **tableau_screenshots/** – Folder with preview images of dashboard  
- **README.md** – Project documentation  
- **sql_analysis.sql** (coming soon) – SQL scripts for deeper analysis  

## Contact

- **Author:** Luis Carabajo  
- **Email:** luisc121203@gmail.com  
- **LinkedIn:** [Luis Carabajo](https://www.linkedin.com/in/luis-carabajo-a5449b250/)  
- **GitHub:** [Mario121284](https://github.com/Mario121284)

---

*This project highlights my ability to clean, analyze, and visualize healthcare data — with more SQL-powered insights coming soon.*
