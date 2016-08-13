# OmegaT project to translate IntelliJ platform resources in Japanese.

This project is a community translation project to intellij sdk docs.

## Prerequisite

You need to have Java Runtime Environment version 1.8 or later.

## How to generate translation files for Intellij community

Please call Gradle build system `gradlew` command from console.

```
$ ./gradlew translate
```

If you runs it on MS Windows platform, please call batch file.

```
$ .\gradlew.bat translate
```

Generator depends on a couple of libraries and applications, you need to connect
your platform to internet. If you are behind proxy server or firewall, please
refer Gradle documentation how to configure Gradle for network connections.
It will download some jar files from https://jcenter.bintray.com repository.

## How to translate

The project use OmegaT, Computer Aided Translation tool.
OmegaT is an Open Source Software and freely available for translators.
It is a kind of a translation memory.

The repository is designed to work with OmegaT team features. This means
translators who work on the repository are collaborative team.

## Contributions

Translation updates are not supporeted to merge with PR. Instead of push a request,
please ask us to join as a member who can write a repository.

OmegaT has a team feature. It automatically push translation contribution
onto github repository.

If you want to join, please leave a issue to express your will.

We use custom version of OmegaT Version 4.0 snapshot for automation of the project.
Also we bundles custom plugin that support XML fils in IntelliJ platform.
You should use gradle to launch custom OmegaT;

```
$ ./gradlew omegat
```

It automatically start omegat GUI and prepare environment for you.
You need to install JRE 1.8 or later to run OmegaT.

## License

Translation memories are distributed on the Apache 2.0 License.


## Copyright

Copyright 2016      Hiroshi Miura
