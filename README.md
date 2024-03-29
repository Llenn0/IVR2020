# IVR2020

This is the github repository for the 2020 IVR Assignment by Harry Lennox (Vision) & Rongxuan Liu (Kinematics).

# Usage and Known Issues

The code is currently set up with the sinusoidal signals from section 2, since the vision half of the code is error-free. Unfortunately, there are issues with the kinematics that prevent it from functioning properly.
With these signals, the robot can sometimes hit the ground of the simulation or otherwise be thrown off after a long period of use, so it is recommended to restart gazebo frequently. For the elements of section 4 to function properly, the robot must be in its fresh initialised state to ensure the base joints are correctly identified (see report).

To still view the robot functioning according to the kinematics, you can comment out the movement code publishers and uncomment the ones beneath which are currently commented out.

# Github Updates

Initially, the whole ivr_assignment folder was not included in the repository, and whilst attempting to correctly upload the whole directory, the master branch of the project was essentially wiped. Thankfully, there were not many updates to master in the first place. Ongoing use of github pushes can be seen in the Vision branch, which remains as it was.
