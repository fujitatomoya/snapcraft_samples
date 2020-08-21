### Environment

- Ubuntu20.04 (Focal Fossa)
- ROS:Foxy
- (Do not use docker, it requires some tricks to run snapd in container)
- [Use LXD instead of KVM](https://snapcraft.io/blog/faster-snap-development-additional-tips-and-tricks), sometimes vmx is disabled by BIOS.

### Build Snap

```
# git clone git@github.com:fujitatomoya/snapcraft_samples.git
# cd ros2/<sub_directory>
# snapcraft --enable-experimental-extensions --use-lxd
```

### Reference

- https://snapcraft.io/docs/ros2-applications
- https://snapcraft.io/blog/how-to-build-a-snap-using-ros-2-foxy
- https://index.ros.org/doc/ros2/Installation/Foxy/Linux-Install-Debians/
