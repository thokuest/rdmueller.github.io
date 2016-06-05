---
layout: post
title: Why you should use AsciiDoc to document your Software Solution
tags: [asciidoc, documentation]
---

Last week I wrote about why I don't like  Word, but I didn't mention an alternative.

For me, AsciiDoc as markup format is a perfect alternative for technical documents. Together with the tooling provided by the AsciiDoctorJ community it fulfills all my requirements.

AsciiDoc is a plain text format and thus just stores the information you want to document. The text will contain - besides tables - no layout. The layout is created by whatever renderer you chose. Since you don't have to worry about the layout, it also will not distract you. No "argh - how do I get this paragraph together with the diagram on one page?"!

And since it is plain text, you can happily store it along with the source code of your project. This not only solves versioning problems. You can now apply version control, "code"-review and diffs the same way you are used to do with your code. It also solves the first problem of your information architecture: Where are documents stored?

Now, let's take a look at the extrafeatures AsciiDoc provides over real plain text.

Images are referenced and not embedded.

http://asciidoctor.org/docs/asciidoc-syntax-quick-reference/#images

```
image::sunset.jpg[] 
image::sunset.jpg[Sunset] 
[[img-sunset]] 
image::sunset.jpg[caption="Figure 1: ", title="A mountain sunset", alt="Sunset", width="300", height="200", link="http://www.flickr.com/photos/javh/5448336655"] 
image::http://asciidoctor.org/images/octocat.jpg[GitHub mascot]
```

This opens up new possibilities when you want to keep your documents up to date.

