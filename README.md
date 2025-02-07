# AI-Driven-Job-Market-Analysis-and-Salary-Prediction

The demand for data analytics professionals in the U.S. is evolving rapidly, with new roles, skill requirements, and salary trends emerging across industries. Despite the increasing integration of data-driven decision-making and AI advancements, students and professionals face uncertainty regarding career prospects, market demand, and potential earnings. Additionally, academic institutions struggle to align curricula with industry needs, creating a gap between education and workforce readiness.

### The objective of this study was to analyze the 2024 U.S. job market for data analytics professionals, providing insights into:

Geographical distribution of job opportunities.
![image](https://github.com/user-attachments/assets/d0184e8d-7726-4537-af5a-e8d5f1ca87c5)

Salary trends across various roles and industries.

Most in-demand technical skills in the field.
Educational requirements for different positions.
Remote vs. hybrid vs. on-site work trends.
Job market concentration among top companies.

### Work Flow
1. For this project we have Collected real-time job postings using SERP API https://serpapi.com/ from multiple job platforms.
2. Applied Natural Language Processing (NLP) techniques (e.g., BERT) to extract salary information.
3. Processed unstructured job descriptions by standardizing categories, refining experience fields, and structuring skills/education data.
4. Created a synonym dictionary to enhance skill extraction from job postings.
5. Finally, Developed a MultiOutput Random Forest Regressor to predict Min and Max Salaries simultaneously, providing real-time salary insights based on qualifications, experience, and location for job seekers and employers.

### Result
Enhanced salary prediction accuracy, enabling data-driven decision-making for job seekers and employers.
Provided real-time salary insights, reducing uncertainty in job negotiations and compensation planning.
Created a scalable model adaptable to various industries and geographies.
Improved transparency in salary expectations, helping recruiters optimize hiring strategies.
