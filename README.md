# gazebo_worlds
gazebo simulation worlds for my projects


## Dependencies
* ubuntu 16.04 LTS
* ROS kinect


## installation

Download the package [bguplp/gazebo_worlds package](https://github.com/bguplp/gazebo_worlds).
Run in terminal:
```bash
$ cd ~/catkin_ws/src
$ git clone https://github.com/bguplp/gazebo_worlds.git
$ cd ..
$ catkin_make

```

In order for all the models used in the simulations will appear properly, all the models  in "gazebo_worlds/Building_37/models " must be copied
to "~/.gazebo/models".

There two options to do it:
* Recomended :
  copy to terminal:
  ```bash
  $ cp *  ~/catkin_ws/src/gazebo_worlds/Building_37/models ~/.gazebo/models/
  
  ```
* Manualiy

## Runing
Run the launch file from the terminal:
```bash
$ cd ~/catkin_ws/src/gazebo_worlds/Building_37
$ gazebo NAME_OF_WORLD.world
```

 
## Examples of worlds in the package
In this package there a diffrent verssions of a same building.
The difference between the worlds is the weight of the world, i.e. 
Each world has a different number of objects, a different order
adapted to different scenarios according to the needs of the lab.
 
 
 1. building_37_sim_1.world
 
  A. floor 2
 ![Before ](https://github.com/bguplp/gazebo_worlds/blob/master/Building_37/building_37_sim_1.png)
 
  B. floor 1 
 ![Before ](https://github.com/bguplp/gazebo_worlds/blob/master/Building_37/building_37_sim_1_floor_1.png)
 
 2. building_37_sim_1.world
 ![Before ](https://github.com/bguplp/gazebo_worlds/blob/master/Building_37/building_37_sim_2.png)
 
  
  
  
  





