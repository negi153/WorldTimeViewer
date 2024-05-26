# WorldTimeViewer
World Clock Timezone Viewer is a desktop application designed to display the current time for every timezone around the globe. Built using Python for the backend and PyQT Designer for the GUI, this software provides an intuitive and user-friendly interface for viewing timezones.

![Python](https://img.shields.io/badge/Language-Python3.9-green)
![PyQt-Designer](https://img.shields.io/badge/UI-PyQt_Designer-orange)

## Preview

https://github.com/negi153/WorldTimeViewer/assets/27079205/9d1aa748-65d5-4c22-b061-9057a836b7ac

## Features
1. Comprehensive Timezone Display
    - Real-time Updates: Shows the current time for all timezones, updating in real-time.
    - Full Timezone List: Includes all major timezones, ensuring comprehensive global coverage.
2. User-friendly Interface
    - Intuitive Design: Clean and easy-to-navigate interface designed with PyQT Designer.
 
## Installation

1. Clone the repository:
   
   `git clone https://github.com/negi153/WorldTimeViewer.git`

2. Install dependency modules

    `pip3 install -r requirements.txt`

## How to execute
1. Execute below command to run the code
    
    `python timezone_clock.py`


## Additional Details
1. How to start Pyqt Designer?

    Open `cmd` and type `designer`

2. Execute below command if you want to create a executable file for this program

    `pyinstaller -n "Task Planner" --add-data="task_manager_home_page.ui;." --noconsole --onefile task_manager.py`


3. Convert <filename>.ui file to <filename>.py
    
    `pyuic5 -x <filename>.ui -o <filename>.py`

4. Command to create executable file.
	
    `pyinstaller -n "<filname>" --noconsole --onefile <filename>.py`
    
    where 
    - -n : name of executable file
    - --noconsole : hide black cmd which comes during execution of program
    - --onefile : will create only single execution file 

## References
Tutorial : [PyQt Designer Tutorial](https://www.pythonguis.com/pyqt5-tutorial/)
