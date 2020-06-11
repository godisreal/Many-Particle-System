# Multi-Agent Simulation of Collective Behavior

Group Social Force is implemented with Interactive Opinion Dynamics.  This model is an extension of the social force model introduced by Helbing and Molnár (1995) and Helbing, Farkas, and Vicsek (2000). 
The fundamental idea is demonstrated as below in a feedback style. The model aims at investigating protypes of pedestrian behavior in a general sense. The current version of model especially contributes to simulating the crowd behavior in evacuation scenarios.

![](https://github.com/godisreal/Many-Particle-System/blob/master/FigNew.PNG)

In the repository there are several small examples to test protypes of the model.  The examples were intially written in Python 2.7, and you need to slightly modify the code if you want to run it in python3.  Pygame and Numpy are required to run the code. 
How-To: python simulator_XXX.py

The latest version of code is in 2Path  
A complete simulation package is in the following repo.  Comment and suggestion are appreciated!  
https://github.com/godisreal/CrowdEgress

You can also check the video file pre-evac2.swf to browse the simulation result in the latest version.  
https://github.com/godisreal/group-social-force/blob/master/pre-evac2.swf

Thank Shen Shen for his original work on Social Force Model.  This repo was initially built up based on Shen Shen's code.  
https://github.com/dslwz2008/SocialForceModel

Pull requests welcome!

### Current Version: 

![](https://github.com/godisreal/group-social-force/blob/master/Pre-Evac2/pre-evac2b.PNG)

### Walls are abstracted in type of lines and specified in Wall_Data2018.csv
<Start X, Start Y>: 	Start Point 
<End X, End Y>: 		  End Point 

### Agents are specified in the Agent_Data2018.csv
<InitalX, InitialY>: 	Initial Positions  
<DestX, DestY>: 		  Destination Positions  
acclTime: 				    Relaxation Time in Social Force Model  
tpre: 					      The TPRE Time in the Pre-Evacuation Stage  

In advance mode I start to use obstData2018.csv and Door_Data2018.csv, where the walls and doors are considered as rectangular areas.  
Several things to do to improve existing work!  
Maybe I should write a brief manual in the future.  Commets are much appreciated!
