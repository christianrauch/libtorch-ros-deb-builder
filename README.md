```bash
echo "deb [trusted=yes] https://github.com/christianrauch/libtorch-ros-deb-builder/raw/jammy-humble/ ./" | sudo tee /etc/apt/sources.list.d/christianrauch_libtorch-ros-deb-builder.list
echo "yaml https://github.com/christianrauch/libtorch-ros-deb-builder/raw/jammy-humble/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-christianrauch_libtorch-ros-deb-builder.list
```
