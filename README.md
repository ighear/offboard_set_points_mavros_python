# offboard_set_points_mavros_python
I am trying to control a drone from the offboard mode using a python script, 
I am new at this so this is my first attempt and I have tried to keep it simple: 
first the drone is armed, then the offboard mode is set, and then a series of positions 
are sent to the drone for it to fly.  
At the moments this commands are sent to a simulator (jmavsim) connected,and the arming
command is working fine, as does the offboard mode, but the drone does not move to any
positions, so I believe I must be sending those commands incorrectly.

The script can be seen in the file "arm", and the commands to set up the simulator and
connect to it, and run the script can be seen in the file "Simulator and scripts". As
I mentioned, the drone arms and sets offboard mode correctly using the script, and no
syntax errors are displayed either, so the script is running fine and the drone is connected.
