dsadasParachute
=========

# General idea

The idea is to make an open-source "easy-to-use" service for building and distributing(OTA) iOS apps. Something similar to [TestFlight](https://www.testflightapp.com/) or [HockeyApp](http://hockeyapp.net/).

Service will include:

1. Back-end that will receive package, parse it, prepare manifest and deploy it.
2. Mobile app that will communicate with back-end and build a list of available apps.
3. Scripts that will automate environment configuration for Xcode project (Development, QA, Production).
