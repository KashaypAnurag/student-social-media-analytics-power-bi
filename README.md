\# Student Social Media and Mental Health Analytics Dashboard



\## Project Overview

This dashboard was built to help school advisors and mental health counselors understand how social media usage impacts students. It analyzes a dataset of 705 students from different countries to find links between daily screen time, sleep patterns, relationship status, and academic performance.



\## Dashboard Interface

\### Executive Summary

This section provides high-level KPIs tracking cohort size, average usage velocities, sleep hours, and academic impact distributions.



!\[Executive Overview Dashboard](screenshots/executive\_overview.png)



\### Academic Performance Impact

This view highlights specific application channels driving academic drops alongside interactive numeric filtering tools.



!\[Academic Impact Analysis](screenshots/academic\_impact.png)



\### Student Profile Drill-Through Navigation

An advanced individual profile view that lets users dive deep into individual student demographics and calculated risk metrics.



!\[Student Profile View](screenshots/student\_profile.png)



\## DAX Calculations and Repository Structure

I saved this project in the Power BI Project (.pbip) format. This breaks the binary file down into text configurations, which allows Git to track changes to layouts and DAX formulas cleanly over time. 



All business logic calculations are organized explicitly within a centralized Measures Table container rather than relying on default implicit columns.



!\[Centralized DAX Measures Table](screenshots/dax\_measures.png)



\## Key DAX Measures Created

1\. Average Sleep Hours: Calculates the average sleep duration per night across the student group.

2\. Average Usage Hours: Tracks the daily average time spent on social media platforms.

3\. Percentage Affected Academically: Measures the proportion of students who report that social media has hurt their grades.

4\. Addicted Student Count: Counts the number of students who scored higher than a 7 on the addiction scale.



\## Main Insights from the Analysis

\* Data shows that 64.26% of the surveyed students have seen a direct, negative impact on their academic performance because of social media use.

\* Image-heavy and video-heavy platforms like Instagram and TikTok are linked to the highest number of academic performance issues.

\* The individual drill-through page allows counseling staff to identify specific high-risk student profiles instantly based on behavioral scores.



