# Underwater simulation workspace

> **Supporting archive** · Upstream ROS/Gazebo framework; not a standalone personal perception implementation
>
> [Selected projects](https://github.com/BadrEss01/BadrEss#selected-projects) · [Coursework](https://github.com/BadrEss01/BadrEss/blob/main/COURSEWORK.md)

Historical ROS 1 / Gazebo workspace containing the upstream UUV Simulator packages. This repository supports the underwater-robotics side of my coursework portfolio; it is not evidence that I authored the simulator.

## Source layout

- `src/uuv_simulator/`: simulator packages, vehicle descriptions, controllers, sensor plugins and upstream documentation.
- `src/uuv_simulator/launch/rexrov_pubsub.launch`: a launch file present in this workspace.
- `docs/`: project context and reproduction notes.

Generated `build/`, `devel/` and `logs/` directories were removed from the current tree during portfolio maintenance. They are recoverable from earlier commits. Rebuild them locally instead of reusing machine-specific outputs.

## Provenance

See the preserved [upstream README](src/uuv_simulator/README.md), [license](src/uuv_simulator/LICENSE) and [third-party notices](src/uuv_simulator/3rd-party-licenses.txt). The upstream project is [uuvsimulator/uuv_simulator](https://github.com/uuvsimulator/uuv_simulator).

A repository copy does not establish which changes were made by an individual student. Upstream simulator functionality is not presented as my own implementation.

## Environment and status

The included upstream documentation describes ROS Kinetic, Lunar and Melodic with Gazebo. These historical environments are not a ROS 2 setup. Build and simulation execution have not been revalidated here.

See [reproduction notes](docs/REPRODUCTION.md) before attempting a build and [RAMI/BlueROV context](docs/RAMI_CONTEXT.md) for the distinction between the class project and this simulator workspace.

[Portfolio](https://github.com/BadrEss01/BadrEss)
