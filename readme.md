# Required Modules
* numpy
* matplotlib
* opencv
* skimage

# How to run
1. Open code file using jupyter notebook
2. Edit robot pose and map path
3. Run all the cells and wait untill output files generated inside directory called **Outputs**

# Outputs
* ***original_map_with_robot.png*** : input map with the robot drawn in red in the input position
* ***map_with_generated_rays.png*** : map with generated rays drawn in green
* ***measurements.txt*** : text file containing the euclidean distance for the each generated ray from the robot to the nearest obstacle
* ***likelihood_output.png*** : image with maximum likelihood for each cell in the input map 