# Efficient Dataset Storage for Job Change Prediction  

## Project Overview  

This project focuses on optimizing the storage of a large customer dataset for Training Data Ltd., a prominent online data science training provider. The aim is to clean and restructure the dataset to enhance its efficiency, enabling quicker model predictions related to students' job-seeking behavior.  

## Dataset  

The dataset used for this project is `customer_train.csv`, which contains anonymized information about students and their job-seeking status. The key columns in the dataset include:  

| Column                     | Description                                                   |  
|----------------------------|---------------------------------------------------------------|  
| `student_id`               | A unique ID for each student.                                 |  
| `city`                     | A code for the city where the student resides.               |  
| `city_development_index`   | A scaled development index for the city.                     |  
| `gender`                   | The student's gender.                                        |  
| `relevant_experience`      | An indicator of the student's relevant work experience.       |  
| `enrolled_university`      | The type of university course the student is enrolled in (if any). |  
| `education_level`          | The student's education level.                                |  
| `major_discipline`         | The educational discipline of the student.                   |  
| `experience`               | The student's total work experience (in years).              |  
| `company_size`             | The number of employees at the student's current employer.    |  
| `company_type`             | The type of company employing the student.                   |  
| `last_new_job`             | The number of years between the student's current and previous jobs. |  
| `training_hours`           | The number of hours of training completed.                   |  
| `job_change`               | An indicator of whether the student is looking for a new job (1) or not (0). |  

## Objectives  

- Clean and optimize the `customer_train.csv` dataset for efficient storage.  
- Develop a proof-of-concept for a more efficient storage solution.  
- Prepare the dataset for subsequent analysis to predict if students are seeking new job opportunities.  
