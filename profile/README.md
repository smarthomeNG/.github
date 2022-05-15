## SmartHomeNG
**SmartHomeNG** is the open-source integration platform for your smart home

[![Made with Python](https://img.shields.io/badge/made%20with-Python-blue.svg)](https://www.python.org)
[![Made with Angular](https://img.shields.io/badge/made%20with-Angular-blue.svg)](https://angular.io)
[![Forum](https://img.shields.io/badge/forum-KNX_User_Forum-brightgreen.svg)](https://knx-user-forum.de/forum/supportforen/smarthome-py)
[![Chat on Gitter](https://img.shields.io/badge/chat-On_Gitter-brightgreen)](https://gitter.im/smarthomeNG/smarthome?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Website smarthomeng.de](https://img.shields.io/website-up-down-green-red/http/smarthomeng.de.svg)](http://smarthomeng.de/)
[![GitHub forks](https://badgen.net/github/forks/smarthomeNG/smarthome/)](https://GitHub.com/smarthomeNG/smarthome/network/)
[![GitHub license](https://img.shields.io/github/license/smarthomeNG/smarthome.svg)](https://github.com/smarthomeNG/smarthome/blob/master/LICENSE)


<br>

## SmartHomeNG repository ecosystem

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

There are already several repositiories containing different parts of SmartHomeNG. Of interest for users of SmartHomeNG are only the following of them. Most users will only use the first two (***smarthome*** and ***plugins***):

* [smarthome](https://github.com/smarthomeNG/smarthome)
  The Core of the application resides in this Repository

  master: ![Github Tag](https://img.shields.io/github/v/release/smarthomeng/smarthome?sort=semver)
[![Aktuelles Release](https://img.shields.io/github/workflow/status/smarthomeNG/smarthome/Unittest%20Workflow%20Core/master)](https://github.com/smarthomeNG/smarthome/actions/workflows/unittests.yml)

  develop: [![Aktuelles Release](https://img.shields.io/github/workflow/status/smarthomeNG/smarthome/SmartHomeNG%20Unittest%20Workflow%20Core/develop)](https://github.com/smarthomeNG/smarthome/actions/workflows/unittests.yml)


* [plugins](https://github.com/smarthomeNG/plugins)
  The Core may be extended by several plugins which provide additional functionality for gateways, devices, etc.
  Here the plugins have found their home
  
  master: ![Github Tag](https://img.shields.io/github/v/release/smarthomeng/plugins?sort=semver)
[![Aktuelles Release](https://img.shields.io/github/workflow/status/smarthomeNG/plugins/Unittest%20Workflow%20Plugins/master)](https://github.com/smarthomeNG/plugins/actions/workflows/unittests.yml)

  develop: [![Aktuelles Release](https://img.shields.io/github/workflow/status/smarthomeNG/plugins/Unittest%20Workflow%20Plugins/develop)](https://github.com/smarthomeNG/plugins/actions/workflows/unittests.yml)


* [raspberrypi-image](https://github.com/smarthomeNG/raspberrypi-image) This repository conains a "ready to use" image for the Raspberry Pi. It contains SmartHomeNG, the smartVISU and other tools.
  The release number is a combination of the Debian/RaspiOS version followed by the SmartHomeNG version.

  master: ![Github Tag](https://img.shields.io/github/v/release/smarthomeng/raspberrypi-image?sort=semver)
[![Github all releases](https://img.shields.io/github/downloads/smarthomeng/raspberrypi-image/total.svg)](https://GitHub.com/smarthomeng/raspberrypi-image/releases/)
  
  ![Github Tag](https://img.shields.io/github/downloads/smarthomeng/raspberrypi-image/11.1.9.2/total.svg)
![Github Tag](https://img.shields.io/github/downloads/smarthomeng/raspberrypi-image/11.1.9.1/total.svg)
![Github Tag](https://img.shields.io/github/downloads/smarthomeng/raspberrypi-image/11.1.8.2/total.svg)
![Github Tag](https://img.shields.io/github/downloads/smarthomeng/raspberrypi-image/10.1.7.1/total.svg)
![Github Tag](https://img.shields.io/github/downloads/smarthomeng/raspberrypi-image/9.1.6/total.svg)


* [docker](https://github.com/smarthomeNG/docker)  This repo contains a docker container and dokumentation for SmartHomeNG

  master: ![Github Tag](https://img.shields.io/github/v/tag/smarthomeng/docker?sort=semver)


* [plugin_archive](https://github.com/smarthomeNG/plugin_archive)
  Older plugins that are not maintained any more or the ones being obsolete due to a switched off service are kept here for reference

<br>

-------

The rest of the repositories are for use by the development team:
  
* [Developer Documentation](https://github.com/smarthomeNG/dev_doc)
  Helper repository for the automatic build of the documentation from the develop branch. No manual commmits occur.
  
* [shngadmin](https://github.com/smarthomeNG/shngadmin)
  The Core and many of its plugins can be controlled via a web interface. It is created with Typescript and Angular 7 currently and here the source of the GUI is found
  
* [ansible](https://github.com/smarthomeNG/ansible) Repository with the scripts used to build the raspberrypi image

* [shng-install](https://github.com/smarthomeNG/shng-install) work in progress
  
  
  
  
