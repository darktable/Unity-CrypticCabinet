﻿# Changelog
All notable changes to this project will be documented in this file.

## 11/13/2024
### Update
* Update to Unity 2022.3.36
* Update to SDK v69
  * Set boundaryless on camera rig
  * Remove grabbableFixed script and replace by the Grabbable script from ISDK (fixed in latest sdk)
* Add MR Utility Kit (MRUK)
  * Replace deprecated OVRScene apis with MRUK api
* Update Fusion app version to 2.0.0 to avoid conflict with previous apps
* Update app version to 2.0.0

### Fixes
* Fixed the shadow flickering
  * We needed to update URP and Visual Effect Graph packages which required the Unity update