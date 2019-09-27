# **centos-openjdk**
___

### Description

This image adds [OpenJDK](http://openjdk.java.net/) to a base [**Centos**](https://hub.docker.com/r/centos/centos/) Linux distribution.

The *latest* tag of this image is build using the last available Centos Docker image and the last available Oracle JDK.
You can pull it with:

    docker pull comchangs/centos-openjdk


You can also find other images based on different OpenJDK releases, using different tags in the following form:

    docker pull comchangs/centos-openjdk:[openjdk-release]


For example, if you want a Centos with OpenJDK release 8 you can pull the image with:

    docker pull comchangs/centos-openjdk:8


Run with Docker Compose:

    docker-compose run centos-openjdk java -version


Run with Docker run:

    docker run comchangs/centos-openjdk java -version


Available tags:


- OpenJDK 9 ([9](https://github.com/comchangs/docker-centos-openjdk/blob/9/Dockerfile), [latest](https://github.com/comchangs/docker-centos-openjdk/blob/latest/Dockerfile))
- OpenJDK 8 ([8](https://github.com/comchangs/docker-centos-openjdk/blob/8/Dockerfile))
- OpenJDK 7 ([7](https://github.com/comchangs/docker-centos-openjdk/blob/7/Dockerfile))
