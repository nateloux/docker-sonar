Forked from MehrCurry/docker-sonar and modified to:

  * Not have the external DB dependency
  * Use the plugins I'm interested in


Docker Image for Sonarqube
==========================

It uses the offical sonarqube image now and installs selected plugins into
a data-only container.

Just use docker-compose to run as normal i.e. `docker-compose up -d`

NOTE: To rebuild the plugin container you have to use docker-compose build
