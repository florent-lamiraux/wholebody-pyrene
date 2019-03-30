# Simple whole body motion on Pyrène Robot

This package provides 2 scripts that generate wholebody motion for Pyrène

  * simple-wholebody.py generates a collision free motion from an initial
    configuration to a randomly generated goal configuration,
  * manipulation.py generates a manipulation motion where the robot grasps an
    object lying on a table, flips the object and put it back on the table.

## How to use this package

Follow the instructions provided in file instructions:

  * install hpp via robotpkg,
  * make sure omniNames is running, otherwise start it,
  * run hpp-manipulation-server, run the desired python script,
  * to display the resulting path, run gepetto-gui and follow the instructions
    commented out at the end of both scripts.

## Output

The resulting motion is sampled at .1 second in /tmp/traj.yaml.
