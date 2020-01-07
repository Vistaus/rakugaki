# ![icon](data/icon.png) Rakugaki

## Want to just draw, sketch or doodle? This is the tool for you

[![Get it on AppCenter](https://appcenter.elementary.io/badge.svg)](https://appcenter.elementary.io/com.github.lainsce.rakugaki)

[![Build Status](https://travis-ci.org/lainsce/rakugaki.svg?branch=master)](https://travis-ci.org/lainsce/rakugaki)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)

![Screenshot](data/shot.png)

## Ecosystem

Change the UI colors by using the special [Ecosystem SVGs here](https://github.com/hundredrabbits/Themes/)

## Donations

Would you like to support the development of this app to new heights? Then:

[Be my backer on Patreon](https://www.patreon.com/lainsce)

## Dependencies

Please make sure you have these dependencies first before building.

```bash
granite
gtk+-3.0
meson
```

## Building

Simply clone this repo, then:

```bash
meson build --prefix=/usr && cd build
sudo ninja install
```
