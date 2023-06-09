# Onekinatros Home Assistant add-on repository

Welcome to my HomeAssistant Addon Repository! This repository is intended for users who want to add their own addons to HomeAssistant, and it's free for anyone to use. However, please note that some addons provided here may be unfinished or untested, while others may be deprecated and no longer supported.

To help you identify the state of each addon, I've created tags that you'll see in the addon name:

- [DEV]: This addon is currently in development and has not been fully tested.
- [TEST]: This addon is currently in the testing phase.
- [DEPRECATED]: This addon is no longer being actively developed or supported. It may still work, but it's recommended to find an alternative addon.
Please keep in mind that addons without any tags are considered stable and have been fully tested for use in production environments.

I hope you find this repository useful, and I welcome any feedback or contributions to help improve it. Please feel free to contact me if you have any questions or issues.

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fonekintaro%2Fhassio-addons)

## Add-ons

This repository contains the following add-ons

### [\[DEV\]CATT add-on](./catt-addon/)
### [\[DEV\]Passtrough VPN add-on](./passthroughvpn/)

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]

_VPN Addon._

<!--

Notes to developers after forking or using the github template feature:
- While developing comment out the 'image' key from 'example/config.yaml' to make the supervisor build the addon
  - Remember to put this back when pushing up your changes.
- When you merge to the 'main' branch of your repository a new build will be triggered.
  - Make sure you adjust the 'version' key in 'example/config.yaml' when you do that.
  - Make sure you update 'example/CHANGELOG.md' when you do that.
  - The first time this runs you might need to adjust the image configuration on github container registry to make it public
  - You may also need to adjust the github Actions configuration (Settings > Actions > General > Workflow > Read & Write)
- Adjust the 'image' key in 'example/config.yaml' so it points to your username instead of 'home-assistant'.
  - This is where the build images will be published to.
- Rename the example directory.
  - The 'slug' key in 'example/config.yaml' should match the directory name.
- Adjust all keys/url's that points to 'home-assistant' to now point to your user/fork.
- Share your repository on the forums https://community.home-assistant.io/c/projects/9
- Do awesome stuff!
 -->

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
