About my code <3 <3 publicado
=====

This repository contains the code for the Twitter feed microservice that you will use during the [Oracle Container Native Application Development workshop](http://oracle.github.io/learning-library/workshops/container-native-development).
During the workshop you will Dockerize this Java microservice using Wercker, configure a CI/CD pipeline, and deploy the microservice to Oracle's managed Kubernetes service.


Build
=====

Build the application and the distribution zip file with the build.sh file.  It simply runs `mvn clean assembly:assembly`.  That will result in a zip file in the target folder that can be uploaded to Java SE CS.


Run Locally
===========

On successful build, you can run the app with `sh target/bin/start` which is a shell script generated by the Maven build that constructs the correct classpath to dependencies in target/repo.


Deploy
======

You will create Wercker pipelines to build, publish, and deploy this microservice during the workshop.


