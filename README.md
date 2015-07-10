## MultiBit Commons

Build status: [![Build Status](https://travis-ci.org/bitcoin-solutions/multibit-commons.png?branch=develop)](https://travis-ci.org/bitcoin-solutions/multibit-commons)

This repo contains the source for the MultiBit Commons library.

From a technical point of view this project uses

* Java - Primary language of the app
* [Maven](http://maven.apache.org/) - Build system
* [Guava](https://github.com/google/guava) - Excellent support libraries for Java

## Branches

We follow the ["Git Flow" branching strategy](http://nvie.com/posts/a-successful-git-branching-model/).

This means that the latest release is on the "master" branch (the default) and the latest release candidate is on the "develop" branch.
Any issues are addressed in feature branches from "develop" and merged in as required.

## Verify you have Maven 3+

Most IDEs (such as [Intellij Community Edition](http://www.jetbrains.com/idea/download/)) come with support for Maven built in,
but if not then you may need to [install it manually](http://maven.apache.org/download.cgi).

IDEs such as Eclipse may require the [m2eclipse plugin](http://www.sonatype.org/m2eclipse) to be configured.

To quickly check that you have Maven 3+ installed check on the command line:

    mvn --version

A quick way to install Maven on Mac is to use HomeBrew.

## Manually build and install MultiBit HD Commons library (multibit-commons)

At present it is necessary to checkout [multibit-hd](https://github.com/bitcoin-solutions/multibit-commons/) and
build it manually. You will need to use the HEAD of the `develop` branch.

    mvn clean install

Later this will be available in a host repository (such as Maven Central) which will simplify the build process.
