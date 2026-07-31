# Windows
Run Windows in your browser. The default version is Windows 11 but you can configure it in the `windows.yaml` file.

The Docker image is from https://github.com/dockur/windows#docker-compose

## Installation
1. Open up your ZimaOS Dashboard.
2. Open up the `App Store`
3. Click on `My Apps`.
4. Click on `Install Custom App`.
5. Click on `YAML`.
6. Replace the contents with the `windows.yaml` file.
7. Update your `volumes` to match your external drive. By default it will save in `ZimaOS-HD/AppData/windows:/storage`

