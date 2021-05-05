# ros-stream-stack 

ROS metapackage used to group available ROS packages for network streaming solutions. 

In order to properly use following metapackage it's neccessary to install `gstreamer` libs 
as follows: 
```
sudo apt-get install gstreamer1.0-plugins-ugly libgstreamer-plugins-base1.0-dev libgstreamer-plugins-good1.0-dev libgstreamer-plugins-bad1.0-dev libgstrtspserver-1.0-dev 
```

OpenCV is also prerequisite and you can try to install it with `python-pip` as follows: 
```
pip install opencv 
```

You can find detailed instructions how to install OpenCV [here](https://linuxize.com/post/how-to-install-opencv-on-ubuntu-18-04/) 

# Currently ros-stream-stack contains following ROS packages: 
 * [video-stream-opencv](http://wiki.ros.org/video_stream_opencv)  
 * [ros-rtsp](https://github.com/CircusMonkey/ros_rtsp)  

 
