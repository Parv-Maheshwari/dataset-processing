gps_bag needs building in catkin_ws nmea_msgs 

use MarkDown language!!!!

Use the S-PTAM branch https://gitlab.com/taihu/sptam/tree/ras_2017_sptam_full_working to make S-PTAM work properly on the


rus S-PTAM on Rosario dataset
roscore &
rosparam set use_sim_time true
roslaunch sptam zed_bag.launch
rosbag play --clock <sequenceXX.bag>

[crear configuración para levantar con rviz]

Plotters
el Plot de S-PTAM plot-paths anda para mostrar la trayectoria bien de S-PTAM. Falta el script de comparación con el GT y comparación con otros métodos
Podemos probar con ORB-SLAM.

Transformar datos de GT a formato EuRoC y a KITTI para poder comparar fácilmente (hacer script)





