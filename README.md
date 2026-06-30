## MOAR Planner: Multi-Objective and Adaptive Risk-Aware Path Planning

The problem of autonomous navigation for UAV inspection remains challenging as it requires effectively navigat- ing in close proximity to obstacles, while accounting for dynamic risk factors such as weather conditions, communication reliability, and battery autonomy. This paper introduces the MOAR path planner which addresses the complexities of evolving risks during missions. It offers real-time trajectory adaptation while concurrently optimizing safety, time, and energy. The planner employs a risk-aware cost function that integrates pre-computed cost maps, the new concepts of damage and insertion costs, and an adaptive speed planning framework. With that, the optimal path is searched in a graph using a discrete representation of the state and action spaces. The method is evaluated through simulations and real-world flight tests. The results show the capability to generate real-time trajectories spanning a broad range of evaluation metrics—around 90% of the range occupied by popular algorithms. The proposed framework contributes by enabling UAVs to navigate more autonomously and reliably in critical missions.

A video showing functionalities of MOAR Planner is coming soon.

Demo available [here](https://www.edu.louispetit.be/demo/moar-demo).

<p align="center">
  <img src="img/method.png" alt="Method" width="70%"/>
</p>

## Reference
If you find our repository useful, please consider giving it a star ⭐ and citing our paper in your work:

``` bibtex
@inproceedings{petit2021rrtrope,
  title={{MOAR Planner}: Multi-Objective and Adaptive Risk-Aware Path Planning for Infrastructure Inspection with a UAV},
  author={Louis Petit and Alexis Lussier Desbiens},
  booktitle={IEEE International Conference on Robotics and Automation (ICRA)},
  year={2024},
  organization={IEEE}
}
```

## Author

[Louis Petit](https://edu.louispetit.be) (louis.petit@usherbrooke.ca)
