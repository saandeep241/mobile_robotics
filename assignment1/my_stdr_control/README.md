# my_stdr_control
An minimal, example node to illustrate control of the STDR mobile robot with open-loop commands.
This specific code and usage has been forked from the repository of Dr. Wyatt Newman professor of mobile robotics in case western reserve university

## Example usage
`roslaunch stdr_launchers server_with_map_and_gui_plus_robot.launch`
to start the simulator.  Run a simple, open-loop command sequence with:
`rosrun my_stdr_control my_stdr_open_loop_commander`

## Changes from the original
There are no specific changes from the original, the difference is the original file would move the robot , turn and move it again.
The changes I made takes the robot from the initial position to the top left corner in the environment.


    
