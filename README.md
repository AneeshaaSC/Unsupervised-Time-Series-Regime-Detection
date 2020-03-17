# Unsupervised-Time-Series-Regime-Detection
Attempt at learning Regime detection using HMM on Telematics data as opposed to the conventional regime detection on Financial data.


Introduction

We absorb telematics data from various sources and processes to enable an understanding of how a vehicle is being driven and any events that occur during the journey. This data can be volatile and can contain anomalies; this test is designed to assess your ability to clean this data and understand what it might imply.


The Challenge
The functional goal of the challenge is to analyse a number of journey files, to understand the data and:
identify the trips containing an ‘event’ that might be an accident
identify the time of the ‘event’ 	
allocate a notional severity index to each ‘event’ 	
allocate a notional confidence to the ‘event’ being an accident

The technical part of the challenge is to provide a program (in Java or Python) that can be run on this or other datasets to achieve the same results.

You should provide a report describing the methodology. The report should give consideration to the pros and cons of the solution and give reference to any alternative solutions that were considered.

The challenge will be assessed by comparing your results against known outcomes.


Objectives


Mandatory Goals:

Apply data science techniques to solve the challenge using Java or Python
Demonstrate an understanding of sensor data
Identify journeys containing an ‘event’ that might be an accident
Clearly communicate the methodology with consideration of the pros and cons of the provided solution

Desirable Goals:

Accuracy & efficiency of the program when run against a similar test set of data
Any notes considering trade offs between efficiency and accuracy
Evidence of understanding of the data
Any advanced data manipulations performed
Use of Object-oriented Programming and Unit Tests
Data Set
25 Journey files have been provided.



These contain:
Unix Epoch Timestamp
Latitude
Longitude
Altitude
Lateral accuracy
GPS Time
Speed
Accelerometer X
Accelerometer Y
Accelerometer Z

Accelerometer values are not oriented to a fixed vertical and relate to the axis of the phone that the data was sourced from. The phones are loose in the vehicle so the actual orientation can change over time.

All devices use the same GPS system but some measure the XYZ accelerometer values in G whilst others use m/s2. You will need to identify the correct unit for each journey and make any necessary adjustments.
Submission
Your submission must include:
The code and all instructions required to run your solution
A copy of the results produced by your solution
A report detailing your:
Methodology, considering the pros and cons
A description of your results and final findings - including an explanation of any scoring metrics you apply for the severity and confidence measures


