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

# What is TKinter?

Tkinter is a built-in Python module for developing a GUI application. It's easy to use and shipped as a package with Python. We can visualize our data with GUI applications.

Tkinter is included with standard Linux, Microsoft Windows and macOS installs of Python. The name Tkinter comes from Tk interface. Tkinter was written by Steen Lumholt and Guido van Rossum, then later revised by Fredrik Lundh. Tkinter is free software released under a Python license.

Tkinter is a Python binding to the Tk GUI toolkit. It is the standard Python interface to the Tk GUI toolkit,[1] and is Python's de facto standard GUI.[2] Tkinter is included with standard Linux, Microsoft Windows and macOS installs of Python.

The name Tkinter comes from Tk interface. Tkinter was written by Steen Lumholt and Guido van Rossum,[3] then later revised by Fredrik Lundh.[4]

Tkinter is free software released under a Python license.[5]

# Why Tkinter?

Python, when combined with Tkinter, provides a fast and easy way to create GUI applications. Tkinter provides a powerful object-oriented interface to the Tk GUI toolkit. Creating a GUI application using Tkinter is an easy task. 

# All you need to do is to follow the steps listed below:

# Import the module Tkinter
# Create the GUI application's main window.
# Add one or more widgets like Button, Radiobutton, Checkbutton, Canvas, Menubutton, etc. 
# Apply the event Trigger on the widgets.
# All Tkinter widgets have access to specific geometry management methods to organize widgets throughout the parent widget area.
# We can use standard attributes like color, size, etc.
# Some of the Tkinter applications that will be creating in this course:

GUI Calculator:
The GUI-based simple calculator can be created using the Python Tkinter module (Creating a Calculator Using Tkinter), which can perform basic arithmetic operations, i.e., addition, subtraction, multiplication, division, etc. 

# Methods 

Here in the first line we import everything from the tkinter module. We create a root window in the second line. In the third line we specify the root and what labels we are deciding to put into the root. Here it is just a text. Then to pack the label to the window we use w.pack(). To start the execution with the event looping, we use root.mainloop()

• Geometry manager or Layout manager of tkinter uses

• pack() method

• grid() method

• place() method

Pack- The pack() method in geometry manager organizes and place the widgets in blocks before putting them in the parent widget.

Fill- Fill is used to specify if it takes the space allocated to it or to change if extra space is allocated. Fill method used X and Y attribute to set the space in window.

Grid-This separates the parent widget into a table like structure with rows and columns in them with each part contributed to a widget.Grid method used row and column attribute to set the widget in window.

# What is root window?

the root window into which all other widgets go. It is an instance of the class Tk, and every tkinter application must have exactly one instance of this class. app is an instance of the class App, which is a subclass of Frame


# Button, methods & Variables

# Button


 ● Button is a standard widget in python tkinter. If the button is clicked, some mouse action is started.
 
● They can also contain text and images like labels.

● While labels can display text in various fonts, a button can only display text in a single font.

● The text of a button can span more than one line.

● It contain the attribute like text which help to set text in button.

● With the help of width attribute ,button size can be change.

● With the help of command attribute you can add functionality in button.

# Tkinter Variables

There are 4 type of tkinter variable as mentioned in below lines: BooleanVar()-It used to store Binary values.

StringVar()-It used to store string values.

IntVar()-It used to store integer values.

DoubleVar()-It used to store float type values.

# Methods

Geometry method can help to change the dimension of gui window. Entry method can help to take input from user in gui screen.
Get method is used to get the data from tkinter variable.




# Partial

 ● Partial functions allow us to fix a certain number of arguments of a function and generate a new function.
  
