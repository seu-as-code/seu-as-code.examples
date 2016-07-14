[![Stories in Ready](https://badge.waffle.io/seu-as-code/seu-as-code.examples.png?label=ready&title=Ready)](https://waffle.io/seu-as-code/seu-as-code.examples)
[![Stories in Progress](https://badge.waffle.io/seu-as-code/seu-as-code.examples.png?label=in%20progress&title=In%20Progress)](https://waffle.io/seu-as-code/seu-as-code.examples)
[![Apache License 2](http://img.shields.io/badge/license-ASF2-blue.svg)](https://github.com/seu-as-code/seu-as-code.examples/blob/master/LICENSE)

# Multi-Platform SEU-as-code Example

This example is a multi platform software development environment supporting both
Windows and MacOS in one SEU definition. It showcases the following features:
- the SEU must be mounted under `P:` or `/Volumes/Platform-SEU`
- the home and environment dependency are installed as normal dependencies
- the environment dependency is installed using the OS qualifier
- a different version of Gradle is installed for Windows and MacOS using the platform closures
- the platform specific tasks are enabled depending on the platform
