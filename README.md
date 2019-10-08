# Wemo

[![Build Status](https://travis-ci.org/DocCodes/wemo.svg?branch=master)](https://travis-ci.org/DocCodes/wemo)
[![Documentation Status](http://img.shields.io/badge/docs-1.0.4-orange.svg?style=flat)](https://github.com/DocCodes/wemo/wiki)
[![Release](https://img.shields.io/github/release/doccodes/wemo.svg)](https://github.com/DocCodes/wemo/releases/latest)
[![Beta](https://img.shields.io/github/release/doccodes/wemo/all.svg?label=nightly)](https://github.com/DocCodes/wemo)

## What is this branch?
Basically I didn't need the script to do the port sweep that it does. So I just branched it so that it'd talk to my specific device in the office.

## Installation
### Windows
```
pip3 install wemo
```
### macOS
```
sudo -H pip3 install wemo
```
### Linux
```
sudo pip3 install wemo
```

## How-To Use
```
import wemo

bedroom = wemo.switch('192.168.1.72')
bedroom.enable()
```
output
```
1 # The status of the light
```
## Requirements
Any requirements will automatically be installed using the aforementioned installation method

To install any modules use `pip3 install (module)`
* requests
