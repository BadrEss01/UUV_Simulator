# Reproduction notes

This is a source-preserving archive of a ROS 1 catkin workspace.

1. Review the distribution-specific setup in the [included upstream README](../src/uuv_simulator/README.md).
2. Use a compatible isolated ROS/Gazebo environment and install the package dependencies required by that distribution.
3. Build the source workspace afresh with the matching catkin tooling. Do not reuse historical generated outputs.
4. Source the resulting workspace setup and inspect the launch file and its arguments before starting Gazebo.
5. Record the OS, ROS, Gazebo and Python versions, build result and observed behavior.

No successful end-to-end build is claimed by this maintenance pass. Historical catkin metadata may reference the original machine; it is context, not a portable environment specification. The local simulation archive must not be treated as a tested physical-robot deployment.
