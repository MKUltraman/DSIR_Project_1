For this course, I am pretending that I am tasked with providing guidance to students, all of whom want to know what SAT/ACT score they should be aiming for in order to get into the school or program they desire.

I begin by looking at the average SAT scores by intended major.  This provides me with scores for each field, and thus I can recommend that students looking to enter fields such as mathematics or medicine set ther goals on exceptionally high scores (past 1300) if they want to stand out from the crowd.  Students with goals of entering security or construction fields can set their goals on much lower totals (higher than 1000) to stand out.  

Then, instead of looking at scores by individual schools, we can look at the relationsip between a school's acceptance rate and their average accepted student's SAT/ACT scores.  Generally speaking, the lower the acceptance rate, the higher the average score.  Schools such as Harvard, with exceeedingly low acceptance rates, have nearly perfect scores as their 75th percentile.  To stand out from such a crowd, perfect scores would be a necessity, but even then, you only stand out by a little.  It would appear that a low score would more harmfully impact your chances than would a high score positively impact them.  
For schools with much higher rates, such as Queens University of Charlotte, the school's average accepted scores are much lower.  With that in mind, exceeding those average scores would be a good way to make yourself an appealing student to the school.

Data Dictionary:
|Feature|Type|Dataset|Description|
|---|---|---|---|
|intended_college_major|object|intended_major|What major a student intends to focus on| 
|test_takers|integer|intended_major|how many students with only the corresponding intended major took the SAT test|
|percent|float|intended_major|percentage of all students given who selected this major|
|total|int|intended_major|average combined SAT score of students in this intended major|
|reading_writing|int|intended_major|average SAT reading/writing score of students in this intended major|
|math|int|intended_major|average SAT math score in this intended major|
|school|object|score_by_school|which school is represented in this row|
|test_optional|object|score_by_school|is the test optional at this school|
|applies_to_class_years|object|score_by_school|which years the policy in this row applies to|
|policy_details|object|score_by_school|specific exceptions and detail made by each school|
|number_of_applicants|int|score_by_school|how many students applied to this school|
|accept_rate|float|score_by_school|percentage of applicants which were accepted to this school|
|sat_total_75th_percentile|float|score_by_school|75th percentile total SAT score of the accepted students|
|act_total_75th_percentile|float|score_by_school|75th percentile total ACT score of the accepted students|

Ultimately, a higher score on these tests is always a preferable one.  Nonetheless, it can ease the pressure off students who know they are aiming for programs where the competition is looser.  If the student knows they want to enter a field or attend a school with a lower average score, they can focus on getting their scores just high enough to stand out, and then spend the rest of their energy elsewhile.  Students that want a field or school with a much higher average, however, must focus their energy on improving their score as much as possible so as to make themselves an exciting candidate.

https://www.compassprep.com/college-profiles/

https://reports.collegeboard.org/pdf/2019-total-group-sat-suite-assessments-annual-report.pdf

https://hms.harvard.edu/

https://www.queens.edu/academics/majors-minors-programs/nursing-bsn.html
