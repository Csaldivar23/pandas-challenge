# pandas-challenge
Module_4_Challenge_Pandas

For this challenge I sorted and analyzed the data provided in the 'schools complete' and 'students complete' csv files.

The basis of this challenge was to break down this raw data to show:

- the school name/type
- the total amount of students/per school
- the budget: per total/school/student
- average scores in math and reading
- percentage of students passing math and reading

in a variety of different dataframes.

These are some of the key finding in this analysis:

- We had two school types: Charter and District. The Charter schools in general have less students and a smaller school budget in comparison to District schools. To compare, 'Ford High School' is a District school and had the smallest total students (2739) and total school budget ($1,763,916.00) in comparison to the other District schools. 'Wilson High School' is a Charter school and it had the highest total students (2283) and total school budget ($1,319,574.00) in comparison to the other Charter schools. This can be seen under 'Scores by School Spending'.

- There are 15 schools in total, and it is clear through this analysis that the highest-performing schools are Charter schools. When analyzing which schools had the highest '% Overall Passing,' it was Charter schools that came out on top, with the top 5 schools having a passing rate of over 90%. On the contrary, District schools had the lowest '% Overall Passing' rate, with the bottom 5 all being District schools, and the lowest score being 52.98%. This can be seen under 'Highest-Performing Schools (by % Overall Passing)' and 'Bottom Performing Schools (By % Overall Passing)'.

- This analysis has made it clear that small to medium sized schools have a higher passing rate amongst their students. All the Charter schools except for the previously mentioned 'Wilson High School' are small to medium sized schools. As for the District schools, they are all large schools. In general, the Charter schools in this data set have an average of 90.43% Overall Passing Rate. The District Schools have an average of 53.67% Overall Passing Rate. This can be seen under 'Scores by School Size' and 'Scores by School Type'.