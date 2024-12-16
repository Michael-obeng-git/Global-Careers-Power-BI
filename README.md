# Global Careers Data Analytics and Visualization with Power BI.

## Power BI Dashboard for Tracking Student Progress and Performance: Global
Careers

### Preamble: 

Global Careers is a business that provides training in Power BI and AWS Cloud. To
effectively monitor the progress and performance of its students,Global Careers requires a
comprehensive Power BI dashboard. This dashboard will track key metrics, including daily
Zoom attendance records, daily participation, weekly quiz and lab grades, and learner
status (graduation and certification). The data for this project is organized as follows:
• Zoom Attendance: Directories for both Power BI and AWS Cloud tracks,
each containing 10 directories (Week 1 through Week 10). Each directory
holds daily attendance records for the respective week.
• Lab and Quizzes: Directories for both Power BI and AWS Cloud tracks, each
containing weekly lab and quiz grades for the 10-week period.
• Participation Records: Directories for both tracks, containing daily participation
records for each learner over 10 weeks.
• Status Records: Directories for both tracks, containing the certification and graduation
status of each learner.
This dashboard will provide insights into learner engagement, progress, and outcomes,
helping program managers and trainers track performance trends, identify learners at risk
of dropping out, and measure key performance metrics such as certification and
graduation rates.

## Page 1: Overall Performance Metrics

### Objective:

Provide a high-level overview of learner performance, summarizing key metrics for
program stakeholders.

#### Visuals:

1. Bar Charts:
- Graduation Rates: Percentage of learners who graduated from each
cohort.
- Certification Rates: Percentage of learners who achieved
certification.
- Dropout Rates: Percentage of learners who dropped out of
the program.
- Average Attendance: Display the average percentage of total class
time attended by learners.
- Average Participation: Visualize the average engagement score based on
daily participation.
- Average Assessment Scores: Show the average quiz and lab scores for
each cohort.

3. Cards (Summary Figures):
- Total Certifications: Display the number of learners who achieved certification.
- Total Learners: Show the total number of learners enrolled across all cohorts.
- Total Dropouts: Count the number of learners who dropped out
before completing the program.
- Total Graduations: Show the total number of learners who
successfully graduated.

### Filters:
Incorporate slicers to allow users to filter the data based on the following
dimensions: • Cohort: Choose specific cohorts to view their performance.
• Track: Filter by different tracks (e.g., Power BI, AWS Cloud).
• Certification Type: Filter by the type of certification (if applicable).
• Learner Status: Filter by learners who are Certified or Not Certified.

Page 2: Detailed Learner Insights

### Objective:
Provide detailed insights into individual learner progress and engagement for trainers
and program managers.

### Visuals:
1. List of All Learners:

- Display a table listing all learners, their respective tracks, and key
performance metrics (e.g., attendance, participation, assessment scores).
2. Cards (Summary Figures):
- Count of Labs: Total number of labs completed by all learners.
- Average Labs Completed: Average number of labs completed per learner.
- Total Hours Spent in Class: Total number of hours each learner has
spent attending class sessions.
- Average Attendance Rate: The average attendance rate per learner.
- Average Participation Rate: The average participation rate for learners based
on daily engagement.
o Average Assessment Scores: Average score of all quizzes and labs for
each learner.

### Filters:
Slicers will allow users to explore data specific to:
• Cohort: Filter by individual cohorts to monitor specific groups of learners.
• Track: Filter by track (Power BI or AWS Cloud).
• Month: Filter metrics by the month within the 10-week program.
• Week: Filter by specific weeks to analyze performance trends.
• Learner Status: Filter by learners who are Certified or Not Certified.
• Program Status: Filter by program completion status (Ongoing or Completed).

## Additional Instructions:

1. Class Attendance:
o Condition: A learner will be marked as "attended" if they have spent more
than 30 minutes in a Zoom session.
o This condition will apply to all attendance calculations in both the
Overall Performance Metrics and Detailed Learner Insights.

2. Data Preparation:
o Ensure daily attendance records, participation records, lab and quiz grades,
and learner status (graduation and certification) are structured and cleaned
before importing into Power BI.
o Use the daily attendance directories to track attendance compliance with
the condition of “attended” being over 30 minutes per session.
o Aggregate weekly lab and quiz scores to provide averages and totals for
both detailed learner insights and cohort-level performance analysis.

3. Modeling and DAX:
o Use DAX formulas to calculate averages, attendance percentages, and
track certification and graduation rates dynamically.
o Ensure relationships between attendance, participation, labs, quizzes,
and learner status tables are properly defined.
