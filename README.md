:warning: WORK IN PROGRESS
==========================

# SikuliX IDE - Twitter Bot

[![Twitter Follow](https://img.shields.io/twitter/follow/Damien_Fremont?style=social)](https://twitter.com/Damien_Fremont)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

2024's advanced Twitter Bot using Sikulix-IDE and web-browser UI (ex: Firefox).

![alt text](./docs/README/thumb.png)

## Content

  - [Dependencies](#dependencies)
  - [Screenshots](#screenshots)
  - [Features](#features)
  - [Install](#install)
  - [Usage](#usage)
  - [Resources](#resources)

---------------------------------------

## Dependencies

- Java 8+
- FireFox + Container
- [SikuliX IDE v2.0.5](http://sikulix.com/)

## Screenshots

![alt text](./docs/README/screenshot-1.png)

## Features

- Targets:
  - [x] Win64 (Windows)
- Twitter
  - [ ] site: open, close
  - [ ] favtweet.py
  - [ ] retweetuser.py
  - [ ] tweetfile.py
  - [ ] followback.py
  - [ ] followfriendsof.py	
- Firefox
  - [x] app: start, stop
  - [x] container: open
  
- OS
  - []
  - [x] cmd: run

Repository layout:
```
├── docs
├── platform
│   ├── cmd...
│   └── firefox...
├── standalone
│   ├── twitter-bot
└── tools
    └── ci
```

## Install

### Windows

Java:
- use your existing Java version 
- ...or follow SikuliX official [quickstart](http://sikulix.com/quickstart/)

FireFox + Container:
- download app [FireFox](https://www.mozilla.org/en-US/firefox/download/thanks/)
- install extension [Firefox Multi-Account Containers](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/)
- open a tab with a container (ex: `Work`)

![alt text](./docs/README/firefox-install-1.png)

![alt text](./docs/README/firefox-install-2.png)

![alt text](./docs/README/firefox-install-3.png)

![alt text](./docs/README/firefox-install-4.png)

SikuliX IDE:
- Download the `v2.0.5` release of `SikuliX IDE` at https://launchpad.net/sikuli/sikulix/2.0.5/+download/sikulixide-2.0.5.jar.

## Usage

### CLI

TODO

### SikuliX IDE

- Start `SikuliX IDE`
- SikuliX:
  - Menu > "File" > "Open" > `C:/...git/sikulix-twitter-bot/plateform/bot-twitter`
  - click "Run"

![alt text](./docs/README/sikulix-usage.png)

## Resources

- Sikulix
  - [SikuliX](http://sikulix.com/)