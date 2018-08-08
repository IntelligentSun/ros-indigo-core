# ros-indigo-core
Linux 4.4.0-79-generic #ubuntu 14.04.1

1.Installing bootstrap dependencies
$ sudo apt-get install python-rosdep python-rosinstall-generator python-wstool python-rosinstall build-essential

2.Initializing rosdep
$ sudo rosdep init
$ rosdep update

3.Installation
$ git clone https://github.com/IntelligentSun/ros-indigo-core.git
$ ./src/catkin/bin/catkin_make_isolated -DCMAKE_BUILD_TYPE=Release
$ source ~/ros-indigo-core/devel_isolated/setup.bash
