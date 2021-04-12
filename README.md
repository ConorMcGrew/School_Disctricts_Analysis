# School_Disctricts_Analysis

## Overview

We were tasked with helping Maria to analyze math and reading standarized test data. The data was sourced from a variety of school disctricts, and it is used to show trends in performance and budgets. This will eventually be used by the board of education and superintendent to inform future budgetary decisions.  

## Results

* How is the district summary affected?
  - With Thomas High School's 9th grade results removed: <img width="926" alt="W:O THS 9th" src="https://user-images.githubusercontent.com/80495710/114340633-0501d200-9b26-11eb-8d56-df645419d64b.png">
  - With Thomas High School's 9th grade results included: <img width="917" alt="Screen Shot 2021-04-12 at 12 05 25 AM" src="https://user-images.githubusercontent.com/80495710/114340761-42fef600-9b26-11eb-9bab-00011ae2e7c1.png">
  - As can be seen, the district's results were somewhat affected considering only apprioximately 1% of the sample was removed. The overall percent passing decreased by nearly 0.3%, the percent passing math decreased 0.,18%, and the percent passing reading decreased only 0.1%.
* How is the school summary affected?
  - Thomas high school's overall performance *drastically* increased by the exclusion of the ninth grade results. The overall percent passing went from 65% to 90%, and the reading and math percent passing went from just under 70% to well over 90% (the overall size of the school decreased by a quarter, but it appears the students in the 10-12th grade all did exceptionally)
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - Thomas high school was right in the middle as far as performance before replacing the ninth grade. By replacing the ninth grade scores, they went from 8th, in terms of overall performance, to 2nd. 
* How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
    * Replacing the ninth grade scores had very little affect on this summary because the scores for Thomas High simply showed NaN, but the scores for other grades remained the same
  - Scores by school spending
  - Scores by school size
  - Scores by school type

## Summary: 
After removal of the Thomas High 9th Grade Results:
1. Thomas High's overall standing was 2nd best of all the schools.
2. It decreased the district overall passing percentage of the district by nearly 0.3%
3. The budget allotment per student at Thomas High increased substantially.
4. Thomas High became the 2nd best performing charter school, and better performing than *any* district school.
