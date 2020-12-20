# Newyorktimes-Project
This is the project of Hauke Schnepel, Claudio Vassallo, Dennis Philip Erni. The project exist of one notebook with all the code, one .txt-file with bestsellers2 data from the new york times, and a readme with a step by step manual.

For the functionality of the code, we kept to a large extent to the specifications of the task description. However, it was very important to us that the code runs very well and securely on the one hand, and on the other hand we wanted to refresh the input and output a little graphically. We hope that we have achieved our two goals in your opinion. 

# Instructions on how to run the code
First, the tkinter and datetime libraries must be installed. We have included two instructions below to install the two libraries. Secondly, the location in the 5th line of code must be changed to the location on the computer where the .txt file was stored. 

### tkinter
Tkinter comes pre-installed with the Python installer binaries for Mac OS X and the Windows platform. 
So if you install Python from the official binaries for Mac OS X or Windows platform, 
you are good to go with Tkinter.
For Debian versions of Linux you have to install it manually by using the following commands.
For Python 3 --> sudo apt-get install python3-tk
For Python 2.7 --> sudo apt-get install python-tk
(Source: https://riptutorial.com/de/tkinter/example/3206/installation-oder-setup)

### datetime
Python provides plenty of functionality to deal with date and time data. The standard libraries contain the following modules: time, calendar, datetime - As a result, we no longer need to install the datetime library separately and can use it directly in the code.
(Source: https://www.python-kurs.eu/python3_time_and_date.php)

### Change the path to the .txt-filde
First save the .txt-file with the bestseller data from the new york times on your local storage. Second, the location in the 5th line of code must be changed to the location on the computer where the .txt file is stored. To do this, simply change the path fh = open('Enter your path here').

### Last step
Just create a .py-file on your computer with the code in main or run it on a virtual python machine/programm. Then you just be all set. To press the run button and our graphic tkinter interface should appear.

# Instruction on how to use our search engine
It is actually quite easy to use, you can simply enter the respective data and press the corresponding search button. The respective books that match the search criteria are displayed directly below.

We hope you enjoy our little programme and are open to any suggestions and feedback.




