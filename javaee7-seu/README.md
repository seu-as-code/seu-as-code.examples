[![Stories in Ready](https://badge.waffle.io/seu-as-code/seu-as-code.examples.png?label=ready&title=Ready)](https://waffle.io/seu-as-code/seu-as-code.examples)
[![Stories in Progress](https://badge.waffle.io/seu-as-code/seu-as-code.examples.png?label=in%20progress&title=In%20Progress)](https://waffle.io/seu-as-code/seu-as-code.examples)
[![Apache License 2](http://img.shields.io/badge/license-ASF2-blue.svg)](https://github.com/seu-as-code/seu-as-code.examples/blob/master/LICENSE)
[![Join on Chat](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/seu-as-code/seu-as-code?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

# JavaEE7 SEU-as-Code Example

This example is a simple JavaEE7 development environment. It contains the following packages and features:
- the SEU must be mounted under `J:`
- custom SEU environment package located in the `repo/` directory
- the OpenJDK 8u40 package is installed locally in the SEU
- additionally Maven 3.3.3 and Gradle 2.5 are installed as build tools
- a Glassfish v4.1 application server is installed
- custom Gradle tasks in the SEU to handle the Glassfish domain
- the examples Git repository can be cloned using the Git plugin
