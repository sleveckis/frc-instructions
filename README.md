# Frequency Ratio Calculator

## First-Time Setup and Execution

Unzip the frc.zip file at the address below into your Documents folder on your C: drive.

	P:\05_AnalysisProjects_Working\EDX4CCS\Task2.2\frc

After unzip, there should be a folder called 'frc' in your Documents folder.

Press the windows key on your keyboard (or click the windows icon on the bottom left corner of your screen), type in "Anaconda Prompt" and hit enter.
In the terminal screen that appears, enter the following commands:

*Note: In the Anaconda Prompt you can paste with right-click*

First, point the Anaconda Prompt to the project folder:

	cd %USERPROFILE%\Documents\frc\Freq_Ratio_Calculator-master

*If you get a "The system cannot find the path specified" error, verify that the 'frc' folder does exist in your documents folder on your C drive.*
 
Then, to create the virtual environment we need in the project folder:

	conda create -n frc --file ./virtual-env/frc-xplct.txt
 
Then, to activate the virtual environment:

	conda activate frc
 
Finally, to run the program:

	python fr_calc_main.py

These commands will have created the project folder in your Documents folder. Because the project folder downloaded is a git repository, if any future changes are made to the project, it will be trivial to "pull" them to your machine with git instead of re-downloading them and moving files around manually. 

## Executing Again After Setup
To run the calculator after first-time setup (you don't need to clone the repo and the virtual environment again), do the following.
Press the windows key on your keyboard, type in "Anaconda Prompt" and hit enter.
Enter the following commands:

	cd %USERPROFILE%\Documents\frc\Freq_Ratio_Calculator-master
 
Then, 

	cd Freq_Ratio_Calculator
 
Then, 

	conda activate frc
 
 Finally,
 
	python fr_calc_main.py
