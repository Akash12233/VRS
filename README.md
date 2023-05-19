# VRS
A Vehicle Management System is a software application or platform designed to streamline and automate various aspects of managing a fleet of vehicles. It is commonly used by businesses or organizations that rely heavily on transportation, such as logistics companies, delivery services, rental car companies, or large corporate fleets. 
erent types of vehicles on rent to customers which includes
1. Bike
2. Car
3. Bicycle
4. Scooter
The complete program of this project is in Python language and we use Object-Oriented
Programming approach to reduce complexity and number of lines in programme. Another major
highlight in our project is GUI interface which we created with the help of Tkinter module in
Python.
Following are some of the modules and libraries we used:
1. Tkinter:-
S. No. Name of Students Roll No.
1 Aditya Jadhav BT21ECE082
2 Vedant Lokhande BT21ECE083
3 Akash Tayade BT21ECE085
4 Himanshu Kohade BT21ECE086
2
➢ Tkinter is the standard GUI library for Python. It provides a powerful object –
oriented interface to the Tk GUI toolkit.
2. Python sqlite3: -
➢ Python sqlite3 is an excellent module with which you can perform all possible
DataBase operations within memory and persistent database in your applications.
➢ In our project we connect a database file “Users.db” to Python with help of sqlite3
module.
3. random: -
➢ It is a python module to generate random numbers.
➢ In our project we used this module for generating reference number and receipt
number.
4. datetime: -
➢ This module supplies classes to work with current date and time.
5. openpyxl: -
➢ It is a python module which is used to read data from an excel file or write to an
excel file. A spreadsheet is represented as a workbook in openpyxl.
Programme for Vehicle Rental System is divided into 3 main classes. Those are as follows: -
1. user class: - Useful methods (functions) in this class are discussed below:
• login: - User enters username and password. If it matches with data in
database, the user logins successfully. If not, throws error that username
not found.
• new_user: - User can create account by setting new username and
password and will then able to login.
• widgets: - This method packs the above two methods in beautiful GUI
interface.
2. list class: - Useful methods (functions) in this class are discussed below:
• LOV: - Displays the list of all 4 types of vehicles i.e. Bike, Car, Bicycle,
Scooter.
• Bike/ Car/ Bicycle/ Scooter: - Displays all models of every Vehicle type
by reading “Vehicle.xlsx” file using openpyxl module.
• RAV: - Gives option to user to return a vehicle which he rented initially.
• logout: - Gives option to user to logout and terminate the programme.
3
• checkSrNo: - Gives option to user to enter serial number of vehicle model
he rented. If it matches then allow user to proceed with payment else
throws an error.
3. ReturnVehicle Class: - Useful methods (functions) in this class are discussed below:
• Damage_chk: - Add damage cost to final bill amount if there is any
damage in vehicle.
• iExit: - Gives option to exit and terminate the programme.
• Receiptt: - Creates buttons and entry widgets for getting user details.
4. afterselectingVehicle: -
• This class has programme for printing user details entered by user in entry
widgets and print it in receipt.
• For calculation of final bill amount to be paid by user.
• Reset option to clear all details entered by user in entry widgets.
• Back( ) method for going to back to window with “Return a Vehicle”
option.
