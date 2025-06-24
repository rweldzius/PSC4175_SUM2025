# PSC 4175-01: Introduction to Data Science (Summer 2025)

## Table of Contents

  * [Course Description](#course-description)
  * [Required Applications](#required-applications)
  * [Evaluation & Responsibilities](#evaluation-&-responsibilities)
  * [Course Policies](#course-policies)
  * [Office Hours](#office-hours)
  * [Syllabus](#syllabus)
  * [Helpful Resources](#helpful-resources)
  * [Acknowledgements](#acknowledgements)
    
## Course Description

The use of large, quantitative data sets is increasingly central in social science.  Whether one seeks to understand political behavior, economic outcomes, or violent conflict, the availability of large quantities of data has changed the study of social phenomena. In this course, students will learn about data acquisition, management, and visualization — what we call data science — to answer exciting questions in the social sciences. Whereas most data-related courses focus exclusively on probability theory, matrix algebra, and/or statistical estimation, our main focus will be on the computational tools of data science. Students will leave the course with the ability to acquire, clean, visualize, and analyze various types of political data using the statistical programming language R, which will set them up for success in future statistical courses (as well as the post-graduation job market). No prior background in statistics is required, but students should be familiar with how to use a computer and have a willingness to learn a variety of data science tools. 

The contents of this repository represent a work-in-progress and revisions and edits are likely frequent.

The main text for the course is "R For Data Science" which can be assessed free online [here](https://r4ds.hadley.nz). Note that there are no assigned readings from this book; the material is synthesized in the daily homework assignments. However, should you need another source with more detail, you'll find most of the topics we cover in this course in this book.

Villanova has an enterprise site license for Microsoft’s Copilot chat application, which is built off of Open A.I.  Copilot is available to all faculty, staff, and students [here](https://copilot.microsoft.com).

**Class time and location**: Asynchronous (online), Monday-Thursday May 28 - June 2, 2025.

[Back to ToC](#table-of-contents)

## Required Applications

### Blackboard

This is the course management software used at Villanova University to support course learning. It is clunky, not user-friendly, and is thankfully on its way out soon. For these reasons, I will only utilize Blackboard to post course materials (e.g., additional readings), for you to submit your assignments, and to see your grades.

### Campuswire

I have set up a Campuswire workspace for our use this semester to help us better communicate with each other. You will need to create an account and join our workspace by following [this link](https://campuswire.com/p/GF9F6AD11). The Code/PIN can be found on the first email I sent to the class. You are encouraged to adopt these [Slack etiquette tips](https://slack.com/blog/collaboration/etiquette-tips-in-slack). Most likely, you will utilize a similar communication system at a future job, so use this time wisely as you adopt best practices. 

Here is the list of channels you should see upon joining the Campuswire workspace:

  * Class feed: A space to post questions and respond to other posts.

  * #announcements: A space for all course announcements.

  * #general: A space for you to share and discuss stories you've seen in the news or on social media that are relevant to our class.

  * Calendar: Not used. See [Syllabus](#syllabus) below. 

  * Files: Not used. See [Syllabus](#syllabus) below. 

  * Grades: Not used. See Blackboard. 

### GitHub

I have created a [GitHub](https://github.com/rweldzius/PSC4175_SUM2025/tree/main) repository to prepare and share all course-related content. This very syllabus is available as the repository's README and all links below are connected to the appropriate folders, sub-folders, and files in this repository.

You are expected to adopt the following workflow for this class:

  1. Prior to viewing each lecture, download the appropriate homework `.Rmd` file, open it in `RStudio`, and read through it. This is your primary homework assignment. As you work through it, try to tweak some of the code and answer the toy examples where provided. Each time you make a change, click the knit button in `RStudio` to see if everything still loads. You may find it useful to read through the homework first, then watch the lecture, then go back to the homework and complete the examples. These knitted files should be uploaded to Blackboard by midnight on the day the lecture is assigned; see schedule below.

  2. During each lecture, create a new `.Rmd` file to take notes in. As with the homework, you should be tweaking and adjusting things on your own, extending your learning beyond what is covered in lecture.

  3. After each lecture, tweak the notes `.Rmd` file further to test out new ideas that you come up with which were not covered in the lecture. Each lecture's slides will be made available as `PDF` for you use to help you review. 

[Back to ToC](#table-of-contents)

## Evaluation & Responsibilities  

As with learning any new topic or language, the best strategy is to put in a little effort every day. To this end, you will be assigned homework assignments for each class (see "workflow" above) that correspond with readings from the text. I recommend you read through the book first to get an overview of the topic and then attack the homework. 

You will be assigned weekly problem sets that will test your ability to apply what you've learned in the lectures. These problem sets are assigned on the Monday of each week and are due by **11:59PM Villanova time the following Friday**. You are welcome to collaborate on these problem sets, and are encouraged to ask questions on the Class feed on Campuswire.

The final grade is calculated as a weighted average of these components with the following weights:

  * **Problem sets**: 4 in total, total of 76 points available across all four. There will be a total of eight extra credit points available across the four problem sets.

  * **Homeworks**: There are 14 homeworks over the four weeks of class. Each will be worth 2 points, but only 12 will be graded (total 24 points). Thus, you can either miss two homeworks (two freebies) or you can use these two extra homeworks as extra credit. 

See the table below for a breakdown of the percentages, points, and extra credit.

| Item | Percent | Points | EC | Max |
|:-----|:-----:|:-----:|:-----:|:-----:|
| pset0 | 0% | 0 | 0 | 0 |
| pset1-pset4 | 76% | 76 | 8 | 84 |
| Homeworks | 24% | 24 | 4 | 26 |
| **Totals** | **100%** | **100** | **12** | **112** |

Letter grades are determined as per the standard Villanova grading system:

  * A: 94+
  * A-: 90-93
  * B+: 87-89
  * B: 84-86
  * B-: 80-83
  * C+: 77-79
  * C: 74-76
  * C-: 70-73
  * D+: 67-69
  * D: 64-66
  * D-: 60-63
  * F: <60

[Back to ToC](#table-of-contents)

## Course Policies

### Attendance

This course is entirely asynchronous, thus there is no official attendance policy. However, there are specific due dates for assignments, so you must be organized and be sure to submit everything on time. 

### Late Assignments

Homework assignments are due on the day they are assigned by **11:59PM Villanova time**. Late homeworks will not be accepted. Every problem set is assigned on a Monday and due on Blackboard by **11:59PM Villanova time on the following Friday**. Problem sets should be submitted via Blackboard. The problem sets are designed to require no more than a few hours to complete. Late submissions will be **penalized 1 point off for each day late**. After three days, problem sets will no longer be accepted and will be scored 0. 

### Academic Honor Code

All students are expected to uphold Villanova’s Academic Integrity Policy and Code. Any incident of academic dishonesty will be reported to the Dean of the College of Liberal Arts and Sciences for disciplinary action. You may view the [University’s Academic Integrity Policy and Code](https://www1.villanova.edu/villanova/provost/resources/student/policies/integrity/code.html) for a detailed description.

If a student is found responsible for an academic integrity violation, which results in a grade penalty, they may not WX the course unless they are approved to WX for significant medical reasons. Students applying for a WX based on significant medical reasons, must submit documentation and their request for an exception will be considered.

Collaboration is the heart of data science, but your work on your assignments should be your own. Please be careful not to plagiarize. The above link is a very helpful guide to understanding plagiarism. In particular, while students are invited to work on problem sets together, collaboration is prohibited on the midterm and final exams.

Copilot and related Large Language Models (LLMs) are essential tools in the data scientist's toolkit, and acceptable resources for completing the assignments and learning concepts at a deeper level. However, graded assignments cannot be generated purely by these tools. All assignments must include a log of the Copilot (or other AI programs) prompts and resulting output used to complete the assignment.

### Office for Access & Disability Services (ADS) and Learning Support Services (LSS)

It is the policy of Villanova to make reasonable academic accommodations for qualified individuals with disabilities. All students who need accommodations should go to Clockwork for Students via myNOVA to complete the Online Intake or to send accommodation letters to professors. Go to the LSS website http://learningsupportservices.villanova.edu or the ADS website https://www1.villanova.edu/university/student-life/ods.html for registration guidelines and instructions. If you have any questions please contact LSS at 610-519-5176 or learning.support.services@villanova.edu, or ADS at 610-519-3209 or ods@villanova.edu.

### Absences for Religious Holidays

Villanova University makes every reasonable effort to allow members of the community to observe their religious holidays, consistent with the University’s obligations, responsibilities, and policies. Students who expect to miss a class or assignment due to the observance of a religious holiday should discuss the matter with their professors as soon as possible, normally at least two weeks in advance. Absence from classes or examinations for religious reasons does not relieve students from responsibility for any part of the course work required during the absence. https://www1.villanova.edu/villanova/provost/resources/student/policies/religiousholidays.html.

[Back to ToC](#table-of-contents)

## Office Hours

  * Thursdays, 10am-12pm Villanova time
  * You must make an appointment for office hours here: https://calendly.com/weldzius/officehours
  * If you cannot make my office hours, please email me your availability at least 24-hours in advance and we can try to find a time that works.

[Back to ToC](#table-of-contents)

## Syllabus

| Date | Topic | Learning Goal | Materials | HW | Pset |
|:-----|:------|:------|:------|:------|:------|
| 5/28/25 | Introduction | Scientific method, camps of analysis | [Video](https://youtu.be/Ug166moDRls) <br/> [Slides](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/1_intro.html) | [HW1.html](https://rweldzius.github.io/PSC4175_SUM2025/Homeworks/psc4175_hw_1.html) <br/> [HW1.Rmd](https://github.com/rweldzius/PSC4175_SUM2025/blob/main/Homeworks/psc4175_hw_1.Rmd) |  |
| 5/29/25 | Intro to R 1 | Objects, functions, and code | [Video(1)](https://youtu.be/nBxddalwQyA) <br/> [Slides(1)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/2_Rintro_part1.html) <br/> [Video(2)](https://youtu.be/2MFCLkZVoAA) <br/> [Slides(2)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/2_Rintro_part2.html)| [HW2.html](https://rweldzius.github.io/PSC4175_SUM2025/Homeworks/psc4175_hw_2.html) <br/> [HW2.Rmd](https://github.com/rweldzius/PSC4175_SUM2025/blob/main/Homeworks/psc4175_hw_2.Rmd) | |
| 5/30/25 | No lecture | | | | [PS 0](https://github.com/rweldzius/PSC4175_SUM2025/blob/main/Psets/psc4175_pset_0.Rmd) |
| 6/2/25 | Data Wrangling | Replicability and tabular data | [Video](https://youtu.be/Nka7Ma7vBFI) <br/> [Slides](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/3_DataWrangling.html) | [HW3.html](https://rweldzius.github.io/PSC4175_SUM2025/Homeworks/psc4175_hw_3.html) <br/> [HW3.Rmd](https://github.com/rweldzius/PSC4175_SUM2025/blob/main/Homeworks/psc4175_hw_3.Rmd) | |
| 6/3/25 | Data Visualization (1) & Univariate Analysis (2) | Summaries of variables | [Video(1)](https://youtu.be/-pBebtWPb2o) <br/> [Slides(1)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/4_DataViz.html) <br/> [Video(2)](https://youtu.be/3TnmHJ_rRak) <br/> [Slides(2)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/4_Univariate.html)  | [HW4.html](https://rweldzius.github.io/PSC4175_SUM2025/Homeworks/psc4175_hw_4.html) <br/> [HW4.Rmd](https://github.com/rweldzius/PSC4175_SUM2025/blob/main/Homeworks/psc4175_hw_4.Rmd) | |
| 6/4/25 | Multivariate 1 | Conditional Relationships | [Video(1)](https://youtu.be/_xTEKVbnDbw) <br/> [Slides(1)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/5_Multivariate1.html) <br/> [Video(2)](https://youtu.be/w807SBZbFP0) <br/> [Slides(2)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/5_Multivariate2.html)| [HW5.html](https://rweldzius.github.io/PSC4175_SUM2025/Homeworks/psc4175_hw_5.html) <br/> [HW5.Rmd](https://github.com/rweldzius/PSC4175_SUM2025/blob/main/Homeworks/psc4175_hw_5.Rmd) | |
| 6/5/25 | Multivariate 2 | More Conditional Relationships | [Video](https://youtu.be/P7RsKcUHW6I) <br/> [Slides](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/6_Multivariate3.html) | [HW6.html](https://rweldzius.github.io/PSC4175_SUM2025/Homeworks/psc4175_hw_6.html) <br/> [HW6.Rmd](https://github.com/rweldzius/PSC4175_SUM2025/blob/main/Homeworks/psc4175_hw_6.Rmd) | |
| 6/6/25 | No lecture |  | |  |  [PS 1](https://github.com/rweldzius/PSC4175_SUM2025/blob/main/Psets/psc4175_pset_1.Rmd)  |
| 6/9/25 | Uncertainty 1 | Uncertainty and bootstrapping | [Video](https://youtu.be/DtwDB2nv3BA) <br/> [Slides](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/7_UncertaintyBootstrapping.html) | [HW7.html](https://rweldzius.github.io/PSC4175_SUM2025/Homeworks/psc4175_hw_7.html) <br/> [HW7.Rmd](https://github.com/rweldzius/PSC4175_SUM2025/blob/main/Homeworks/psc4175_hw_7.Rmd) | |
| 6/10/25 | Uncertainty 2 | Confidence statements | [Video(1)](https://youtu.be/q02LciYcIGI) <br/> [Slides(1)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/8a_ConfidenceStatements.html) <br/> [Video(2)](https://youtu.be/uDUPRnX-_ic) <br/> [Slides(2)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/8b_ConfidenceStatements.html)| [HW8.html](https://rweldzius.github.io/PSC4175_SUM2025/Homeworks/psc4175_hw_8.html) <br/> [HW8.Rmd](https://github.com/rweldzius/PSC4175_SUM2025/blob/main/Homeworks/psc4175_hw_8.Rmd) | |
| 6/11/25 | Regression 1 | Interpreting output and evaluating model | [Video(1)](https://youtu.be/Y1XocVcgzq8) <br/> [Slides(1)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/9a_RegressionPart1.html) <br/> [Video(2)](https://youtu.be/taIFftqpDIQ) <br/> [Slides(2)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/9b_RegressionPart1.html)| [HW9.html](https://rweldzius.github.io/PSC4175_SUM2025/Homeworks/psc4175_hw_9.html) <br/> [HW9.Rmd](https://github.com/rweldzius/PSC4175_SUM2025/blob/main/Homeworks/psc4175_hw_9.Rmd) | |
| 6/12/25 | Regression 2 | Interpreting output and evaluating model |[Video(1)](https://youtu.be/wiCMAArQJbg) <br/> [Slides(1)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/10a_RegressionPart2.html) <br/> [Video(2)](https://youtu.be/hGEonkyhad4) <br/> [Slides(2)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/10b_RegressionPart2.html)| [HW10.html](https://rweldzius.github.io/PSC4175_SUM2025/Homeworks/psc4175_hw_10.html) <br/> [HW10.Rmd](https://github.com/rweldzius/PSC4175_SUM2025/blob/main/Homeworks/psc4175_hw_10.Rmd) | |
| 6/13/25 | No lecture |  | |  | [PS 2](https://github.com/rweldzius/PSC4175_SUM2025/blob/main/Psets/psc4175_pset_2.Rmd)  |
| 6/16/25 | Regression 3 | Multiple regression, categorical Xs | [Video(1)](https://youtu.be/kODEpwWQj6s) <br/> [Slides(1)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/11a_RegressionPart3.html) <br/> [Video(2)](https://youtu.be/CC8bhfn76Uo) <br/> [Slides(2)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/11b_RegressionPart3.html)| [HW11.html](https://rweldzius.github.io/PSC4175_SUM2025/Homeworks/psc4175_hw_11.html) <br/> [HW11.Rmd](https://github.com/rweldzius/PSC4175_SUM2025/blob/main/Homeworks/psc4175_hw_11.Rmd) | |
| 6/17/25 | Classification 1 | The concept of logistic regression | [Video(1)](https://youtu.be/zycMNBysKrw) <br/> [Slides(1)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/12a_ClassificationPart1.html) <br/> [Video(2)](https://youtu.be/JtJ3fkr4vJk) <br/> [Slides(2)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/12b_ClassificationPart1.html)| [HW12.html](https://rweldzius.github.io/PSC4175_SUM2025/Homeworks/psc4175_hw_12.html) <br/> [HW12.Rmd](https://github.com/rweldzius/PSC4175_SUM2025/blob/main/Homeworks/psc4175_hw_12.Rmd) | |
| 6/18/25 | Classification 2 | Interpreting output and evaluating model | [Video(1)](https://youtu.be/ojRYXQHhVeQ) <br/> [Slides(1)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/13a_ClassificationPart2.html) <br/> [Video(2)](https://youtu.be/woOrkpJkrDA) <br/> [Slides(2)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/13b_ClassificationPart2.html) | [HW13.html](https://rweldzius.github.io/PSC4175_SUM2025/Homeworks/psc4175_hw_13.html) <br/> [HW13.Rmd](https://github.com/rweldzius/PSC4175_SUM2025/blob/main/Homeworks/psc4175_hw_13.Rmd) | |
| 6/19/25 | Holiday; No lecture | | | | 
| 6/20/25 | No lecture | | | | [PS 3](https://github.com/rweldzius/PSC4175_SUM2025/blob/main/Psets/psc4175_pset_3.Rmd)  |
| 6/23/25 | Clustering | k-means clustering | [Video(1)](https://youtu.be/2VME2P1GYQ8) <br/> [Slides(1)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/14a_ClusteringPart1.html) <br/> [Video(2)](https://youtu.be/F_0CVi4mVzU) <br/> [Slides(2)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/14b_ClusteringPart1.html) | [HW14.html](https://rweldzius.github.io/PSC4175_SUM2025/Homeworks/psc4175_hw_14.html) <br/> [HW14.Rmd](https://github.com/rweldzius/PSC4175_SUM2025/blob/main/Homeworks/psc4175_hw_14.Rmd) | |
| 6/24/25 | NLP 1 | k-means clustering on text | [Video(1)](https://youtu.be/wcPuKwJkXKk) <br/> [Slides(1)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/15a_ClusteringPart2.html) <br/> [Video(2)](https://youtu.be/QUBt_jGP40U) <br/> [Slides(2)](https://rweldzius.github.io/PSC4175_SUM2025/Lectures/15b_ClusteringPart2.html)| [HW15.html](https://rweldzius.github.io/PSC4175_SUM2025/Homeworks/psc4175_hw_15.html) <br/> [HW15.Rmd](https://github.com/rweldzius/PSC4175_SUM2025/blob/main/Homeworks/psc4175_hw_15.Rmd) | |
| 6/25/25 | NLP 2 | Sentiment analysis | Video <br/> Slides | [HW16.html](https://rweldzius.github.io/PSC4175_SUM2025/Homeworks/psc4175_hw_16.html) <br/> [HW16.Rmd](https://github.com/rweldzius/PSC4175_SUM2025/blob/main/Homeworks/psc4175_hw_16.Rmd) | |
| 6/26/25 | No new material |  |  | | [PS 4](https://github.com/rweldzius/PSC4175_SUM2025/blob/main/Psets/psc4175_pset_4.Rmd) |

[Back to ToC](#table-of-contents)

## Helpful Resources

[Rstudio Cheat Sheet: Data Wrangling](https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf)

[Rstudio Cheat Sheet: ggplot2](https://hbctraining.github.io/Intro-to-R-flipped/cheatsheets/data-visualization-2.1.pdf)

[R-graphics Cookbook](http://www.cookbook-r.com/Graphs/)

[... And the full list of Rstudio cheat sheets](https://posit.co/resources/cheatsheets/)

[Tidymodels Resources](https://www.tidymodels.org/learn/)

[Back to ToC](#table-of-contents)

## Acknowledgements

The contents of this course are influenced by and often come directly from Prof. James H. Bisbee who teaches a similar course at Vanderbilt University. I am indebted to him for making his course materials available. 
