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

# What is a GUI?
A Graphical User Interface(GUI) is the first thing your user sees and interacts with when he opens your application or website. Having a good GUI goes a long way in increasing your platform’s reputation and user count. A user interface usually includes a host of visual elements like icons, buttons, graphics, displayed text, and several other forms of input, like checkbox, text input boxes, and such.

It’s the combination of all these elements that makes up a vital part of your application or website’s user experience. Input to these visual elements can be from the usual mediums, such as keyboards, mice, and touchscreens.

# Best Python GUI Frameworks for Developers
Focussing on perfecting the user interface is a good thing but as much important it is to offer the best possible user experience, delivering it without spending an absurdly high amount of resources on it is equally important. Python has loads of frameworks for developing GUIs, and we have gathered some of the most popular Python GUI frameworks in our list that are listed below.

# 1 1. PyQt5

Developed By: Riverbank Computing

The PyQt package is built around the Qt framework, which is a cross-platform framework used for creating a plethora of applications for various platforms. The PyQt5 package includes a detailed set of bindings for Python based on the latest version v5 of the Qt application framework.

Similar to the Qt5 framework, PyQt5 is also fully cross-platform. By leveraging the power of PyQt5, developers can build applications for platforms like Windows, Mac, Linux, iOS, Android, and more.

# 2 2. Tkinter

Developed By: Fredrik Lundh
Website Link: https://wiki.python.org/moin/TkInter

Often referred to as the go-to GUI toolkit by a majority of Python developers, Tkinter was created to equip modern developers with a standard interface to the Tk GUI toolkit with its Python bindings. In Tkinter’s world, most of the visual elements that we’re familiar with are called widgets, and each of these widgets offers a different level of customizability.

Tkinter comes baked into current Python installers for all major operating systems and offers a host of commonly used elements that we’re sure you must be familiar with. Some of those visual elements have been listed below:

● Frame: for providing a structure to your application

● Buttons: used for taking input from the user

● Checkbuttons: used for making selections

● Labels: for displaying textual information

● File Dialogs: for uploading or downloading files to/from the application

● Canvas: provides a space for drawing/painting things like graphs and plots


# 3 3. Kivy
Developed By: Kivy Organization


# 4 4. wxPython
Developed By: Robin Dunn


# 5 5. Libavg
Developed By: Alfred Bigler

# Conclusion
Now, we have a wide array of GUI frameworks in Python, such as TkInter, Kivy, PyForms, and more that are designed to supercharge building user interfaces that people will love to use. 



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
 
 
 
 
 
# Step 1: Importing the necessary modules

To use the Tkinter we need to import the Tkinter module. We are also going to import the function factorial from math module.

Code:

from tkinter import *
import parser
from math import factorial

# Step 2: Making a window for our calculator
Now we are going to draft the window for our calculator which will accommodate the buttons.

Code:

root = Tk()
root.title('Calculator')
root.mainloop()

Explanation:

The above code sets the title of python calculator window as ‘Calculator’. 
When you run the above code, you will get a window like this.


# Explanation(calculator program):

In this calculator program in python, the “Entry” function helps in making a text input field and we use .grid() method to define the positioning associated with the button or input field. We use the button method to display a button on our application window.

root – the name with which we refer to our window
text – text to be displayed on the button
row – row index of the grid
column – column index of the grid
columnspan – spans or combines the number of columns
sticky – If the resulting cell is larger than the widget then sticky defines how to expand the widget.


# Explanation:

We fetch the string present on the input field using the .get() method. We now use the parse module to scan the string with the help of .expr() method which accepts the string as a parameter. We basically leave it to the parser to build an abstract syntax tree of the string which is evaluated using the eval() function.





# Summary

This is a simple calculator GUI application written in Python using the tkinter library. It has four basic arithmetic operations: addition, subtraction, multiplication, and division.

The application has an input area for two numbers and an operator, and a "Calculate" button to perform the calculation. The result is displayed on the screen after clicking the "Calculate" button.

The "calculate" function performs the calculation based on the operator entered by the user. If the operator is 1, addition is performed. If the operator is 2, subtraction is performed. If the operator is 3, multiplication is performed. If the operator is 4, division is performed. If an invalid operator is entered, the result is displayed as "Invalid operator".

The GUI elements, such as labels, entries, buttons, and result labels, are created and arranged on the screen using the tkinter library. The "mainloop" function is called to keep the GUI running and responding to user input.




# Code

import tkinter as tk

This line imports the tkinter library and renames it as "tk" for convenience.

# code

def calculate():

    first_number = int(first_number_entry.get())
    
    second_number = int(second_number_entry.get())
    
    operator = operator_entry.get()
    
    
This defines the "calculate" function, which is called when the "Calculate" button is clicked. The first two lines of the function retrieve the values of the first and second numbers from the first_number_entry and second_number_entry widgets, respectively. The third line retrieves the operator from the operator_entry widget.

# code

    if operator == "1":
    
        result = first_number + second_number
        
        result_label.config(text="Result: " + str(result))
        
    elif operator == "2":
    
        result = first_number - second_number
        
        result_label.config(text="Result: " + str(result))
        
    elif operator == "3":
    
        result = first_number * second_number
        
        result_label.config(text="Result: " + str(result))
        
    elif operator == "4":
    
        result = first_number / second_number
        
        result_label.config(text="Result: " + str(result))
        
    else:
    
        result_label.config(text="Invalid operator")
        
        
This part of the code performs the calculation based on the operator. If the operator is "1", addition is performed. If the operator is "2", subtraction is performed. If the operator is "3", multiplication is performed. If the operator is "4", division is performed. If an invalid operator is entered, the result is displayed as "Invalid operator".

# code
# GUI setup

root = tk.Tk()

root.title("Calculator")


This creates the main window of the GUI application and sets its title to "Calculator".

# code

first_number_label = tk.Label(root, text="First number")

first_number_label.pack()

first_number_entry = tk.Entry(root)

first_number_entry.pack()


These two lines create a label and an entry widget for the first number, and arrange them on the screen using the pack method.

# code

second_number_label = tk.Label(root, text="Second number")

second_number_label.pack()

second_number_entry = tk.Entry(root)

second_number_entry.pack()


These two lines create a label and an entry widget for the second number, and arrange them on the screen using the pack method.

# code

operator_label = tk.Label(root, text="Operator (1-Addition, 2-Subtraction, 3-Multiplication, 4-Division)")

operator_label.pack()

operator_entry = tk.Entry(root)

operator_entry.pack()

These two lines create a label and an entry widget for the operator, and arrange them on the screen using the pack method.

# code

calculate_button = tk

  
