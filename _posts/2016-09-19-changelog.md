---
layout: post
title: "The only constant in life is change"
tags: [doc, asciidoc, arc42]
---

Today I will show how to add a change log to your documents. Git is quite good when it comes to log changes, so why not use git to add a table of changes to your document? If your version your documents along with your code, you don't want to see all code commits in the change log of your documents. But git can handle this.

If you type 'git log src/docs/arc42', it will only output the changes made to the files in 'src/docs/arc42'. That's already a great feature, but not enough to include it into the asciidoc template. 

First, the changes have to be parsed and re-formatted to asciidoc. There are git libraries somewhere which let you do this programatically, but I am a bit more practical. I used nearly the same approach I used for (exporting the Sparx EA diagrams)[https://rdmueller.github.io/sparx-ea/]: I just use groovy to execute a shell command. In this case, I only need the output and don't care to see what happens during the process. Since fetching the changes is quite fast, a simpel groovy statement like this is enough:

    def res = "git log ./src/docs/arc42".execute().text
    
This executes the command and returns the whole change log as string.    
