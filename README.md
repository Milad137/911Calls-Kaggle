
# 911 Calls Project
Analyzing some 911 call data from Kaggle. The data contains the following fields:

lat : String variable, Latitude
lng: String variable, Longitude
desc: String variable, Description of the Emergency Call
zip: String variable, Zipcode
title: String variable, Title
timeStamp: String variable, YYYY-MM-DD HH:MM:SS
twp: String variable, Township
addr: String variable, Address
e: String variable, Dummy variable (always 1)

# Contents

## 1) Data Clean-Up
* Creating columns 'Reasons', 'Issue', and 'Station' based on 'descr' and 'title'
* Droping 'desc','title','twp','addr','e' columns
* Finding missing 'zip' with the help of 'lat' and 'lng'
* Filling missing data of 'Station'
* Creating columns 'Hour','Month','Day of Week', 'Date' from 'timeStamp'

## 2) Data Analysis
* 911 Calls - Zip Code Distribution on Call Reason
* 911 Calls - Date (Year - Week) of Occurrence on Call Reason
* 911 Calls - Call Issue on Call Reason
* 911 Calls - Total Daily on Call Reason
* 911 Calls - Total Monthly on Call Reason
* 911 Calls - Total Monthly Trend
* 911 Calls - Heatmap of Day Time vs Day of Week
* 911 Calls - Heatmap of Day Time vs Month
* 911 Calls - Total Day Time on Call Reason
