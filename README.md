# Gradle Shadow

The main purpose of this fork is to resolve Log4Shell because the original author doesn't want to [maintain](https://github.com/johnrengelman/shadow/issues/739) backport fixes. We would upgrade to shadow [v7.1.2](https://github.com/johnrengelman/shadow/releases/tag/7.1.2) but due to many [API changes](https://docs.gradle.org/current/userguide/upgrading_version_6.html#sec:configuration_removal) of Gradle, we cannot quickly upgrade the shadow jar version in Katalon Gradle Plugin.

Gradle plugin for creating fat/uber JARs with support for package relocation.

## Documentation

Read the [User Guide](http://imperceptiblethoughts.com/shadow)!

## Current Status

<a href='https://bintray.com/johnrengelman/gradle-plugins/gradle-shadow-plugin/view?source=watch' alt='Get automatic notifications about new "gradle-shadow-plugin" versions'><img src='https://www.bintray.com/docs/images/bintray_badge_color.png'></a>
[ ![Download](https://api.bintray.com/packages/johnrengelman/gradle-plugins/gradle-shadow-plugin/images/download.png) ](https://bintray.com/johnrengelman/gradle-plugins/gradle-shadow-plugin/_latestVersion)
[![Circle CI](https://circleci.com/gh/johnrengelman/shadow.png?style=badge)](https://circleci.com/gh/johnrengelman/shadow)

## Latest Test Compatibility

| Gradle Version | Shadow Version |
|----------------|----------------|
| 5.x | 5.2.0|
| 6.x | 5.2.0|

**NOTE**: Shadow v5.+ is compatible with Gradle 5.0+ and Java 7+ _only_.


## Gradle Plugins

https://plugins.gradle.org/plugin/com.github.johnrengelman.shadow

