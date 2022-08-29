# KTBT-Release
#### Note: This simulation software works only on Windows 10 and Windows 11 environments.  
Download the latest release [here (v4.2)](https://github.com/herolab-uga/KTBT-Release/releases/tag/v4.2).  
After downloading the .zip file extract all the contents to a director.  
Open the file BTTransferSimulator.exe  
**Note: If you are using an antivirus or antimalware sofware, you may have to add BTTransferSimulator.exe and LearnBTV1.exe files to the exclusion list.**  

## Simulator settings panel
![FrontEnd](https://github.com/herolab-uga/KTBT-Release/blob/master/forWiki/FrontEnd.png)

<ins> Target Type:</ins> There are four target types in the simulator that are colored red, green, yellow and blue and have four corresponding zones at each corner  
<ins>Target Counts:</ins> The number of targets of each type to be initialized in the simulations.  
<ins>Obstacles:</ins> Check to add static obstacles  
<ins>Scenario:</ins> There are currently two scenarios available for the current study 
&nbsp; 
* 'with KT-BT' and 
* 'without KT-BT'  

<ins>Robot Types:</ins> There are 3 types of robots, 
&nbsp;  
1. ignorant- that have no initial knowledge
2. multi-target - that have knowledge about all the targets
3. robots that have knowledge about red, green, yellow and blue colors.

<ins>Communication Range:</ins> The range within which it can communicate with its neighbors. This is measured in times of the size of the robot.  
<ins>Total Trials:</ins> The number of trials to conduct for data collection  
<ins>Start Count:</ins> Starting trial number count for running simulations. This is to let the user continue simulations from the point they are stopped.  
<ins>Continuous:</ins> If unchecked, simulations stop after each trial and wait for the user to press the exit button on the simulator. If checked a trial instance is closed and a new trial instance is opened automatically.  
<ins>Parallel Instance Interval:</ins> This simulator supports parallel simulation instances. If set to a value more than 1 and if the trials are greater than 1 multiple simulataneous instances are initiated. For e.g. if the trials are 10 and the max parallel instance intervals is 3, only 3 instances are open at a time.  
**Note: Multiple parallel instances might slow down the simulations, hence a PC with good processing speed and a GPU is recommended**  

<ins>Duration:</ins> The maximum number of iterations before stopping. Each iteration has a fixed time of 0.01s.  
<ins>Targets:</ins> Stop after a certain overall percentage of targets are collected.  
<ins>No Stop:</ins> Simulations do not have stopping criterion.  
<ins>Record Data:</ins> Enable this to record data  
<ins>Auto Name:</ins> Auto Names the files and folders (Recommended)  
<ins>Save Path:</ins> Choose save directory for the recorded data.  
<ins>Config. File:</ins> Parameter summary  
<ins>Simulation Control:</ins> Run Simulations -> Click to run simulations after setting the parameters.  
<ins>Pause/ UnPause:</ins> Pause or unpause all instances of simulations  
<ins>Stop Simulations:</ins> Stop all the instances/ terminates all simulation instances.  
**Note: Do not press stop simulations while the instances are initializing**







## Simulation Instance
![SimulationInstance](https://github.com/herolab-uga/KTBT-Release/blob/master/forWiki/Simuloation.png)

The simulation parameters segment in an instant shows the parameters transfered from the settings form.

<ins>Camera View:</ins> Currently there are two views available.  
<ins># Known Conditions:</ins> Counts of robots that have knowledge about each target type.  
<ins>Known Conditions:</ins> Number of robots that are ignorant (None), knowledge about 1, 2 3 and all targets respectively.  
<ins>Robot States:</ins> Number of robots in different states at a given point of time/ iteration.  
