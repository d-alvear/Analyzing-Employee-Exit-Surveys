# Analyzing Employee Exit Surveys

View the final notebook [here](https://nbviewer.jupyter.org/github/d-alvear/Analyzing-Employee-Exit-Surveys/blob/master/Part%202/V7_analyzing_employee_exit_surveys.ipynb), and the accompanying blog post [here](https://medium.com/@deandraalvear/analyzing-employee-exit-surveys-269d058bd762).

## Contents
* `Part 1`: Initial data cleaning and exploration notebooks
* `Part 2`: Final analyses and figures

## Introduction
In this project, I take on the role of a data analyst. I work with exit surveys from employees of the Department of Education, Training and Employment (DETE) and the Technical and Further Education (TAFE) institute in Queensland, Australia.

## Goals
My goals are to clean and analyze the data to answer the following questions to stakeholders:
* Are employees who only worked for the institutes for a short period of time resigning due to some kind of dissatisfaction? What about employees who have been there longer?
* Are younger employees resigning due to some kind of dissatisfaction? What about older employees?

## Data
Below is a preview of a couple columns I'll work with from the dete_survey.csv:

* `ID`: An id used to identify the participant of the survey
* `SeparationType`: The reason why the person's employment ended
* `Cease Date`: The year or month the person's employment ended
* `DETE Start Date`: The year the person began employment with the DETE

Below is a preview of a couple columns I'll work with from the tafe_survey.csv:

* `Record ID`: An id used to identify the participant of the survey
* `Reason for ceasing employment`: The reason why the person's employment ended
* `LengthofServiceOverall. Overall Length of Service at Institute (in years)`: The length of the person's employment (in years)

## Conclusion
The goal of this project was to answer the following questions:

* Are employees who only worked for the institutes for a short period of time resigning due to some kind of dissatisfaction? What about employees who have been there longer?
* Are younger employees resigning due to some kind of dissatisfaction? What about older employees?

It seems that employees that have worked for the institutes the longest are resigning due to dissatisfaction in greater numbers than newer employees. However, half of all resignations for established(7-11 years of service) and veteran (11+ years service) employees are due to dissatisfaction.

Young and older employees are resigning due to dissatisfaction with the highest groups being 26-30 year olds and employees 51 and older.
