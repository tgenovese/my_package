```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/tgenovese/my_package/noble-jazzy-arm64/ ./" | sudo tee /etc/apt/sources.list.d/tgenovese_my_package-noble-jazzy-arm64.list
echo "yaml https://github.com/tgenovese/my_package/raw/noble-jazzy-arm64/local.yaml jazzy" | sudo tee /etc/ros/rosdep/sources.list.d/1-tgenovese_my_package-noble-jazzy-arm64.list
```
