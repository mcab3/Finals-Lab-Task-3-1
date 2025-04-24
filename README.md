# Finals Lab Task 3-1. Using MYSQL Clause
In this task, it involves setting up the database environment, retrieving targeted information based on certain conditions, organizing data into logical categories, and summarizing key figures. This reinforces the ability to extract insights from data and understand how database systems are used to support decision-making processes.

Following the directions given below in creating the given database.
1. Create a database named online_courseDB
2. Use the online_courseDB
3. Copy and paste the initial query then perform the SELECT statements required for each
problems in the figure then the download onlineCourse.sql file.

<img src="Images/db.png" width="300">

Item description:

The following are already implemented:

A table named courses with the following fields:

id: Unique Integer, auto-increment, primary key.

course_name: String (VARCHAR), not null.

category: String (VARCHAR), not null.

enrollment_limit: Integer, not null,

students_enrolled: Integer, not null.

20 courses are already present.

<img src="Images/dbtable.png" width="300">
<img src="Images/insertcourse.png" width="500">

## Query Statements:
- **Step 1.**  Retrieve all courses where students_enrolled is less than the enrollment_limit.  <img src="Images/1retrievelessthan.png" width="500">  
- **Step 2.**  Group courses by category and calculate the total number of students enrolled for each category. <img src="Images/2groupcategory.png" width="500">
- **Step 3.**  Retrieve the courses that are fully enrolled (ie,, students enrolled equals enrollment limit). <img src="Images/3retrievedfullyenrolled.png" width="500">   
- **Step 4.**  Calculate the total number of students enrolled across all courses. <img src="Images/4calculatetotalstudents.png" width="500">  
- **Step 5.**  Sort courses by students_enrolled in ascending order.  
  <img src="Images/5sortstudent.png" width="500">

## Table Structures:
- **Table 1.** students_enrolled is less than the enrollment_limit.    
  <img src="Images/1retrievelessthan_ts.png" width="500">  
- **Table 2.** orgranized grouped courses by category.  
  <img src="Images/2groupcategory_ts.png" width="500">  
- **Table 3.** retrieved courses that are fully enrolled.  
  <img src="Images/3retrievedfullyenrolled_ts.png" width="500">  
- **Table 4.** calculated total of the students.  
  <img src="Images/4calculatetotalstudents_ts.png" width="500">    
- **Table 5.** sorted courses.  
  <img src="Images/5sortstudent_ts.png" width="500">  




