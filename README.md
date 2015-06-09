WebChimera.js
---
libvlc binding for node.js/io.js/NW.js/Electron

[![Join the chat at https://gitter.im/RSATom/WebChimera](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/RSATom/WebChimera?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Demos
* https://github.com/jaruba/wcjs-player
* https://github.com/RSATom/wcjs-ugly-demo

## Build Prerequisites
### Windows
* [Visual Studio Community 2013](https://www.visualstudio.com/en-us/products/visual-studio-community-vs.aspx);
* [VLC Player](http://www.videolan.org/vlc/download-windows.html) in your PATH environment variable;
* [CMake](http://www.cmake.org/);
* [io.js](https://iojs.org) or [Node.js](https://nodejs.org);

### Linux
for apt based distros:
```bash
$ sudo apt-get install build-essential cmake libvlc-dev
```

## Build from sources
### Windows
* `npm install -g cmake-js`
* `git clone --recursive https://github.com/RSATom/WebChimera.js.git`
* `cd WebChimera.js`
* `build_nw.cmd` or `build_electron.cmd`

### Linux
Clone repository
```bash
$ git clone --recursive https://github.com/RSATom/WebChimera.js.git && cd WebChimera.js
```

Run npm install script
```bash
$ npm install
```

Test demo in nw.js
```bash
$ cd demos/ugly
$ npm install
$ sudo npm install nw -g
$ nw
```
