[![Udacity - Robotics NanoDegree Program](https://s3-us-west-1.amazonaws.com/udacity-robotics/Extra+Images/RoboND_flag.png)](https://www.udacity.com/robotics)

# RoboND-MCL-Lab
You will be able to observe the `MCL` in action through the generated images. 

### Editing the Program
Enter the code in the designated section:
```C++
//####   DON'T MODIFY ANYTHING ABOVE HERE! ENTER CODE BELOW ####
		
//TODO: e.g Graph the position of the robot and the particles at each step 
```
### My Modification

I have added the steps of the algorithm on different files with main and solution

The final is RoboND-MCL-Lab compile solution.cpp to see the visualization with the Images
as described below.

### Steps

1. Robot Class 
2. First Interaction
3. Motion and Sensing
4. Noise
5. Particle Filter
6. Importance Weight
7. Resampling
8. Resampling Wheel
9. Error
10. Graphing - RoboND


### Compiling the Program from the original repo
```sh
$ cd /home/workspace/
$ git clone https://github.com/udacity/RoboND-MCL-Lab
$ cd RoboND-MCL-Lab/
$ rm -rf Images/*
$ g++ main.cpp -o app -std=c++11 -I/usr/include/python2.7 -lpython2.7
```

### Running the Program
Before you run the program, make sure the `Images` folder is empty!
```sh
$ ./app
```
Wait for the program to iterate `50` times.

### Generated Images
After running the program, `50` images will be generated in the `Images` folder.
#### Step0
![alt text](/Step0.png)
#### Step49
![alt text](/Step49.png)

