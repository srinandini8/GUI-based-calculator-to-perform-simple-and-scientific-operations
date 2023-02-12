# GUI-based-calculator-to-perform-simple-and-scientific-operations


# write a python program using tkinter to create a GUI for simple calculator which can perform basic arithmetic operations like addition, subtraction, multiplication or division depending upon the user input.
 

# Hints:
Users choose the desired operation. Options 1, 2, 3, etc are valid.

Two (or more) numbers are taken and an if…elif…else branching is used to execute a particular section.

Using functions like add(), subtract(), multiply(), divide(), hcf(), lcm(), power(), log(), etc. to evaluate respective operations.



## 2nd way program 
In this program, the user inputs two numbers in the fields and selects the desired operation from the dropdown menu. When the "Evaluate" button is pressed, the selected operation is evaluated using the corresponding function and the result is displayed in the output field.


# 3rd way program
This program uses tkinter to create a GUI for a simple calculator that performs basic arithmetic operations. The user can choose the desired operation by entering a number (1, 2, 3, or 4) in the "Operator" field. The calculate function evaluates the expression and displays the result in a label.

# Methods 

Here in the first line we import everything from the tkinter module. We create a root window in the second line. In the third line we specify the root and what labels we are deciding to put into the root. Here it is just a text. Then to pack the label to the window we use w.pack(). To start the execution with the event looping, we use root.mainloop()
• Geometry manager or Layout manager of tkinter uses
• pack() method
• grid() method
• place() method
Pack- The pack() method in geometry manager organizes and place the widgets in blocks before putting them in the parent widget.
Fill- Fill is used to specify if it takes the space allocated to it or to change if extra space is allocated. Fill method used X and Y attribute to set the space in window.
Grid-This separates the parent widget into a table like structure with rows and columns in them with each part contributed to a widget.Grid method used row and column attribute to set the widget in window.
