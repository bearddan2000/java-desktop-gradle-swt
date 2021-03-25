# java-desktop-gradle-swt

## Description
This is a POC project to demonstrate a
java swing application running inside a
docker container. Built with multistage
docker file with gradle.

## Tech stack
- gradle
- java
  - jre 11
  - swing

## Docker stack
- ubuntu:latest
- gradle:jdk11

## To run
```xhost +localhost && sudo ./install.sh -u```

## To stop (optional)
```xhost && sudo ./install.sh -d```

## To see help
`sudo ./install.sh -h`
