# School_District_Analysis.
## Project Overview

In this project, we prepare all standaredized test data for analysis, reporting, and presentation to provide insights about performance trends and patterns.These insights are used to inform discussions and strategic decisions at the school and district level. 
We analyze data on students' funding and students' standardized test scores. Our task is to aggregate the data and showcase trends in school performance. 

In this project, we also check for any academic dishonesty by replacing the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact.

## Resources
- Data Source: [Students_Complete](Resources/students_complete.csv)
- Software: Jupyter Notebook

## Results
- How is the district summary affected?
<img width="1015" alt="District Summary" src="https://user-images.githubusercontent.com/77806210/194192008-7bc60ab9-7d01-40b0-a657-1a224a9252b9.png">
The district summary is not affected by the changes made. Every column remained the same.

- How is the school summary affected?
<img width="1020" alt="School Summary" src="https://user-images.githubusercontent.com/77806210/194199858-6ec49388-4d29-47b5-8231-c31d2ac983bb.png">
We can also see that the school summary is not affected by the changes made. Every column is pretty much the same.

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
<img width="1305" alt="High and Low Performance" src="https://user-images.githubusercontent.com/77806210/194200508-09f5e44d-7995-41c6-9b79-4c8ba44764b2.png">
We can see that Thomas High School is in the Top 5 schools. The high and low school performance was not affected by the changes made. 

- Math and reading scores by grade
<img width="1269" alt="Math and Reading Scores by Grade" src="https://user-images.githubusercontent.com/77806210/194201959-85a0695f-4763-42cf-90e9-750fc243f774.png">
The average math and reading scores show as Nan as we expected. 

- Scores by school spending
<img width="1001" alt="Scores by school spending" src="https://user-images.githubusercontent.com/77806210/194202580-7ea90e1c-3a82-48e4-b980-c09430cc6510.png">
There is no significant changes, except that the Passing Reading and the Overall Passing dropped by few percentages.

- Scores by school size
<img width="1165" alt="Scores by school size" src="https://user-images.githubusercontent.com/77806210/194202786-5a0e7e42-36a6-4c33-be56-9be21411a325.png">
There is no noticeable change to the Scores by School size.
- Scores by school type
<img width="1320" alt="Scores by school type" src="https://user-images.githubusercontent.com/77806210/194202876-132251c2-856a-4c7a-ae81-7f13edc0ca1b.png">
There is no noticeable change to the Scores by School type.
## Summary 
After reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs, there are no major changes, except for the values that have been replaced by Nan in the scores grade. 
