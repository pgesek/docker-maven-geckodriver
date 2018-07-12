Maven & Geckodriver Docker Image
================================

This is a Docker image based on the maven-jdk-9 image (ubuntu). This image comes with Geckodriver v0.21 and Firefox preinstalled, which will allow you to run Selenium tests in a Dockerized environment, like BitBucket pipelines, without going into a very complicated setup.

Information
-----------

* Firefox is installed using apt-get and available on the PATH.
* Geckodriver is installed under /usr/bin/geckodriver

