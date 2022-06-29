---

## !!! PLEASE READ BEFORE USAGE !!!  
This is an unofficial and unsupported fork of JobRunr. Please use it at your own risk but don't open any issue's on the original project when using this fork! Feel free to open an issue on this project instead or consider trying the official version if you experience any issues.

---

## Overview
This is just a fork of the popular JobRunr library,adding smaller features and bugfixes. See the original [GitHub Page](https://github.com/jobrunr/jobrunr) and [website](https://www.jobrunr.io) for more information on how to use the library and consider supporting the original project if you like it.

## Changes added by this fork
- Decreased minimum configurable fetch interval in seconds from 5 to 1 (see https://github.com/jobrunr/jobrunr/issues/366)
- Added backgroundJobServer to JobRunrConfigurationResult (see https://github.com/jobrunr/jobrunr/issues/497)
- Added an option for auto restart on crash to BackgroundJobServerConfiguration (see https://github.com/jobrunr/jobrunr/issues/498)

Installation
------------
 
#### Using Maven?
 
JobRunr is available in Maven Central - all you need to do is add the following dependency:
 
 ```xml
<dependency>
    <groupId>com.lumaserv</groupId>
    <artifactId>jobrunr</artifactId>
    <version>5.1.4-R0</version>
</dependency>
```
 
#### Using Gradle?
 
Just add the dependency to JobRunr:
 ```groovy
implementation 'com.lumaserv:jobrunr:5.1.4-R0'
```

### How to build?
* `git clone https://github.com/LUMASERV/jobrunr.git`
* `cd jobrunr`
* `cd core/src/main/resources/org/jobrunr/dashboard/frontend`
* `npm i`
* `npm run build`
* `cd -`
* `BUILD_VERSION=5.1.4-R0-SNAPSHOT ./gradlew publishToMavenLocal`

Then, in your own project you can depend on `com.lumaserv:jobrunr:5.1.4-R0-SNAPSHOT`.
