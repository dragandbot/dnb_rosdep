# dnb_rosdep
Rosdep overlay for dragandbot

## What is rosdep? Why do we need an overlay?

rosdep is the system ROS uses for defining system dependancies. Many common dependancies are already supported in the standard rosdep. Some of the raspberry pi deps used by raspicam are not declared there, so we define them in this 'overlay'.

You can add this overlay to your system creating the file: `/etc/ros/rosdep/sources.list.d/30-dragandbot.list` and add this to it.

`yaml https://github.com/dragandbot/dnb_rosdep/blob/master/python.yaml`
