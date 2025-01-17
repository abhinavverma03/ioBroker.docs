---
translatedFrom: en
translatedWarning: Wenn Sie dieses Dokument bearbeiten möchten, löschen Sie bitte das Feld "translationsFrom". Andernfalls wird dieses Dokument automatisch erneut übersetzt
editLink: https://github.com/ioBroker/ioBroker.docs/edit/master/docs/de/adapterref/iobroker.sunnyportal/README.md
title: ioBroker.sunnyportal
hash: N0gUYnO3uswmFbjmUP5qlRzzTLWov6A+hRKm6l7uWk8=
---
![Logo](../../../en/adapterref/iobroker.sunnyportal/admin/sunnyportal.png)

![Build-Status](https://travis-ci.org/marvincaspar/ioBroker.sunnyportal.svg?branch=master)
![NPM-Version](http://img.shields.io/npm/v/iobroker.sunnyportal.svg)
![Downloads](https://img.shields.io/npm/dm/iobroker.sunnyportal.svg)
![Anzahl der Installationen (neueste)](http://iobroker.live/badges/sunnyportal-installed.svg)
![Anzahl der Installationen (stabil)](http://iobroker.live/badges/sunnyportal-stable.svg)
![Abhängigkeitsstatus](https://img.shields.io/david/marvincaspar/iobroker.sunnyportal.svg)
![Bekannte Schwachstellen](https://snyk.io/test/github/marvincaspar/ioBroker.sunnyportal/badge.svg)
![NPM](https://nodei.co/npm/iobroker.sunnyportal.png?downloads=true)

# IoBroker.sunnyportal
![Testen und freigeben](https://github.com/marvincaspar/ioBroker.sunnyportal/workflows/Test%20and%20Release/badge.svg)

## Sunny Portal-Adapter für ioBroker
Jede Minute die aktuellen Daten von Sunny Portal abrufen.

### Einstellungen
![Einstellungen](../../../en/adapterref/iobroker.sunnyportal/./docs/images/settings.png)

### Objektübersicht
![Objektübersicht](../../../en/adapterref/iobroker.sunnyportal/./docs/images/object-overview.png)

## Credits
Ich habe den Code auf [Sunnyportal-API](https://github.com/mkorthuis/sunnyportal-api/) von mkorthuis basiert

## Changelog

### 0.1.5
* (Marvin Caspar) Reduce update interval to 60 seconds

### 0.1.4
* (Marvin Caspar) Rewrite code to fix login issue
* (Marvin Caspar) Add units to ioBroker states

### 0.1.3
* (Marvin Caspar) Fix version

### 0.1.2
* (Marvin Caspar) Fixes for ioBroker repository

### 0.1.1
* (Marvin Caspar) Fix redirect after login
* (Marvin Caspar) Cleanup readme

### 0.1.0
* (Marvin Caspar) Login and fetch current data from sunny portal

### 0.0.1
* (Marvin Caspar) initial release

## License
MIT License

Copyright (c) 2020 Marvin Caspar <info@caspar.dev>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.