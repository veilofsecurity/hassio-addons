# Changelog

## 1.3.0
- bump hassio-addon-base to V14.0.0
- autorelease new version updates on addon base updates
- auto bump dependency updates for bt-mqtt-gateway python module

## 1.2.1
- bump hassio-addon-base to latest release

## 1.2.0
- bump hassio-addon-base python to V10.0.0

## 1.1.1
- Fixed an installation issue

## 1.1.0
- Fixed an issue where the config file wont be detected correctly
- Rebase the dockerfile on hassio addon base to be independent from the original Dockerfile
- Update base image which comes with the latest python and pip

## 1.0.4
- Let this addon access host_dbus (hopefully this fixes the bluetooth connection issue)

## 1.0.3
- Let this addon run at the host network (hopefully this fixes the bluetooth connection issue)

## 1.0.2
- Allow the use of the debugging mode (create a empty text file at /share/bt-mqtt-gateway-debug.txt to enable debugging mode)

## 1.0.1
- Allow Hardware access (fixes the issue that the addon cant connect via bluetooth to devices)

## 1.0.0
- Initial release
