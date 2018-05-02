# Ravada VDI

![GLPI Banner](https://user-images.githubusercontent.com/29282308/31666160-8ad74b1a-b34b-11e7-839b-043255af4f58.png)

[![License AGPL 3.0](https://img.shields.io/badge/License-AGPL%203.0-blue.svg)](https://github.com/pluginsGLPI/ravada/blob/develop/LICENSE.md)
[![Telegram RavadaVDI](https://img.shields.io/badge/Telegram-RavadaVDI-43BC9C.svg)](https://t.me/ravadavdi)
[![Documentation Status](https://readthedocs.org/projects/ravada/badge/?version=latest)](http://ravada.readthedocs.io/en/latest/?badge=latest)
[![Follow twitter](https://img.shields.io/twitter/follow/ravada_vdi.svg?style=social&label=Twitter&style=flat-square)](https://twitter.com/ravada_vdi)
[![Follow Twitter](https://img.shields.io/badge/Twitter-GLPI%20Project-26A2FA.svg)](https://twitter.com/GLPI_PROJECT)
[![Project Status: WIP](http://www.repostatus.org/badges/latest/wip.svg)](http://www.repostatus.org/#wip)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org)

Remote Virtual Desktops Manager [Official Website](https://ravada.upc.edu/).

Ravada is a software that allows the user to connect to a remote virtual desktop, developped by the **[UPC](https://github.com/upc)**.

## Table of Contents

* [Synopsis](#synopsis)
* [Build Status](#build-status)
* [Documentation](#documentation)
* [Versioning](#versioning)
* [Contact](#contact)
* [Professional Services](#professional-services)
* [Contribute](#contribute)
* [Copying](#copying)

## Synopsis

Ravada is an open-source project that allows users to connect to a virtual desktop. It is a VDI broker.

Its back-end has been designed and implemented in order to allow future hypervisors to be added to the framework. Currently it supports KVM and LXC is in the works.

### Features

* KVM backend for Windows and Linux Virtual machines.
* LDAP and SQL authentication.
* Kiosk mode.
* Remote Access with Spice for Windows and Linux
* Light and fast virtual machine clones for each user
* Instant clone creation
* USB redirection
* Easy and customizable end users interface
* Administration from a web browser

## Build Status

|**LTS**|Bleeding Edge|
|:---:|:---:|
|[![Travis CI build](https://api.travis-ci.org/pluginsGLPI/ravada.svg?branch=master)](https://travis-ci.org/pluginsGLPI/ravada/)|[![Travis CI build](https://api.travis-ci.org/pluginsGLPI/ravada.svg?branch=develop)](https://travis-ci.org/pluginsGLPI/ravada/)|

## Documentation

We maintain a detailed documentation of the project on the website, check the [How-tos](https://pluginsGLPI.github.io/ravada/howtos/) and [Development](https://pluginsGLPI.github.io/ravada/) section.

## Versioning

In order to provide transparency on our release cycle and to maintain backward compatibility, this project is maintained under [the Semantic Versioning guidelines](http://semver.org/). We are committed to following and complying with the rules, the best we can.

See [the tags section of our GitHub project](https://github.com/pluginsGLPI/ravada/tags) for changelogs for each release version. Release announcement posts on [the official Teclib' blog](http://www.teclib-edition.com/en/communities/blog-posts/) contain summaries of the most noteworthy changes made in each release.

## Contact

For notices about major changes and general discussion of development, subscribe to the [/r/glpi](http://www.reddit.com/r/glpi) subreddit.
You can also chat with us via IRC in [#GLPI on freenode](http://webchat.freenode.net/?channels=GLPI) if you get stuck, [@RavadaVDI on Telegram](https://t.me/ravadavdi) and [@glpien on Telegram](https://t.me/glpien).

## Professional Services

The GLPI Network services are available through our [Partner's Network](http://www.teclib-edition.com/en/partners/). We provide special training, bug fixes with editor subscription, contributions for new features, and more.

Obtain a personalized service experience, associated with benefits and opportunities.

## Contribute

Want to file a bug, contribute some code, or improve documentation? Excellent! Read up on our
guidelines for [contributing](./.github/CONTRIBUTING.md) and then check out one of our issues in the [Issues Dashboard](https://github.com/pluginsGLPI/ravada/issues).

## Copying

* **Name**: [Ravada](https://ravada.upc.edu/) is a registered trademark of [UPC](http://www.upc.edu).
* **Name**: [GLPI](http://glpi-project.org/) is a registered trademark of [Teclib'](http://www.teclib-edition.com/en/).
* **Code**: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License ([AGPLv3](https://www.gnu.org/licenses/agpl-3.0.en.html)).
* **Documentation**: released under Attribution 4.0 International ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)).