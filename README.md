# School_District_Analysis Challenge. Learning Jupyter with School District Data.

# How is the district summary affected when reading and math scores are dropped for 9th graders at Thomas High School?
	* The % Passing Math dropped from 94% to 88%
	* The % Passing Reading dropped from 97% to 91%
   	* The overall % Passing Percentage dropped from 95% to 90 % for Medium Sized schools

# How is the Thomas HS school summary affected?
Thomas High Schools drops from 4th in Overall Passing % at 95.3% to last place at 68.3%.
	
	* Average Math and Reading cores remained nearly identical (83.4%, 83.8%) before the exclusions and (83.4%, 83.9%) after exclusions. This means either the dropped student scored very similarly to the district scores, or their exclusions where too small in number compared to the total student count to make a significant impact.
	* % Passing Math dropped from 93.3% to 66.9%
	* % Passing Reading dropped from 97.3% to 69.7%
	
So overall, the THS averages are about the same, but a large enough pool of students was removed that the overall passing percentages went down dramatically when factoring the excluded students.      

# Affect on Math and Reading scores by removing Grade for THS
  Since there is no longer and math and reading score data for THS, we get nan, or nothing, for Average Math and Reading Scores.

# Scores by School Spending
What stands out is change in the $630-644 binn, where % Passing Math, % Passing Reading and % Overall Passing all drop due to the exclusions. This tells us that THS is in the third quartile, or third bin, with respect to Spending Per Student. 
	* % Percent Passing Math dropped from 77% to %73%.
	* % Percent Passing Reading dropped from 72% to 67%.
	* % Overall Passing Percentage dropped from 77%  to 72%.

# Scores by School Size
The scores for the medium sized schools dropped, serving as another indicator for Thomas High School. The % Passing Math dropped from 94% to 88%. The % Passing Reading dropped from 97% to 91%, and the overall % Passing Percentage dropped from 95% to 90% for Medium Sized schools.

# A note on discrepancy between average scores and percent passing scores. 
Average scores are calculated using the number of valid scores as the score count.  As THS math and reading scores are dropped, the mean is calculated using available scores rather than the count of students.  Percent Passing statistics are based on student counts, so percent passing statistics will reflect larger differences than average scores. Ergo larger differences are visible in the percent passing stats as compared to averages.

# Overall Summary of affects of removing Thomas High School 9th Graders
The average scores where not notably affected, but clearly the percentage passing both math and reading suffered due to the exclusions. 

This summary analysis also shows how data groups can be highly affected when group binn sizes are smals, as shown by the changes in percentage passing by school spending and scores by schools size, two groups with binn sizes of four and five. 

Overall, the removal of the THS 9th graders was visible in the percentage passing statistics district summmary, the per school summary for Thomas High School, and the group statistics for medium sized schools and schools in the third quartile in per student spending.
