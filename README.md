# Vconnex Custom Integration for Home Assistant

[![GitHub Release][releases-shield]][releases]
[![License][license-shield]](LICENSE)
[![HACS Latest](https://img.shields.io/badge/HACS-Latest-blue)](https://github.com/custom-components/hacs)

This is a custom component to allow control Vconnex smart devices in [HomeAssistant](https://home-assistant.io).


## Features:

* Switch
* Power Meter
* Cover


## Installation

### Install using HACS (recomended)

**1.** [Download HACS](https://hacs.xyz/docs/use/download/download/)

**2.** [Setup the HACS integration](https://hacs.xyz/docs/use/configuration/basic/#setting-up-the-hacs-integration)

**3.** **Install custom repository**

HACS -> Integrations -> ... -> Custom repositories 
![Install custom repository](https://github.com/vconnex/asset/raw/master/vconnex-home-assistant/img/hacs-install-custom.png)

**4.** **Download custom components: Vconnex CC**

**-** Input the vconnex-home-assistant GitHub URL: **https://github.com/vconnex/vconnex-home-assistant** and select **Integration** as the Category type,  then click **ADD**.

![Add integration](https://github.com/vconnex/asset/raw/master/vconnex-home-assistant/img/add-custom-repo.png)

**-** Click **DOWNLOAD**

![Download](https://github.com/vconnex/asset/raw/master/vconnex-home-assistant/img/install-custom-component.png)

**-** Restart Home Assistant: Developer tools -> RESTART

![Restart HASS](https://github.com/vconnex/asset/raw/master/vconnex-home-assistant/img/restart-hass-new.png)


### Install manually

Clone or copy this repository and copy the folder 'custom_components/vconnex_cc' into '&lt;homeassistant_config&gt;/custom_components/vconnex_cc'


## Configuration

### Get Vconnex project credential

**1.** Open [Vconnex Project](https://hass.vconnex.vn): https://hass.vconnex.vn.

**2.** Login with your **Vhomenex** account. 

**3.** Project -> Create project.
![Create Project 1](https://github.com/vconnex/asset/raw/master/vconnex-home-assistant/img/create-project-1.png)

![Create Project 2](https://github.com/vconnex/asset/raw/master/vconnex-home-assistant/img/create-project-2.png)

**4.** View project detail page to get to your project credential.
![View Project Detail 1](https://github.com/vconnex/asset/raw/master/vconnex-home-assistant/img/view-detail-1.png)

![View Project Detail 2](https://github.com/vconnex/asset/raw/master/vconnex-home-assistant/img/view-detail-2.png)


### Active Vconnex Integration

**1.** Configuration -> Integrations -> ADD INTEGRATION -> Vconnex
![Active 1](https://github.com/vconnex/asset/raw/master/vconnex-home-assistant/img/active-component-1.png)

![Active 2](https://github.com/vconnex/asset/raw/master/vconnex-home-assistant/img/active-component-2.png)

**2.** Enter your project credential
![Enter your project credential](https://github.com/vconnex/asset/raw/master/vconnex-home-assistant/img/enter-project-credential.png)



[license-shield]: https://img.shields.io/github/license/vconnex/vconnex-home-assistant
[releases-shield]: https://img.shields.io/github/v/release/vconnex/vconnex-home-assistant
[releases]: https://github.com/vconnex/vconnex-home-assistant/releases