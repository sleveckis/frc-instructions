# Frequency Ratio Calculator
## Distribution 

Instead of using git, it has been easier to just copy and paste the source code from P(10.50.10.198)://05_AnalysisProjects_Working/EDX4CCS/Task2.2/frc/Frequency_Ratio_Calculator into your personal Documents folder.

Any updates will be pasted into that P: drive location, which will then need to be re-pasted into the user's Documents folder and overwrite the existing source code.

## Setup

You'll first need to create a python virtual environment to run the code. This can be done using a file in the source code. It is presupposed that you have Anaconda installed

Press the windows key on your keyboard (or click the windows icon on the bottom left corner of your screen), type in "Anaconda Prompt" and hit enter.
In the terminal screen that appears, enter the following commands:

#### Virtual Environment 
First, point the Anaconda Prompt to the project folder:

	cd %USERPROFILE%\Documents\Frequency_Ratio_Calculator\

 *If this command did not work, ensure you have a folder called 'Frequency Ratio Calculator" in your Documents folder

 Then, check if you already have the virtual environment before adding a new one, with:

 	conda env list

  If there is no entry called 'frc' in the results, create the environment:

	conda create -n frc --file ./virtual-env/frc-xplct.txt

 This will create the environment and name it frc, which you can double-check with 'conda env list' again if you wish.

## Running the Program

First, point the Anaconda Prompt to the project folder:

	cd %USERPROFILE%\Documents\Frequency_Ratio_Calculator\

 Then, activate the virtual environment:

 	conda activate frc

 Finally, run the program

 	**python fr_calc_main.py**
