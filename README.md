[Video](https://www.youtube.com/watch?v=5SEZZBKRWCk)

# How to run  the code:

Choose algorithm in file `traj_planning/test_sequence.m` and run.

  

On file `test_sequence.m` uncomment accordingly one of the five functions below.

Note that the first function is the RRT of the report, while the fifth function is the proposed RRT of the report.

    path{qn}=rrt_function(map,start,stop,num_iter);    
    path{qn}=rrt_goal_on_view(map,start,stop,num_iter);
    path{qn}=bi_directional_rrt_function(map,start,stop,num_iter);    
    path{qn}=bi_directional_rrt_function_on_view(map,start,stop,num_iter); 	path{qn}=bi_directional_rrt_function_optimized(map,start,stop,num_iter);

  

From these functions, one can navigate accordingly to the created functions such as `back_tracking`, `path_collision_checker` `plot_path_rrt`.

  

Furthermore, the maps created are saved in folder traj_planning/maps.

The main room map is saved as `map_ours_11`, while the second map mentioned on the report is `map3`.

In folder `traj_planning/maps` there exist other maps with different types of obstacles for the sake of more tries if necessary.

  

Most of the files created by us are under folder traj_planning. We also made modifications to folder control in order to suit our setup.

Credits to my teammates: George Apostolides, Guru Singh and Kevin Voogd

