This tutorial shows how to create a custom model (maze) and add to an existing world.  Model is a keyword used to refer a virtual object in Gazebo. You can add any model from the existing models in Gazebo. Many models are available to be used in simulations. 

These steps are demonstrated in the video.
1.	Create a new package called my_simulation.

2.	Copy .launch and .world files from turtlebo3_empty_world simulation to my_simulation, and edit them.

3.	Create my_maze model using the Building Editor in Gazebo. After you saved the model (in /home/master/.gazebo/models/my_maze) you will see two files inside my_maze folder (.config and .sdf). They are configuration and simulation description format files. Any object in Gazebo is described with these two files. If you want to modify an object you have to edit these files manually or modify the object in a GUI and save it updating these files.

4.	For this tutorial, you are creating only four files to complete your maze.

Your simulation package
          a.	/home/catkin_ws/src/my_simulations/worlds/empty_world.world
          b.	/home/catkin_ws/src/my_simulations/launch/my_world.launch
Your maze model
          c.	/home/master/.gazebo/models/my_maze/model.config
          d.	/home/master/.gazebo/models/my_maze/model.sdf
          5.	Next, you have to modify your .world file to include my_maze model.

		  
Software used for this tutorial:

- Ubuntu 16.04 running on VirtualBox
- .bashrc file is already updated for TurtleBot3 Waffle Pi
- Gazebo TurtleBot3 simulations are already installed

Compiling (catkin_make) step is not always shown in the video. Always compile your packages after making changes to your files.

https://www.youtube.com/watch?v=J_vasKVhUQM
