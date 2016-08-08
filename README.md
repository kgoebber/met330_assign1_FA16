# MET 330 - Assignment #1
Dr. Kevin Goebbert <br>
Fall 2016 <br>
<br>
### <b>Due Date: 8 September 2016 at 1:30 pm</b><br>
## Objectives
* Use basic Fortran and selective operations to answer a scientific question
* Learn to use github to organize and track work
* Break down large task into smaller pieces to complete work

## Problem
You have just moved to a new place with a different climate than any area you have previously lived and you want to learn about the seasonality of precipitation over the region. Since you have taken a computer programming class you have decided to use the Fortran programming language to help you out. Currently you don't have the proper data to analyze the actual values, but you're going to get started by setting up the framework to be able to  get the answers you desire once you have the data.  <p>
A helpful piece of information to investigate the seasonality of any atmospheric variable is to know the Julian Day of the year. The way that a meteorologist would typically define the Julian Day is to start with 1 January as Julian Day 1, 2 January as Julian Day 1, etc. This appears to be a straightforward task, but we can't forget about leap years! Leap years occur every four years, but not in years divisible by 100 unless it is also divisible by 400. For example, 2000 <b>is</b> a leap year despite the fact that it is divisible by 100 because it is divisible by 400.<p>
For this assignment, your final code should do the following (reading in a date from a file): <br>
* Determine the Julian Day of the year (whether a leap year or not)
* Determine what percentage of days have occurred by the given date
* Determine what percentage of days have yet to occur during the given year
* Determine what astronomical season the date falls in (winter = January, February, March; spring=April, May, June; summer=July, August, September; fall=October, November, December)
* Output should be clearly formatted and easily readable by a non-specialist
* Turn in a diagram that maps the final code to visualize program workflow

## Evaluation Criteria
Each of the following criteria will be rated from 0 (not present/completed) to 10 (exemplary)
* Required elements completed as listed in assignment description
* Informative and Clear Output from running code
* Code is well documented (informative comments/descriptions of code blocks) and solid use of github to organize and track progress on assignment
* Code is well structured and not overtly repetitive
* Code map accurately represents actual code and is neat and professional
