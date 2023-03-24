# mapless_navigation_on_uneven_terrain
Autonomous Mapless Navigation on Uneven Terrains

____________________________________________________________________________________

The code and the paper will be published after the acceptance of the paper (Submitted for IROS 2023)

We introduce a novel method for autonomous navigation in challenging, uneven terrains by leveraging the uncertainty quantification provided by a Sparse Gaussian Process (SGP) based local perception model. This model is trained using local ranging observations (point clouds) to accurately learn terrain elevation profiles and identify feasible navigation subgoals in the robot's vicinity. Our approach employs a cost function that prioritizes the robot's safety by maintaining its roll and pitch angles within a predefined range, allowing us to select safety-conscious subgoals that guide the robot to its ultimate destination. Designed for real-time operation, our algorithm has been thoroughly evaluated in simulations with 100 trials across three different scenarios: uphill traversal, downhill traversal, and valley-following. The results demonstrate the algorithm's effectiveness in navigating uneven terrains without requiring a global map.

The video below shows the methodology and the results.


https://user-images.githubusercontent.com/58668234/227651190-613f7b1c-d5d6-4789-9a7c-201cab4c7727.mp4


