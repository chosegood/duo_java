# Overview

**duo_java** - Duo two-factor authentication for Java web applications

Duo provides simple two-factor authentication as a service via:

1.  Phone callback
2.  SMS-delivered one-time passcodes
3.  Duo mobile app to generate one-time passcodes
4.  Duo mobile app for smartphone push authentication
5.  Duo hardware token to generate one-time passcodes

This package allows a web developer to quickly add Duo's interactive, self-service, two-factor authentication to any web login form - without setting up secondary user accounts, directory synchronization, servers, or hardware.

What's here:

* `src/main/js` - Duo Javascript library, to be hosted by your webserver.
* `src/main/java` - Duo Java SDK to be integrated with your web application, including unit tests

# Usage

Developer documentation: <http://www.duosecurity.com/docs/duoweb>

To build:
mvn clean install

# Support

Questions? Join the duo_web mailing list at
<http://groups.google.com/group/duo_web>

Report any bugs, feature requests, etc. to us directly:
<https://github.com/duosecurity/duo_java/issues>

Have fun!

<http://www.duosecurity.com>
