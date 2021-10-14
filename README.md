# School District Analysis
### Project Overview
The goal of this project is to evaluate data from a complete School District, such as financing and student grades, in order to get fresh insights and present visual results on each school's performance. Furthermore, due to probable academic dishonesty among a group of pupils, this analysis was conducted twice to uphold state-testing requirements. The consequences of omitting potentially deceptive data are also considered.

#### Resources: All data used in this analysis is found inside of the Resources folder.

#### Software: Python 3.7, Anaconda, Jupyter Notebook

### Results
This analysis was done twice due to the possibility of academic dishonesty by Thomas High School's ninth grade students. The whole set of student data was used in the first trial of this study but in the second iteration of this research, the ninth-grade students at Thomas High School's results were not included in the calculations. Thomas High School's whole ninth grade class had their scores substituted with NaN. 

Replacing the ninth graders' math and reading scores with NaN resulted in the following changes for Thomas High School:

The overall passing percentage for Thomas High School fell to 65%
The overall passing percentage for the entire district fell to 64.9%
Thomas High School was no longer included on the list of top five schools.

When the ninth graders' of Thomas High School had their scores omitted from the calculations, the following changes occured:

The overall passing percentages of Thomas High School decreased by 0.11%
The average scores of Thomas High School for math and reading increased by 0.06
For the spending range of $630-644 per student, the overall passing percentage decreased by 0.1%

The school rankings have not changed. Thomas High School remains the district's second best performing school, with an overall passing percentage of 90.63 percent among tenth through twelfth students.

### The Effects of School Budget and School Size
My analysis uncovered that when per-student spending grows, average scores and passing percentages do not rise. In fact, the highest-performing school in the district (Cabera High School) received $68 less per student than the lowest-performing school (Johnson High School). This implies that there are more important elements influencing average student scores than financing.

When it comes to school sizes, "Large" Schools (2,000+ students) have the lowest average scores and passing rates. The performance gap between "Small" and "Medium" Size Schools is minimal (about 1 percent ). However, all District schools in this dataset are labeled as "Large." This might indicate that children in this district learn and perform better in smaller, more personal settings.

### Charter vs. District Schools
In this research, charter schools outperformed district schools on average. The top five schools with the highest overall passing percentages are all Charters, whereas the lowest five are all Districts. Charter schools in this dataset were generally classified as "Small" or "Medium" in size. Charter schools have a 36% better overall passing rate than district schools, as seen in the DataFrame below. 

This does not mean all charter schools are better than district schools, this analysis is only limited to this district.

### Average Scores by Grade Level
After evaluating the average math and reading results by grade level for each school, it was shown that a student's grade level does not effect their scores as much as the school that they attend. The average results within each school vary by only 1-2 percent depending on grade level. When comparing scores from other schools, the disparity becomes more obvious.


### Summary
Unfortunately, determining the level of the potential academic dishonesty and identifying specific individuals to eliminate from the dataset is not achievable. As a result, the scores of all ninth-grade students at Thomas High School have been deleted from the results. This is not an ideal condition because a complete collection of data is best for producing the most accurate results.

When the ninth graders' scores were replaced with NaN, Thomas High School's overall passing percentages and average scores plummeted. The district's average math and reading scores, as well as the total passing rate for kids, have all decreased. Furthermore, Thomas High School lost its ranking as one of the District's top five schools. However, after adjusting the overall student counts to exclude Thomas High School ninth graders and removing their results from the dataset, Thomas High School restored its high average scores and maintained its status as the District's number two school. Please open PyCitySchools Challenge.ipynb to see the entire script.
