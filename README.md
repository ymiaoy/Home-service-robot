# Home-service-robot

## cmd:
      mkdir -p catkin_ws/src
      cd ..
      catkin_make
      cd src
      git clone https://github.com/ymiaoy/Home-service-robot
##  remove all of the files and folders into src folder.

##  back to catkin_ws folder and build
      cd ..
      catkin_make
      
## test 
 
      cd scripts
      ./test_navigation.sh
      
      or
      ./test_slam.sh
      
      or
      ./pick_objects.sh
      
      or
      ./add_markers.sh
      
      

