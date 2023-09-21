# Student data entry application
This Python program helps you manage and process student data. You can input information about students, such as their name, class, stream, and percentage. The program validates the data and saves it to CSV files. It also calculates and assigns grades based on the percentage.
# How to use the program 
Input Student Data

Enter student details as prompted:  

Student Name: (Enter the student's full name)  

Class: (Enter '10th' or '12th')  

Stream: (Enter 'Science' or 'Commerce')  

Percentage: (Enter a number )  

# Data Validation
The program checks if the data is valid:  

The name should contain only letters.  

Class should be '10th' or '12th'.  

Stream should be 'Science' or 'Commerce'.  

Percentage should be a number.  

Invalid data is saved separately.
# Saving Data
Valid student data is saved to a file named studentinputdata36.csv.  
Invalid data is saved to the same file. 
Processed valid data is saved to studentoutputdata36.csv.  
# Grades
The program assigns grades based on percentage:  
Less than 35%: 'F'  
35% to 44%: 'C'  
45% to 59%: 'B'  
60% to 74%: 'A'  
75% and above: 'A+'  
