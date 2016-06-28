---
layout: page
title: About
permalink: /about/
---

My goal is to make the software-world a better place with one doc at a time.

I truely believe that one of the biggest problems of the software-world isn't technology, skills or quality in the broad sense but missing **documentation**. Another is missing **simplicity**.

**Regarding the documentation** - there are some open source projects out there which do have great user documentation, but as soon as you try to change the code, you are on your own - no documentation of the solution architecture. I only remember one open source project with a proper documentation of the solution architecture (http://biking.michael-simons.eu/docs/index.html), but maybe I don't know enough OS projects :-)

So my aim is to build software on [the works of Gernot Starke and Peter Hruschka](http://arc42.de) to make use of arc42 even easier. In order to achieve this goal, there are the following ressources available:

- the original arc42 pages in [german](http://arc42.de) and [english](http://arc42.org) (Created by Gernot Starke and Peter Hruschka)
- the [arc42 ressources on github](https://github.com/arc42)
- github.io pages containing the links to all known available [arc42 templates in different formats](http://arc42.github.io/)
- the [asciidoc2confluence-script](https://github.com/rdmueller/asciidoc2confluence) to easily publish your docs to confluence

In addition to arc42, my second stream of thoughts is about the documentation of test results. The red/green output of unit tests is often not enough - it doesn't say _what_ has been tested and also reading the code is not the solution for all stakeholders.

So I first came up with the [Grails FilmStrip-Plugin](https://github.com/rdmueller/grails-filmStrip) which displays screenshots made with the functional test module of [Grails](https://www.grails.org), as a film strip. This way, anybody can easily inspect those screens and check _what_ has been tested.

Together with [Tobias Kraft](https://twitter.com/tokraft) we developed this idea further and merged the test specification created for [Spock](https://github.com/spockframework) Tests with the screenshots made with [Geb](http://www.gebish.org/) and came up with a good looking test report. As a result, there is

- the [execl2spec](https://github.com/rdmueller/Excel2Spec) script on github which let's you define the spock specification in a spreadsheet. A script will turn the spreadsheet in a Spock test skeleton.
- a [full blown example](https://github.com/rdmueller/etka15) for creating asciidoc based test reports with Geb based screenshots
- we presented the example at [Entwicklertag Karlsruhe 2015](https://entwicklertag.de/karlsruhe/2015/spock-und-geb-bersichtlich-und-nachvollziehbar-testen-f-r-alle) ([video](https://www.youtube.com/watch?v=L75DdPon5Gk))and [JavaLand 2016](https://www.javaland.eu/de/archiv-2016/) (both talks where held in german)

**When it comes to simplicity** I often have to think about a talk given by [Dierk König](https://twitter.com/mittie) with the headline ["Einfach" - "Simple"](https://www.dropbox.com/s/ui38pl12wobrgdl/Dierk_Koenig-Einfach-JAX2013.pdf?dl=0). The "facts" presented in this talk might not have a scientific foundation, but they sum up what many of us experience every day and Edsger Dijkstra fomulated as "Simplicity is a great virtue but it requires hard work to achieve it and education to appreciate it. And to make matters worse: complexity sells better."

---


The Blog uses github pages together with [Jekyll](https://github.com/jekyll/jekyll) as engine. Template from [Jekyll Now](http://www.jekyllnow.com/)

#### Contribute

You've found a typo? You've got a good idea for an article for this blog?

Just for this repository on https://github.com/rdmueller/rdmueller.github.io and send a pull request!

#### Contact me

[ralf.d.mueller@gmail.com](mailto:ralf.d.mueller@gmail.com)
