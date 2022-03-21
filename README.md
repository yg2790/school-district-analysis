# School District Analysis
## Overview
Helping the School Board to update student scores in the school district database due to reported academic dishonesty in Thomas High School 9th grade, and create new analysis report on the impact of overall grade averages and passing percentages after grade removal.

## Result
- Before the removal of Thomas High School 9th graders' reading and math scores, the average of overall math_score and reading_score across all high school students were of 78.98 and 81.88, respectively. <br />
 <img width="350" alt="Screen Shot 2022-03-20 at 8 29 49 PM" src="https://user-images.githubusercontent.com/98621924/159201801-c9e9c08b-0a62-490e-8f54-4964f434be31.png"><br />
 <img width="331" alt="Screen Shot 2022-03-20 at 8 29 40 PM" src="https://user-images.githubusercontent.com/98621924/159201811-54832029-5a16-4fd9-b7de-0b1d08c59f62.png"><br />
- After the removal of these results the new average overall math and reading score became 78.9 and 81.9 as shown in our newly calculated district summary.<br />
<img width="709" alt="Screen Shot 2022-03-20 at 8 40 13 PM" src="https://user-images.githubusercontent.com/98621924/159202373-1861a01d-bc31-493e-8971-c854e686bcd7.png"><br />
- After the removal of 9th grade scores from the calculation of school summary, Thomas High School saw extremely low passing percentages because the 9th graders were will counted in the total student population.<br />
<img width="738" alt="Screen Shot 2022-03-20 at 8 35 04 PM" src="https://user-images.githubusercontent.com/98621924/159202180-349dc5e2-efb5-4b2f-ab4d-81d538bc58fa.png"><br />
- We took the steps to recalculate the Thomas High School student population that should be accounted for for this period's school summary, removed 9th graders, and recalculated the percentage of passing students in all fair test takers. The passing percentage rose from 67% to 93% for maths and 70% to 97% for reading. <br /> 
<img width="734" alt="Screen Shot 2022-03-20 at 8 35 15 PM" src="https://user-images.githubusercontent.com/98621924/159202261-5ec00266-cb4c-4a76-901b-71cbea39ad1f.png"><br />
- Since we are only recalculating the averages and percentages of scores for Thomas High School and not adjusting the overall formula, other school's results inthe school summary were not effected.<br />
### By Grade
- As we can see by grade, since one of the variable is the grade of the students, the incident does not effect the results. <br />
- There are no aggregation or calcuations in these tables, and the 'na' are clearly visible to illustrate the anomaly in the results.<br />
<img width="233" alt="Screen Shot 2022-03-20 at 8 44 19 PM" src="https://user-images.githubusercontent.com/98621924/159202636-ec32991a-fe88-4956-acd0-e1e58e12dcaa.png"><br />
<img width="227" alt="Screen Shot 2022-03-20 at 8 44 28 PM" src="https://user-images.githubusercontent.com/98621924/159202641-80449bbd-146b-439d-b70f-8aaa978d0a87.png"><br />
### By School Spending, School Size, and School Type
- The results is impacted by the replaced ninth-grade scores because we are completeing calculation such as the mean and percentage passing in this table, which the 9th grader should be removed in not only their grades, but also the number of students accounted for.<br />
- Specifically the Chartered school type and medium school size results will be impacted because Thomas High School is a Chartered High School with around 1600 students, which lies in the middle sized school category.
<img width="638" alt="Screen Shot 2022-03-20 at 8 46 59 PM" src="https://user-images.githubusercontent.com/98621924/159202826-018d4667-e2d2-4ac8-8b3d-ee3a8061d5ff.png"><br />
<img width="582" alt="Screen Shot 2022-03-20 at 8 49 42 PM" src="https://user-images.githubusercontent.com/98621924/159202979-763c3b8b-97fc-4264-a649-72cb8a77bcfc.png"><br />
<img width="554" alt="Screen Shot 2022-03-20 at 8 50 39 PM" src="https://user-images.githubusercontent.com/98621924/159203027-b82fbb5e-961d-4725-b390-8e8d77d795d5.png"><br />

## Summary
The changes includes:<br />
- The removal of 9th grader math and reading scores of Thomas High School in the student data file.
- Isolate 10th-12th graders and calculate new student number for Thomas High Schhol.
- Recalculate Thomas High School average test scores and percentage of student passing both the math and reading test with new total student number.
- Replacing the values in the automated school summary file with new calculated results.
