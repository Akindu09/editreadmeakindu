# ECOR 1042 Winter 2021 README for the data analyzer project
## Project version 1.0 9/12/2022
### Email:keziafulukwe17@gmail.com

# Description:
# ___________

# The first step of the project is to create a low data module by loading the data into a data structure. Using text processing, you will create a dictionary and fill it with the student data whilst also calculating each student's average grade (G_Avg) and including it in the dictionary. Then we will undergo unit testing to make sure the functions work properly hence manipulation of the data can begin. To manipulate the data we will convert the dictionaries created before into lists of students and furthermore use more functions to sort the students out by various different attributes which will then lead to the creation of the Sort Module which will contain different histograms with the students data by polynomials that undergo either regression or interpolation to get the polynomial that best fits the data. Then we optimize the data along with the equation of the polynomial of best fit to find the minimum and maximum of the given data using different methods and libraries. We will create two user interfaces where the first UI will take inputs directly from the terminal to execute commands whereas the second one will be a batch user interface.

# This project is made up of these files :
-  T020_M1_load_data.py,
-  T020_M2_sort_plot.py,
-  T020_M3_optimization.py,
-  T020_M3_text_ui.py,
-  T020_M3_batch_ui.py

# Installation:
# ————————— 

# Python3.7.3 or later must be installed to run properly
# The external modules to be installed with the file and libraries needed:



# Usage:
# __________

# > python T020_M1_load_data.py
# this file contains 6 different functions that load the data stored in a file into the program

# > python T020_M2_sort_plot.py
# this file contains five different functions to sort, fit and plot data previously loaded into a dictionary using the load_data module

# > python T020_M3_optimization.py
# this file contains two functions 
- maximum: maximum uses the curve_fit function developed in Lab 5 to find the 2nd order regression polynomial that best fits the data and calculates the maximum of that curve. 
- minimum: minimum uses the curve_fit function developed in Lab 5 to find the 2nd-order regression polynomial that best fits the data and calculates the minimum of that curve.

# > python T020_M3_text_ui.py
# The L)oad file command allows the user to select and read the dataset file (i.e., enter the file’s name to be loaded), and select the key to be used for loading the data. The loaded data must include the average grades for each student.
# The commands S, H, W, and B will ask the user to enter an attribute to select the specific analysis the user wants to perform.
# The Q)uit command terminates the program.

# > python T020_M3_batch_ui.py
# The batch UI will use all the same commands as the text UI and should function nearly identically. The difference is that the input will be taken from a text file.
#  a text file containing the following values will load ‘studentmat.csv’, sort the data by health, output the best Age for grades, output the worst Health for grades, and display a histogram looking at students’ StudyTime’.
- L;student-mat.csv
- s Health N
- b Age
- w Health
- h StudyTime

# Credits 
# _________

# Lab 3 distribution :
- Function 1(student_schools_dictionary): Giovanni Utano
- Function 2(student_health_dictionary): Maria Parkhomchuk
- Function 3(Student_age_dictionary): Kezi Afulukwe
- Function 4(student_failures_dictionary): Akindu Silva 
- Function 5(load_data): Kezi Afulukwe
- Function 6(add_average): Giovanni Utano

# lab 4 distribution :
- Test 1(Dictionary Keys): Giovanni Utano
- Test 2(Dictionary Values- Size of lists): Maria Parkhomchuk
- Test 3(Dictionary Values- Individual student entries): Kezi Afulukwe
- Test 4(add average): Akindu Silva

# lab 5 distribution :
- Function 1(student_list): Kezi Afulukwe
- Function 2(students_bubble): Maria Parkhomchuk
- Function 3(sort_students_selection): Giovanni Utano
- Function 4(curve_fit): Akindu Silva
- Function 5(histogram): Sagarika Gupta

# lab 6 distribution :
- Function 1(minimum): Sagarika Gupta
- Function 2(maximum): Maria Parkhomchuk
- Module 1(Text user interface): Kezi Afulukwe
- Module 2(batch user interface): Giovanni Utano
- Readme.md: Akindu Silva

# License
# __________

# """ 
MIT License

Copyright (c) 2022 Akindu09

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
# """


