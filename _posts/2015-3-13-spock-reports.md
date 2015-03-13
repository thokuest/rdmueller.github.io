---
layout: post
title: How to use the Spock-Reports-Plugin in Grails
tags: [spock, grails]
---

Spock has finally been released as V1.0 and part of the release notes was the announcement that the psock internal reporting module didn't make it to V1.0 but that you should use the cool [spock-reports-plugin by Renato Athaydes](https://github.com/renatoathaydes/spock-reports).

## But how do I use it in Grails? 

First you have to reference it in your `BuildConfig.groovy`

```groovy
    dependencies {
        ...
        test "com.athaydes:spock-reports:1.2.5"
        ...
    }
```

But since it is published in none of the standard repositories configured in Grails, you also have to add the reference to jcenter:

```groovy
    repositories {
        ...
        mavenRepo "http://jcenter.bintray.com"
        ...
    }
```
    
now that was the easy part... to be continued...
