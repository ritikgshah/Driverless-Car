# Driverless-Car

## Tools used: C++, Unreal Engine 4, Neural Networks, Reinforcement Learning

Project Description: In recent years, the magnitude of technological advancement has made unprecedented strides especially in the gaming and autonomous driving industries. These advancements are only possible due to cutting edge artificial intelligence and machine learning research, and thus I wanted to experiment with using reinforcement learning ( a subset of machine learning) to code a self-driving car. The entire point of this game is to see if a virtual car can effectively learn from its environment and correctly make a decision as to whether it should turn left, right, or continue straight in order to continue without a collision. A car takes actions on a race track by acting on the feedback the environment gives back to the car. The car is designed as a class of its own, and each instance of this class provides a simulation of the self-driving car. At the starting point, multiple instances of the car class are created, and they have the initialization process as mentioned in the genetic algorithm and it has to learn to drive itself. If a car gets into a collision, it stops driving. If all the cars get into a collision, a new generation of cars with new weights will be created at the starting point and continue the training process. The percentage of the track that a car completes is its accuracy, therefore I want to see if any car can achieve 100% signifying that it went through an entire lap without any collisions. The following graph of accuracy vs generation (or number of cars) tells a clear story. It is possible for a car to learn to drive itself and complete at least one lap of the track without collisions and it takes about 30 generations of cars to achieve the desired 100% accuracy.


<img width="843" alt="Screen Shot 2022-08-22 at 11 25 43 PM" src="https://user-images.githubusercontent.com/51481040/186062915-555e0b14-7824-4b6e-8b02-4ccb3bc4a57e.png">


Driverless Car Writeup.pdf contains a detailed description of the models I used and my thought process while making this project. 

To watch the video recorded while running this project which shows the car complete a full lap of the track open Driverless car.mov file.

I encountered errors while pushing to github from the command line, thus I had to upload from the website which has restrictions and thus the files are not properly structured. 
Most of the files are uasset files which are used by Unreal Engine, but cannot be viewed on github, hence I was unable to move the files into the correct folders on the github website.
If you wish to download the code for any reason please use this drive link as it has the code according to its perfect structure: https://drive.google.com/drive/folders/1XScrcDiNi1KNmM-qmu1U6nhBsDd8BDWe?usp=sharing

To run the game, you have to run the AI_Car.uproject file. Be sure to run the game only on Unreal Engine 4 (it will not work with other versions).
