---
layout: post
title: "Next Level: PlantUML with Gradle"
tags: [asciidoc, doc, gradle]
---

In my blog post about why I love AsciiDoc, I wrote about the usage of plantUml in AsciiDoc. Today I will show you how to 
configure your Gradle build in such a way that a block like this

``` 
[plantUML,"test",png]
----
class Animal 
class Cat 
class Dog 
Animal <|-- Cat 
Animal <|-- Dog
----
```

will be rendered as Class-Diagram like this

<div> <img src="../images/renderedDiagram.png" style="max-width: 100%" /> </div> 

## Cleanup first

Last time I've added a default task to the maven build for convenience. Let's do the same with the `build.gradle` by appending

``` 
// let's set a defaultTask for convenience
defaultTasks 'asciidoctor'
``` 



## The JRuby Gradle-Plugin

Since most AsciiDoctor plugins exist as Ruby Gems, we first need to Last time we created a Gradle project to render an AsciiDoc file. 

## Conclusion

As you can see, it is easy to combine AsciiDoc with planUML to define UML diagrams _within_ your documentation.

<div> <img src="../images/renderedPlantUml.png" style="max-width: 100%" /> </div>

But one question still remains:

### When does it make sense to use plantUML within your document?


<div style="float:right"><a href="https://www.amazon.de/arc42-Aktion-Praktische-Tipps-Architekturdokumentation/dp/3446448012/ref=as_li_ss_il?ie=UTF8&redirect=true&ref_=as_li_qf_sp_asin_il_tl&linkCode=li1&tag=&linkId=6ed21b5fbad8c1d5793fe05122b6ed2d" target="_blank"><img border="0" src="//ws-eu.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=3446448012&Format=_SL110_&ID=AsinImage&MarketPlace=DE&ServiceVersion=20070822&WS=1&tag=" ></a><img src="https://ir-de.amazon-adsystem.com/e/ir?t=&l=li1&o=3&a=3446448012" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" /></div>

The new book [Communicating Software Architecture](https://leanpub.com/arc42inpractice)(English) / [arc42 in Aktion](http://amzn.to/29UUm0p) by [Gernot Starke](https://twitter.com/gernotstarke) and Peter Hruschka provides a good answer. Since you nearly can't control the layout of plantUML, it only makes sense when you don't have to manually control the layout.

PS: the docToolchain project greated above is available on github: [https://github.com/rdmueller/docToolchain](https://github.com/rdmueller/docToolchain/tree/d2f288bab48d5636172852fa7ef0d2332f9bca68)

