| Field Name    | Data Type               | Professional English Explanation                                                                 |
| ------------- | ----------------------- | ----------------------------------------------------------------------------------------------- |
| q             | std::array<double, 7>   | Joint positions (rad), directly from encoders                                                   |
| dq            | std::array<double, 7>   | Joint velocities (rad/s), directly from encoders                                                |
| tau_J         | std::array<double, 7>   | Joint torques (N·m), directly from encoders                                                     |
| O_T_EE        | std::array<double, 16>  | End-effector pose in base frame, represented as a 4×4 homogeneous transformation matrix         |
| O_T_EE_d      | std::array<double, 16>  | Desired end-effector pose in base frame, represented as a 4×4 homogeneous transformation matrix |
| robot_mode    | RobotMode               | Robot operation mode                                                                            |
| O_F_ext_hat_K | std::array<double, 6>   | Estimated external forces and torques in base frame                                             |
