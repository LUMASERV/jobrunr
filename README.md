## Overview
This is just a fork of the popular JobRunr library,adding smaller features and bugfixes. See the original [GitHub Page](https://github.com/jobrunr/jobrunr) and [website](https://www.jobrunr.io) for more information on how to use the library and consider supporting the original project if you like it.

## Changes added by this fork
Nothing yet

Installation
------------
 
 #### Using Maven?
 
 JobRunr is available in Maven Central - all you need to do is add the following dependency:
 
 ```xml
<dependency>
    <groupId>org.jobrunr</groupId>
    <artifactId>jobrunr</artifactId>
    <version>5.1.0</version>
</dependency>
```
 
 #### Using Gradle?
 
Just add the dependency to JobRunr:
 ```groovy
implementation 'org.jobrunr:jobrunr:5.1.0'
```

### How to build?
* `git clone https://github.com/jobrunr/jobrunr.git`
* `cd jobrunr`
* `cd core/src/main/resources/org/jobrunr/dashboard/frontend`
* `npm i`
* `npm run build`
* `cd -`
* `./gradlew publishToMavenLocal`

Then, in your own project you can depend on `org.jobrunr:jobrunr:1.0.0-SNAPSHOT`.
