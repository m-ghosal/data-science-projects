# data-science-projects
## Projects completed as part of the Introduction to Data Science I & II courses
Project 1: The Open Payments Database (research paper is titled 'midterm project.pdf' and the filtered datasets used and code written aree also attached)

Open Payments is a national disclosure program that gives insight into the financial relationships of drug
and medical device companies with physicians and teaching hospitals. It makes payment transactions
between the two different types of entities available to the general public in an effort to increase
transparency between patients and their healthcare providers. I carried out my exploration of the Open
Payment datasets by looking into the 2020 Research Payments and the 2017 and 2020 Ownership
Payments datasets. Below is a description of how I filtered each dataset to make the research more focused:

- 2020 Research Payments: The original dataset had 588,942 rows containing the payments received by
physicians and teaching hospitals for research purposes from January 1, 2020 - Dec 31, 2020. In order to
conduct a more focused research, I added two filters to this dataset, filtering it by state (to include only
Illinois (IL)) and by recipient type (to include only teaching hospitals). This then reduced the dataset to
3,406 rows, creating a more niche and focused dataset. Since many of my friends are medical students who intend on coming to the US to complete their medical
school journey, I was curious in examining the most popular research areas in Illinois during the Covid
era and the teaching hospitals involved in these research fields and the amount of funding allocated to
them.
- 2017 and 2020 Ownership Payments: I filtered both these datasets based on state (to include only
Illinois (IL)). These datasets give me more insight into individual physician practices and physician
specialties which receive the most funding and how these investments change over the years from 2017 to 2020. This reduced the size of the 2020 dataset from 3,238 rows to 112 rows and the size of the 2017
dataset from 3,218 rows to 119 rows. This would also help my friends in med school come to a more
concrete conclusion about their field of study within medicine.

Project 2: The Chicago Data Portal (research paper is titled 'Data Science II Project final.pdf' and the code written is attached)

This was a group project, the description of which is as follows:
For this project, we selected the Crimes dataset (2001 - Present) from the Chicago Data Portal as our foundation of study. This dataset was extracted from the Chicago Police Department’s CLEAR (Citizen Law Enforcement Analysis and Reporting) map, and includes 22 fields for every crime recorded by Chicago PD since 2001, including the type of crime; a more specific description of each crime; location of crime by coordinates, street address, block and civilian district; time the crime was recorded to have occured (both in terms of date and time of day); whether the crime occured within someone’s home and whether or not the perpetrator(s) was arrested. Given that the complete dataset, which is updated on a daily basis, covers criminal activity over the last 21 years, we chose to focus our study more by filtering the dataset based on the date and the year to only include all records from March 1st, 2019 to March 31st, 2022, which covered a total of 688,825 crimes recorded over the last three years. This gave us the opportunity to analyze how crime rates have changed with COVID since the dataset includes both pre-Covid and post-Covid years, as well as examining subjects of interest such as when and where crime rates are at their highest and lowest, the frequency of certain crimes throughout the day, and the likelihood of arrest depending on the location of the crime.
My role in the group was:
- Filtered the dataset based on year and sent it to the rest of the group to make sure we were all working with the same dataset.
- Researched about the dataset, its fields, and its significance
- Analyzed the Hourly crime rates of most popular crimes (graph C) in Chicago by creating a stacked bar chart after grouping the data and merging datasets appropriately.
- Assisted with the data modelling (linear regression model)

