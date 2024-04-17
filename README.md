Based on the [Foxglove tutorial](https://foxglove.dev/blog/using-rosbridge-with-ros2)

#### How to use
1. `source /opt/ros/$ROS_DISTRO/setup.bash`
2. `ros2 launch rosbridge_server rosbridge_websocket_launch.xml`
3. `ros2 topic pub /my_topic std_msgs/String "data: 'Hello world'"`
4. In a browser, open the `index.html` file