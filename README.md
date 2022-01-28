# ae_attendances_modelling

This repository contains the raw data and a python notebook to ingest historical A&E attendance data and then use a simple Prophet model to predict the number of A&E attendances in England if the COVID-19 pandemic had not happened. The predicted A&E attendance values from (2020-01 to 2021-12) are then compared to the actual data to quantify the impact of the pandemic on A&E attendances.

Raw monthly A&E attendance data sourced from NHS England; [HERE](https://www.england.nhs.uk/statistics/statistical-work-areas/ae-waiting-times-and-activity/)

Further infromation of AE attendance data can be found [HERE](https://www.england.nhs.uk/statistics/wp-content/uploads/sites/2/2019/07/AE-Attendances-Emergency-Definitions-v4.0-final-July-2019.pdf)


## Percent difference in actual total A&E attendances vs. predicted attendances during the course of the COVID-19 Pandemic

![alt text](https://github.com/mattia-ficarelli/ae_attendances_modelling/blob/main/images/percent_difference_actual.png?raw=true)