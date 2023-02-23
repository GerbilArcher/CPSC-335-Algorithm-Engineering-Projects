//==============================================================
//CPSC-335-04 (13772) Scheduling Assignment (Project 1)
//Document:       Project 1 Readme.md (Readme File)
//Due Date:       9/24/2021
//Term:           Fall 2021
//Also Attached:  schedule.cpp (C++ Code File)
//==============================================================

Project Overview:

This is the Readme file for Project 1 program submission for CPSC 335 Alorithm Engeneering. The project program takes pre-formatted schedule files, reads them into memory, and outputs available meeting times to the console. The program is written in C++ coding language and accepts formatted .txt files.  It follows the instructions and parametrs given in the instructor-provided document entitled "CPSC 335_Project 1 Description.pdf". 


Description:

This program accepts .txt files containing the schedules of one or more people (including their daily availability start and end times) along with a meeting duration.  If there are gaps that exist in every persons' schedule that will allow for a meeting of the given duration, this program will output the start and end times of those schedule gaps to the console.  Input files must be in the following format with variable text shown in parentheses:

person1_Schedule = [['(START TIME 1)', '(END TIME 1)'], ['(START TIME 2)', '(END TIME 2)'], ['(START TIME 3)', '(END TIME 3)']]
person1_DailyAct = ['(DAILY START TIME)', '(DAILY END TIME)']

person2_Schedule = [['(START TIME 1)', '(END TIME 1)'], ['(START TIME 2)', '(END TIME 2)'], ['(START TIME 3)', '(END TIME 3)']]
person2_DailyAct = ['(DAILY START TIME)', '(DAILY END TIME)']
duration_of_meeting = (MEETING DURATION)


Example Input:

person1_Schedule = [['7:00', '8:30'], ['12:00', '13:00'], ['16:00', '18:00']]
person1_DailyAct = ['9:00', '19:00']

person2_Schedule = [['9:00', '10:30'], ['12:20', '14:30'], ['14:00', '15:00'], ['16:00', '17:00']]
person2_DailyAct = ['9:00', '18:30']
duration_of_meeting = 30


Example Output:

[['10:30', '12:00'], ['15:00', '16:00'], ['18:00', '18:30']]


User Instructions:

When the program is compiled and launched it will propmt the user to enter a file path for the formatted input file.  When the user types the file path into the prompt and hits "Enter", the program will process the input from the text file and then display the program output in the console.
