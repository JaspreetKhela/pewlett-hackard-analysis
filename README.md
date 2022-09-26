# Pewlett Hackard Analysis

## Overview of Analysis

### Purpose
The purpose of this analysis is to determine the number of retiring employees per title and to identify employees who are eligible to participate in a mentorship program at Pewlett Hackard. Specifically, the organization wants to ensure that the job vacancies created by retiring employees can be filled by current employees so as to not significantly disrupt the operations of the organization.

## Results

### Tables
_____

<img width="780" alt="retirement_titles_csv" src="https://user-images.githubusercontent.com/80941606/192239444-0ef219ae-a4b3-4eb9-aed6-7da9529ed6b5.png">

**Table 1**: Snapshot of retirement_titles.csv.

_____

![retiring_titles_csv](https://user-images.githubusercontent.com/80941606/192239472-1e02be20-2ca9-4ea4-b622-8de7a5d0f0e3.png)

**Table 2**: Snapshot of retiring_titles.csv.

_____

<img width="748" alt="mentorship_eligibility_csv" src="https://user-images.githubusercontent.com/80941606/192239501-05eb5797-24be-4aca-a899-de54bd196d82.png">

**Table 3**: Snapshot of mentorship_eligibility.csv.

_____

### Observations

The following points were observed from the analysis:
* In the retirement_titles.csv, many records correspond to the same person in different jobs throughout that individual's tenure at the organization, so it seems that there are more employees retiring than there actually are at first glance;
* In the retiring_titles.csv, the vast majority of retiring employees are in the engineer and staff jobs;
* In the retiring_titles.csv, most jobs that will become vacant are senior jobs, which means that mostly only other senior non-retiring employees will qualify to fill those job vacancies; and
* In the mentorship_eligibility.csv, many if not most of the current employees whom are available for mentorship are currently in engineer and staff jobs.

## Summary

### Job Vacancies Versus Mentees
In summary, we can observe that:
* There will be 72,458 job vacancies in the near future at Pewlett Hackard and
* There are 1,549 current employees that qualify for mentorship (to fill in the aforementioned job vacancies).

Consequently, a new strategy is or new criteria are required to find more current employees to fill the job vacancies. Additionally, Table 2 and Table 3 illustrate that only those mentorship-qualified employees who are about to reach or are at the senior level within the organization are eligible to fill those job vacancies, so there are fewer than 1,549 employees who are actually ready to fill those job vacancies.
