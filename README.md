# Frequency Ratio Calculator

## First-Time Setup and Execution
Press the windows key on your keyboard, type in "Anaconda Prompt" and hit enter.
In the terminal screen that appears, enter the following command:

(In the Anaconda Prompt you can paste with right-click)

	cd Documents
 
Then,

	git clone https://github.com/NETL-RIC/Freq_Ratio_Calculator/tree/master
 
Then, 

	cd Freq_Ratio_Calculator
 
Then,

	conda create -n frc --file ./virtual-env/frc-xplct.txt
 
Then,

	conda activate frc
 
Finally,

	python fr_calc_main.py

## Executing Again After Setup
To run the calculator after first-time setup (you don't need to clone the repo and the virtual environment again), do the following.
Press the windows key on your keyboard, type in "Anaconda Prompt" and hit enter.
Enter the following commands:

	cd Documents
 
Then, 

	cd Freq_Ratio_Calculator
 
Then, 

	conda activate frc
 
 Finally,
 
	python fr_calc_main.py
 
