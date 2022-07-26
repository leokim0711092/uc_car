# uc_car
This is the record of process about our car project, which can have some introduction in our page.
## uc_car_v1
First version is to use num_laser_scan = 2 in cartographer. However, we still have one error "Drop early point" in this version.
rqt_tf_tree
![](https://i.imgur.com/LkBnarW.png)
rqt_graph
![](https://i.imgur.com/bDravdd.png)

## uc_car_v2
Second Version is to use ira_laser_tools to merge single data. However,when I try to add joint state and pubilsh state in this version, I can only use num_laser_scan = 2 to compute map.
> rqt_tf_tree
![](https://i.imgur.com/CmxBrof.png)
> rqt_graph
![](https://i.imgur.com/9B0xgod.png)

## uc_car_v3
In third Version, I also tried to use ira_laser_tools to merge data without using add joint state and publish state. The parameter num_laser_scan = 1, but the map seems quite slow even I try to change number of some parameter that could influence the mapping speed. 
> rqt_tf_tree
![](https://i.imgur.com/Nh84DHX.png)
> rqt_graph
![](https://i.imgur.com/XeCSIQA.png)

## uc_car_rplis_imu
In this version, I put HFI-a9 imu into uc_car_v1 and make some revision in each file. Putting imu in this project can help us to prevent robot have unreasnoable move in rviz.
> rqt_tf_tree
![](https://i.imgur.com/AmPIS3T.png)
> rqt_graph
![](https://i.imgur.com/XZpxgNt.png)
> result 
![](https://i.imgur.com/Lnqlbpp.png)
