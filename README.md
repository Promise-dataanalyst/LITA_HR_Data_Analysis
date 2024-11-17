# LITA_HR_Data_Analysis

![Screenshot (110)](https://github.com/user-attachments/assets/3516cf18-c558-4245-b978-ab4d2458fa70)

![Screenshot (108)](https://github.com/user-attachments/assets/dcc3b94f-6288-4c32-b8aa-f7b78d11f444)


### HR Data Analysis Report
-----
**Overview:** The HR Data Analysis Tracker for the Incubator Hub, in collaboration with Ladies in Tech Africa, provides key insights into employee demographics, attrition trends, and workforce distribution across various factors. This analysis includes a total of _**1,470**_ employees, with _**1,233**_ currently active.


#### Data Analysis
In the analysis I included some lines of code or queries or even some of the DAX expression Firstly, get your dataset and transform on the power query editor on power BI.  Then remove duplicates, use filters if neccessary. change the data type and promote header by using first row as header.

**Added conditional column for Age band sort**
= Table.AddColumn(#"Changed Type2", "Age Sort", each if [CF_age band] = "Under 25" 

![Capture 11](https://github.com/user-attachments/assets/44055f80-3376-4ddf-9b0f-45f1aa1fe3d4)


Go to column and check the column distribution to know the how many erros.

![Capture 12](https://github.com/user-attachments/assets/63603570-2190-4f34-a99d-31dc1ff8d1fb)


_**Key Metrics:**_
- Total Number of Employees: **1,470** ![Screenshot 1](https://github.com/user-attachments/assets/d5186ff6-7f04-4e88-805d-555f71d16c9d)

- Total Number of Current Employees: **1,233** ![Screenshot 8](https://github.com/user-attachments/assets/8583f38c-41da-4f4a-805d-5581ce08b761)

- Attrition Rate: **16%** ![Screenshot 3](https://github.com/user-attachments/assets/49e59b1d-5cbf-4317-a7ec-7e6b997068b3)


- Total Attrition Count: **237** ![Screenshot 9](https://github.com/user-attachments/assets/24d0ef22-8454-4d74-aea5-186b9c9ad61a)

- Average Age of Employees: **37 years** ![Screenshot 6](https://github.com/user-attachments/assets/c416bac1-209c-4700-b524-e08954054dea)


### Attrition Analysis:
----
**Attrition by Gender:**
- Male: 150 (63.29% of total attrition) 
- Female: 87 (36.71% of total attrition)
  
![Screenshot 2](https://github.com/user-attachments/assets/78d5e7e5-0303-4858-b60f-4c0b5433131d)

The attrition rate among male employees is notably higher than that of female employees, making up the majority of overall attrition.

**Attrition by Department:**
- R&D: 92 (38.82% of total attrition)
- Sales: 133 (56.12% of total attrition)
  
![Screenshot 4](https://github.com/user-attachments/assets/bb924bf5-8635-48c5-b87c-69085bbdc6b4)

The Sales and R&D departments exhibit the highest attrition rates, with Sales leading, suggesting a potential need for improved retention efforts in these areas.

**Attrition by Field of Education:**
- Life Sciences: 89
- Medical: 63
- Marketing: 35
- Technical: 32
  
![Screenshot 7](https://github.com/user-attachments/assets/800324f0-7ad3-4d0f-8585-b58f8b78b5b2)

Employees from Life Sciences and Medical fields exhibit the highest attrition numbers, indicating possible challenges specific to these areas that may affect retention.

**Distribution of Current Employees by Age Band and Gender:**

The bar chart shows the current number of employees divided by age group and gender (female and male). This data reveals insights into the organization’s age and gender distribution.

### Key Findings:

**Main Age Groups:**
- The largest employee groups are ages  25-34 and 35-44
- In the 35-44 age group, there are 272 males and 182 females, indicating strong male presence.
- In the 25-34 age group, there are 268 males and 174 females, also showing significant male representation.

**Older Age Groups (45-54 and Over 55):**
- The 45-54 age group has 104 males and 116 females, showing a more balanced gender mix but a lower total count compared to younger groups.
- The Over 55 age group has the fewest employees, with 36 females and 30 males, indicating a smaller workforce close to retirement.

**Youngest Age Group (Under 25):**
- The Under 25 age group has the least employees, with 20 males and 18 females recorded. This may suggest difficulties in recruiting young women or a preference for hiring slightly older individuals.
  
**Attrition by Age Group and Gender**

- **Under 25:** Male attrition is slightly higher, with 20 males leaving compared to 18 females.
  
- **Ages 25-34:** Attrition is balanced, with 69 males and 43 females leaving.

- **Ages 35-44:** Male attrition is significantly higher, with 37 males leaving compared to just 14 females.

- **Ages 45-54:** Male attrition remains higher, with 16 males leaving compared to 9 females.

- **Over 55:** Overall attrition is lower in this age group, with 8 males and 3 females leaving.

### Implications:
The focus of employees in the 25-44 age range suggests a younger workforce. Organizations should consider ways to recruit and keep younger women (Under 25) and explore options to retain older employees (45+) through flexible work arrangements or career development programs.

Below are the visualizatios

![Screenshot (120)](https://github.com/user-attachments/assets/1cf28cc1-3d2d-436d-ab6b-7b2215bc6a90)




![Screenshot (121)](https://github.com/user-attachments/assets/4ed7bbf4-db9f-49f4-b592-5949c7db0ce9)


### Conclusion:
The HR data reveals that male employees have a higher attrition rate compared to female employees. The Sales and R&D departments, along with employees in Life Sciences and Medical fields, experience the highest attrition rates. Most employees are young, particularly under 25, which could impact retention strategies aimed at stabilizing the workforce.
 You can reach me [Here](https://www.linkedin.com/in/chima-promise/)








