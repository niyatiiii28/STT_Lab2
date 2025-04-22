# STT_Lab2


CS 203: Software Tools & Techniques for AI

IIT Gandhinagar

Sem-II - 2024-25

________________________________________________________________

LAB 02 

Total: 10 Marks

Submission deadline: Sunday, 19/01/2025 11:59:59 PM

Submission guidelines:

Implement the code in google colab and share the link during submission.

The deadline will not be extended at any cost.

Note: Submitting this assignment solution confirms that you will follow the IITGN's honor code. We shall strictly penalize the submissions containing plagiarized text/code.
________________________________________________________________

Objective

This assignment aims to familiarize students with modern data validation techniques using Pandera and Great Expectations frameworks through hands-on experience with real-world fitness data. Students will learn to implement various validation rules, from basic data type checking to complex cross-column validations, while understanding the strengths and limitations of each framework. 
Dataset Preparation

1. Download the data from “https://s3.amazonaws.com/tripdata/202412-citibike-tripdata.zip” using the curl or wget command.


2. Key fields to validate:
   - ride_id (string)
   - rideable_type (categorical)
   - started_at (str)
   - ended_at (str)
   - start_station_name (string)
   - start_station_id (string)
   - end_station_name (string)
   - end_station_id (string)
   - start_lat, start_lng (float)
   - end_lat, end_lng (float)
   - member_casual (categorical)
  
     
Features to Implement
Pandera Validation Rules:
Validate the datatype of each column. [20%]

Analyze each feature and write an appropriate check/scheme for them. For example, for “rideable_type” check the unique options and ensure that no other entry passes the check. [20 %]

Add data validation rules to verify that a ride's end time occurs after its start time using Pandera's decorator functionality. [10 %]

Great Expectations Suite:
Validate the datatype of each column by creating an expectation suite. [20 %]

Implement an Action that will send a mail when encountering a failure. Take a screenshot of the mail and attach it to the submission file. [20 %]

Code Quality:
Maintain clean, modular, and readable code. [5 %]
Provide comments where necessary. [5 %]
















*****Best of Luck*****
