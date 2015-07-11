---
layout: post
title: DRAFT: Spock-Reports for Grails 3.0
tags: [spock, grails]
---

[Spock-Reports](https://github.com/renatoathaydes/spock-reports) is a great way to create better reports for [Spock](https://github.com/spockframework/spock).

Since Grails 3.0 is based on Gradle, integrating the Spock-Reports is easy. Just open your `build.gradle` file and add

```groovy
repositories {
  [...]
  //for spock-reports
  jcenter()
}
```

to the `repositories` section and

```groovy
dependencies {
  [...]
  //for spock-reports
  testCompile 'com.athaydes:spock-reports:1.2.5'  
}
```

to the `dependencies` section.

that's it... The next time you run `grails test-app`, you'll find the generated Spock-Reports in `/build/spock-reports/`
