---
layout: post
title: "Beyond HTML"
tags: [doc, asciidoc]
---

Up until now, the docToolchain build only generates HTML5 output. It looks nice, but sometimes you need different formats. For instance, when you want to share your architecture via mail, a single file format like PDF would be helpful - and this is one of the strengths of asciidoctor: it makes it easy to render your content in different formats.

For the Gradle-Build, I Just add a reference to the [asciidoctor-pdf](https://github.com/asciidoctor/asciidoctor-pdf) plugin and tell the asciidoctor task to render PDF in addition:

{% highlight groovy %}
...

dependencies {
    // this is the gem we need for diagrams
    gems 'rubygems:asciidoctor-diagram:1.5.1'
    gems 'rubygems:asciidoctor-pdf:1.5.0.alpha.12'
}
asciidoctor {
    backends 'html5', 'pdf'

...

{% endhighlight %}
