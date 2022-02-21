# Pewlett-Hackard Analysis
### Helping Pewlett-Hackard prepare for the future

## Overview

Pewlett-Hackard, a company with more than 300,000 employees, has asked for an analysis of their current employment data. The purpose of this analysis is to provide their leadership with an understanding of the Baby Boomer generation's employment, aka the "Silver Tsunami" and how their impending retirement plans will impact the company. Using PostgresSQL, we have identified the number of employees likely to retire soon, as well as employees who may be a good fit for a mentorship program that will help ease the transition. 

## Results
#### Retirement
Of Pewlett-Hackard's 300,024 employees, 30.13% (90,398 / 300,024) are currently eligible for retirement. 
- Of those eligible, the job titles most frequent are Senior Engineer (29,415), Senior Staff (28,254), and Engineer (14,221). 


![retirebytitle](https://github.com/tech-neault/Pewlett-Hackard-Analysis/blob/main/Queries/RetiringByTitle.png)
- Of those eligible, the departments most frequent are Development (23,008), Production (20,163), and Sales (14,083). 


![retirebydept](https://github.com/tech-neault/Pewlett-Hackard-Analysis/blob/main/Queries/RetireByDept.png)

#### Mentorship Program 
Based on the standards set by Pewlett-Hackard, there are 1,549 employees who have the potential to be a mentor.
- This is only <b>1.71%</b> of the retirement-ready employees.

If the company wishes to pursue a mentorship program, they will have to make accomodations for this low number.



## Summary
Based on the analysis completed here, Pewlett-Hackard is facing a large number of employees who are likely to retire within the next few years. If Pewlett-Hackard wishes to replace retiring employees on a 1-to-1 basis, then around 90,000 jobs will need to be posted and re-filled as Baby Boomers retire. However, thanks to technology, it's possible that the company will not fill these positions, and instead reorganize them to require fewer new hires or promotions. At the end of the day, this decision lies with the company.

Considering the relatively low number of employees who are able to participate in the proposed Mentorship Program, Pewlett-Hackard must begin aggressively investing in their own junior employees. This could include additional training on top of the Mentors that younger employees could be assigned to work with. Based on the number available, it's likely that junior employees could be matched with a mentor in groups of 2 or 3. This would still not meet the demand, but it would greatly increase the number of junior employees able to go through the mentorship program. While generational knowledge transfer is not required to ensure the company stays afloat, it will help to make the transition much more smooth. 
