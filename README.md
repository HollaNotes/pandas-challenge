# pandas-challenge
**Module 4 Challenge - Pandas**

### **Background:**
You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.
As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

### **About the Data:**
This analysis is based on data from a particular school district. It is comprised of 2 csv files titled “schools_complete.csv” and “students_complete.csv”. This data was joined together by the “school_name” using the join method and is named “school_data_complete”. The column names are as follows:
 
![image](https://github.com/HollaNotes/pandas-challenge/assets/90803907/291f280e-9423-4c40-bc13-c436637ba324)

---

#### **District Summary:**
In order to get an overall summary of the district, calcualtions were made to find:
  - Total Schools 
  - Total Students
  - Total Budget
  - Average Math Score
  - Average Reading Score
  - % Passing Math
  - % Passing Reading
  - % Passing Overall

![image](https://github.com/HollaNotes/pandas-challenge/assets/90803907/83a35406-dc13-4e17-acf2-d42ec9a5ca6e)


#### **School Summary:**
Next, calculations were made to dig a little deeper into the district by looking into data about each school. In the chart below, you are able to start seeing a better breakdown between the different schools. 

![image](https://github.com/HollaNotes/pandas-challenge/assets/90803907/b1d07084-2d66-4f56-a932-6e69bebb6b91)


#### **Highest-Performing Schools (by % Overall Passing):**
Calculations were made to sort the schools by Highest Overall Passing Percent. This was done by sorting the schools by the column "% Overall Passing" and viewing the rows in descending order, as seen below:

![image](https://github.com/HollaNotes/pandas-challenge/assets/90803907/de3d1098-2bb5-49f9-8bac-f45566bfa7d8)


#### **Bottom Performing Schools (By % Overall Passing):**
Calculations were made to sort the schools by Lowest Overall Passing Percent. This was done by sorting the schools by the column "% Overall Passing" and viewing the rows in ascending order, as seen below:

![image](https://github.com/HollaNotes/pandas-challenge/assets/90803907/d614584b-9e36-40d8-858d-3ab6d787a206)


#### **Math Scores by Grade:**
Math Scores by grade was calculated by separating the scores by grade (9th grade - 12th grade) and grouping the school names with the math scores and finding the average score.

![image](https://github.com/HollaNotes/pandas-challenge/assets/90803907/a39ee262-3e2b-4274-9ee6-2e88fab4042a)


#### **Reading Score by Grade:**
Reading Scores by grade was calculated by separating the scores by grade (9th grade - 12th grade) and grouping the school names with the reading scores and finding the average score.

![image](https://github.com/HollaNotes/pandas-challenge/assets/90803907/c5b36883-0f24-4d45-9ad5-2ff7f2728244)


#### **Scores by School Spending:**
The chart below includes the bin method to group together schools who have spent similar amounts throughout the year. 

![image](https://github.com/HollaNotes/pandas-challenge/assets/90803907/f3dd32cb-a037-4c6f-88b8-3ad29ec5dad5)


#### **Scores by School Size:**
The chart below uses the bin method as well to group together schools by similar size. 

![image](https://github.com/HollaNotes/pandas-challenge/assets/90803907/65e0a822-e27b-4bfe-8919-6077f2fb73ee)

![image](https://github.com/HollaNotes/pandas-challenge/assets/90803907/cd3067f2-d894-49d3-ad58-f57b31124145)


#### **Scores by School Type:**
The chart below compares Charter Schools vs. District Schools. As you can see, Charter schools tent to have an overall passing rate of 90% while District Schools tend to have an overall passing rate of 54%.

![image](https://github.com/HollaNotes/pandas-challenge/assets/90803907/c6a85062-698b-48be-939c-d1e60ed24f80)

---

### **( Conclusions or comparisons from calcs )**

- The data suggests that Charter Schools have a highter overall passing rate than District Schools. As seen in the above section "Scores by School Type", you can see the difference in the average passing rates between the two types of schools.
- The data suggests that there is a negative correlation between spending ranges and overall scores. As seen in the above section "Scores by School Spending", it seems that the schools that spend the most per student tended to have lower scores than schools that spent less money per student. The bins were all within about a $100 range, so this may be a coincidence, but it was in interesting finding for this particular district.
- The data suggests that there is little correlation between test scores and grade in high school. The scores of each grade in a particular high school tend to stay similar while the larger difference is scores between different schools. 


