Project adding the implementation of the Puzzlebot as the real system allowing us to compare the position difference between a real and an ideal model.

Code line for RVIZ simulation using only the ideal model:
roslaunch localisation puzzlebot_rviz.launch

Code line for RVIZ simulation using both models,it's necessary to add the puzzlebot via SSH, otherwise the simulation will only generate the first model due to the real robot topics being missing.

roslaunch localisation double_sim.launch
