An Introduction to the Tidyverse | Session One
========================================================
author: Tim Hargreaves
date: [Session Data TBC]
autosize: true



Introductions
====================================
type: section

About Me
====================================
type: sub-section

Who Am I?
========================================================
left: 75%

* Tim Hargreaves
* Ex-student of Alsager Sixth Form
* Studying Mathematics and Statistics at the University of Warwick
* Work heavily with data and machine-learning models
* Currently undertaking a year-long placement at AstraZeneca
* Previously worked with dunnhumby and Bet365

***

![Warwick Logo](images/company_logos/warwick_logo.png)

![AstraZeneca Logo](images/company_logos/astrazeneca_logo.jpg)

![dunnhumby Logo](images/company_logos/dunnhumby_logo.png)

![Bet365 Logo](images/company_logos/bet365_logo.png)

Contact Details
========================================================

* Best way to contact me is via email: tim.hargreaves@icloud.com
* Feel free to connect with me on LinkedIn: www.linkedin.com/in/tim-hargreaves/
* Check out my blog for data science applications: www.ttested.com

About The Course
====================================
type: sub-section

Prerequisites
========================================================

* The only real expectation of this course is that you have general numerical literacy and can navigate around a computer
* Previous programming experience will make learning easier but is not expected at all

Basis of the Course
========================================================
left: 70%

* Based on the book *R for Data Science* by Hadley Wickham & Garrett Grolemund
* Many sections have been removed (originally ~500 pages)
* Freely available to read at [r4ds.had.co.nz](r4ds.had.co.nz)

This course differs from R4DS in two ways:

* More focus on immediate gains rather than complete mastery of the tidyverse
* Examples centre around the use of the A-Level weather dataset

***

![R for Data Science Cover](images/r4ds_cover.png)

What Will This Course Teach You?
========================================================

This course aims to teach you how to:

* Set up R, RStudio, and the tidyverse on your computer
* Import a data set from the web and clean it
* Wrangle a data set from one form to another
* Transform a data set to help answer a question
* Visualise a data set using plots and graphs
* Communicate data honestly and effectively

What Won't This Course Teach You?
========================================================

Sections of the R4DS book not covered in this course include:

* Working with relational (multi-table) data sets (maybe?)
* Handling non-categorical text data
* Iterative techniques
* Statistical modelling
* Communicating results with wider audiences

Why bother learning the tidyverse?
========================================================

**Why learn data analytics?**

* Data skills are currently in high demand
* In our modern economy, almost all professions process data in some way

**Why use the tidyverse?**

* Far more powerful and expandable than Excel or Tableau
* Open-source and free to use (unlike SAS or SPSS)
* A large and beginner-friendly community
* A lot more intuitive than more conventional programming languages (Python, Julia)

Course Agenda
========================================================

* The course will be ran weekly for six weeks
* The last session will be a DataViz Battle (with prizes)
* Each session will be split into three parts:
  * Recap of the last session and answers to any common questions I have received
  * Presentation covering new material alongside live-coding examples
  * Time to apply the new techniques to a problem sheet
  
The tidy-what?
========================================================
type: section

Foundations
========================================================
type: sub-section

What is R?
========================================================

* Programming language for statistical computing and graphics
* Built upon an historic language (S) which was developed in the mid-70s
* Known for being highly extensible
* Completely free and open-source with a large, friendly community

R is an incredibly powerful tool. It can be used for machine learning, statistical modelling, big data, and much more. It is also capable of producing websites, interactive notebooks, and presentations (such as this one!)

Setting Up R
========================================================

**Installation**

* Go to [CRAN](https://cran.r-project.org/), the *comprehensive R archive network*
* Select the download link that matches your operating system
* Choose the `base` installation and download the latest version
* Install as you would any other program

**Running**

* If the installation was successful, you will have a new entry in your start menu called *R x64 [Version Number]*
* Clicking this will open a program in which you can write R code

Problem:
========================================================
type: alert

The standard R code editor is difficult to use, missing useful features, and frankly quite ugly

Solution:
========================================================
type: prompt

Install RStudio and use it on top of R

What is RStudio?
========================================================

* Integrated development environment (IDE) specifically made for programming in R
* Contains a rich set of features to allow you to code in R with less hassle
* Displays your code and its output in a much clearer way and gives you access to extra features such as help files, code history, and environment variables

Essentially, unless you are trying to provoke a headache, it is advised to do all R programming in RStudio.

Setting Up RStudio
========================================================

* The latest version of RStudio can easily be download from [www.rstudio.com/download](www.rstudio.com/download)
* This can also be reached by simply searching for RStudio
* Once installed, you can open the program and all of the behind-the-scenes communication with your R installation will be done automaticall.

NB: RStudio does not work as a standalone program. You will still need R installed even if you intend to only write code in RStudio.
