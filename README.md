# Part 1 

## Accompanying resources
* Slide deck: https://zipcoder.github.io/curriculum-assets/lectures/python/types-operators-strings-comments/
* Metric Conversion charts: https://www.metric-conversions.org/

## Exercise 1

* Open Terminal. # can be in PyCharm or in zsh/bash/terminal
* Launch the Python interpreter. # enter python3 into cmd line
* Print a line that says "Hello Python". # print("Hello Python")
* Exit the Python interpreter.

## Exercise 2

* Using the Python interpreter, identify the data type for the following values:
    * True # class <'bool'> meaning Boolean
    * 42 # class <'int'> meaning Integer
    * False # class <'bool'> meaning Boolean
    * 1.5 # class <'float'> meaning floating point number
    * "Python is fun" # class <'str'> meaning String
    * "3.5" # class <'str'> meaning String

## Exercise 3

* Using the Python interpreter, perform the following operations. Be sure to experiment with mixing intergers and floats.
    * Addition # >>> 3 + 56 # 59
    * Subtraction # >>> 59-69 # -10
    * Multiplication # >>> -10*2 # 20
    * Division # >>> 20/5 # 4
    * Floor division # >>> 256//3.14 # 81.0
    * Modulo # >>> 256%5 # 1
    * Exponentiation # >>> 2**2**2 # 16

## Exercise 4

Create a Python script called *first_name_500_times.py*. Modify your script according to the instructions below.

* Declare a variable called *first_name* with your first name as its value.
* Print the value of *first_name* to the screen 500 times.
* Save & execute the script.

## Exercise 5.a

* Using Terminal, make a copy of *first_name_500_times.py* and call it *full_name.py*

```
cp first_name_500_times.py full_name.py
```

## Exercise 5.b

Modify *full_name.py* according to the instructions below.

* Comment out the line where your first name was printed 500 times.
* Create a variable called *last_name* with your last name as its value.
* Create a variable called *full_name* whose value is the combination of the *first_name* variable and the *last_name* variable.
* Print the value of the *full_name* variable.

## Exercise 6

Create a Python script called *fahrenheit_to_celsius.py*

* The script should declare a variable called fahrenheit.
* The script should then convert the value of fahrenheit to celsius.
* The conversion should be displayed on the screeen in the following format:
"32 degrees fahrenheit is equal to 0.0 degree(s) celsius"
