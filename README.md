# Linear Printing Robot--Hatching and Printing
This project utilizes a Lulz-Bot gantry to convert any image into a series of linear lines in a process known as hatching.

This is not a maintained project, but a more detailed description of the project with images can be found here: https://sites.google.com/view/linear-printer-robot/home

FILE DESCRIPTIONS:
 - Image_Generator.py: formats image with link in Univ_Settings.py and converts to grayscale
 - Hatch_Algorithm.py: this is the most important function. Converts the grayscale image into a matrix of lists representing print lines (hatching)
 - Unit_Reorderer.py: helper function for Main.py that reorders the lists of lines in the matrix to be printed onto sticky notes
 - GCode_Controller.py: this manages the printer. It converts the matrix to G-code and sends commands when Main.py takes user input.

(Also):
 - Main.py: main funciton
 - Univ_Settings.py: universal settings
