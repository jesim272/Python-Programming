Jesi Miranda-Santos


A14989720

# Lab 1
#
## Introduction
#
The objective of this lab was to be introduced to the programming environments that we will be using
throughout the quarter, Spyder and Arduino, and to become familiar with turning in assignments using
GitHub. Moreover, this lab introduced us into programming in Python and programming the Arduino.
#
### Objective 1
#
##### Part 1A
#
1. The goal of the objective was to download and install Anaconda/Python, Github, and Arduino IDE.
2. For Anaconda/Python installation, I went to the site: https://www.anaconda.com/download/, selected 
the Windows version of the package and downloaded it.
  
    For the Github, I went to the site: https://gitforwindows.org/ , and clicked on the "downloaded" button 
    to download and install the file to get Git Bash.
  
    For the Arduino IDE, I had it already installed in my computer.
      
##### Part 1B
#
1. The goal of this objective was to introduce us to soldering and to understand the types of equipment that
might be used during the duration of the quarter. Moreover, the goal is to learn, as well, how to properly solder,
what type of material is used to solder, and how to use/remove solder.

2. Before I began soldering, I had to go to the envision website: http://jacobschool.ucsd.edu/envision/access.shtml/
and enter into the "Student Portal and Trainings". Once here, I selected "Training" and began watching the introduction
videos about the machines in the MakerSpace. After watching the videos, I took an assessment test, to have clearance to
use the lab space. 

    After I gain access to use the lab space, I proceeded to soldering the board and the pins that were given to me. I
  took a picture of the solder and uploaded it into the file named "Images".
  
  ![Images](https://github.com/UCSD-Product-Engineering/ece16-sp19-jesim272/blob/master/ECE_16/Lab%201/Images/Soldered%20Board.jpg "Soldered Board")
  
  
#
### Objective 2
#
1. The goal of this objective is to learn and create a simple python file using Spyder and the Anaconda Prompt
2. To create and run a file in python using the Anaconda Prompt, I opened a text editor and typed in two line of 
code that was provided:

      `txt = "Hello World" `
      
      `print(text) `
      
  After saving the file as "hello.py", I opened the Anaconda prompt and entered the directory at which my file was stored and
  and ran the file using the command provided `python hello.py `
  
  To create file in Spyder, I opened the application and and wrote the same two lines of code. I save the file as
  "hello2.py". To run the program, I clicked on the "Run File" (or F5).
  
  
  #
  #### Objective 3
  #
  1. The goal of this objective is to introduce us to the programming environment for the Arduino and interface with the
  board to write a simple program to make the LED on the Arduino blink.
  2. Following the instructions provided. I connected the board to my computer and on the Arduino application, I accessed 
  **File->Examples->Basics->Blink**, which opened the example code for LED to blink.
  
     After compiling the code and uploading it to the board, I saw that the LED was turning on and off.
     The code begins by initializing the global variables (if provided) and then moving into *void setup()*, where all the
     pins and the serial monitor is initialized. By default to access the LED 13, the code has a defined variable BUILTIN_LED.
     Moreover, the parameter *OUTPUT* provided that the pin 13 will output voltage to the LED, so that it may turn on.
     Once the *void setup()* runs, the program moves on to follow the *void loop()*, where the loop inside this function will
     repeat indefinitely. Here the LED is turned on by providing the second parameter at *HIGH* or *LOW* to *digitalWrite*. The *delay*
     function pauses the code for the specified time and then proceeds to continue to repeat all the step again.
  
  
  #
  #### Objective 4
  #
  1. The goal of this objective is to create an account on GitHub, access the classroom folder, and learn git commands to create,
  make, push, pull, and commit files to GitHub to be able to turn in assignments. 
  
  2. I had a GitHub account made, so I used the link that was provided to access the classroom folder. Moreover, I had previously 
  downloaded and installed git for Windows. Hence, I used the Git Bash application to create a repository for the files that I was
  going to submit as requested. All the work that I had done for Objectives 1-3, were organized in a comprehensive way such that files
  were neatly placed in their repective folders, emulating the template provided in the PowerPoint slide of Lab 1.
