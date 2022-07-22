# uc_car
This is the record of process about our car project, which can have some introduction in our page.
## uc_car_v1
First version is to use num_laser_scan = 2 in cartographer. However, we still have one error "Drop early point" in this version.
## uc_car_v2
Second Version is to use ira_laser_tools to merge single data. However,when I try to add joint state and pubilsh state in this version, I can only use num_laser_scan = 2 to compute map.
## uc_car_v3
In third Version, I also tried to use ira_laser_tools to merge data without using add joint state and publish state. The parameter num_laser_scan = 1, but the map seems quite slow even I try to change number of some parameter that could influence the mapping speed. 
## uc_car_rplis_imu
