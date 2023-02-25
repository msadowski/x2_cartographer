# Depreciation notice

This code won't be maintained, and likely will not work anymore. I'm leaving this on GitHub in case anyone still finds value in it.

# YDLIDAR X2 - Cartographer project

This project was used to create a demonstrator of using YDLIDAR X2 with Google Cartographer as described in [this blog post](https://msadowski.github.io/ydlidar-x2-review-ros-cartographer/).

## Quickstart (Melodic only)

1. Clone the repo as your src directory `git clone git@github.com:msadowski/x2_cartographer.git`
2. Initialize and update submodules `git submodule update --init`
3. Perform the setup described in ydlidar/README.md
4. If you don't have cartographer installed run `rosdep install --from-paths src --ignore-src --rosdistro melodic -r -y` from your workspace
5. Source your workspace `source devel/setup.bash`
6. Start everything: `roslaunch carto_mapper mapper.launch`

The files in this repository are provided as is. No support is guaranteed but if you find ways to improve it feel free to open a pull request.
