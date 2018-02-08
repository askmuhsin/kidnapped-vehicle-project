# Particle Filter
This project implements a particle filter to track a car in real time with high accuracy using noisy sensor data. Particle filters are powerful sampling-based learning algorithms, they belong to the Bayesian family of filters.
They are easy to implement(compared to some other loclization filters), continous, and capable of having multimodal beliefs. 
To know more about the applications of particle filter in robotics visit this [link](http://robots.stanford.edu/papers/thrun.pf-in-robotics-uai02.pdf).

---
## Project Introduction
Your robot has been kidnapped and transported to a new location! Luckily it has a map of this location, a (noisy) GPS estimate of its initial location, and lots of (noisy) sensor and control data.

In this project you will implement a 2 dimensional particle filter in C++. Your particle filter will be given a map and some initial localization information (analogous to what a GPS would provide). At each time step your filter will also get observation and control data. 

---
## Running the Code
This project involves the Udacity Term 2 Simulator which can be downloaded [here](https://github.com/udacity/self-driving-car-sim/releases)

This repository includes two files that can be used to set up and intall uWebSocketIO for either Linux or Mac systems. For windows you can use either Docker, VMware, or even Windows 10 Bash on Ubuntu to install uWebSocketIO.

Once the install for uWebSocketIO is complete, the main program can be built and ran by doing the following from the project top directory.
1. ./clean.sh
2. ./build.sh
3. ./run.sh

---
## Result
The scripts builds and runs the program without any errors.
Note: The source file `particle_filter.cpp` contains the core algorithms. The number of particles can be changed there.

With    Particles = 100
<br></br>
        Errors :
        x - 0.117, y - 0.109, yaw - 0.004
<br></br>
<br></br>
With    Particles = 1000
<br></br>
        Errors :
        x - 0.109, y - 0.099, yaw - 0.003
 <br></br>
 <br></br>

![filter_image]()

  
