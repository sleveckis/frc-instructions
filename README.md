# Frequency Ratio Calculator

## First-Time Setup and Execution (Using Git)

First, go to your Freq_Ratio_Calculator-master folder at Documents/frc/ and delete it. This is the folder you manually pasted a little while ago. You should still have a folder called 'frc' in your Documents folder, and it should be empty. 

Press the windows key on your keyboard (or click the windows icon on the bottom left corner of your screen), type in "Anaconda Prompt" and hit enter.
In the terminal screen that appears, enter the following commands:

First, point the Anaconda Prompt to the project folder:

	cd %USERPROFILE%\Documents\frc\
 
*Note: In the Anaconda Prompt you can paste with right-click*

Then, clone the repository with git

	git clone https://github.com/NETL-RIC/Freq_Ratio_Calculator.git

 This should create a valid path along /Documents/frc/Freq_Ratio_Calculator

## Creating the Virtual Environment

In your Anaconda Prompt, enter the command 

 	conda env list

If you don't see an entry called "frc" in the list displayed, then follow the steps below to create a virtual environment. Otherwise, you can skip to "Executing Again After Setup" below.
 
To create the virtual environment in the project folder:

	conda create -n frc --file ./virtual-env/frc-xplct.txt
 
Then, to activate the virtual environment:

	conda activate frc
 
Finally, to run the program:

	python fr_calc_main.py

These commands will have created the project folder in your Documents folder. Because the project folder downloaded is a git repository, if any future changes are made to the project, it will be trivial to "pull" them to your machine with git instead of re-downloading them and moving files around manually. 

## Executing Again After Setup
To run the calculator after first-time setup (you don't need to clone the repo and the virtual environment again), do the following.
Open up your Anaconda Prompt and enter the following commands:

First,

	cd %USERPROFILE%\Documents\frc\Freq_Ratio_Calculator
 
Then, 

	conda activate frc
 
 Finally,
 
	python fr_calc_main.py

## Updating the Frequency Ratio Calculator

Periodically there will be bugfixes and changes to the FRC. Thankfully with git, incorporating these is very simple. First, open up your Anaconda Prompt. 

Then, navigate to your FRC folder with the following command:

	cd %USERPROFILE%\Documents\frc\Freq-Ratio-Calculator

Then, download all the changes automatically with one command:

 	git pull

Note that it is ok to do this at any time, the worst that will happen is that git will inform you that there are no changes to be pulled.


