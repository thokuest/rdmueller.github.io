<!DOCTYPE html>
<!--[if IEMobile 7 ]><html class="no-js iem7"><![endif]-->
<!--[if lt IE 9]><html class="no-js lte-ie8"><![endif]-->
<!--[if (gt IE 8)|(gt IEMobile 7)|!(IEMobile)|!(IE)]><!--><html class="no-js" lang="en"><!--<![endif]-->

<head>
  <meta charset="utf-8">
  <title>About - R.D.Müller - Bits from my Brain</title>
  <meta name="author" content="Ralf D. Müller">
  
  
  <!-- http://t.co/dKP3o1e -->
  <meta name="HandheldFriendly" content="True">
  <meta name="MobileOptimized" content="320">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <link rel="canonical" href="/About.md">
  <link href="/images/favicon-eec3051d5c356d1798bea1d8a3617c51.png" rel="icon">
  <link href="/stylesheets/screen-212a3205d97b53ef71581e910c98f79c.css" media="screen, projection" rel="stylesheet" type="text/css">
  <link href="atom.xml" rel="alternate" title="R.D.Müller - Bits from my Brain" type="application/atom+xml">
  
    <script src="/javascripts/libs/jquery.min-663628f795cb62444143fde1ebdf2b5b.js" type="text/javascript"></script>
  
    <script src="/javascripts/modernizr-2.0-f86b862d5ee138da61daf47f24116ed7.js" type="text/javascript"></script>
  
    <script src="/javascripts/octopress-52bd0860c81b8af484852d75380d38f3.js" type="text/javascript"></script>
  
    <script src="/javascripts/github-2c23ec60bbc7e962f6324b25d8b2ae44.js" type="text/javascript"></script>
  
    <script src="/javascripts/jquery.tweet-408e79928ca077df30b72fe36df5754e.js" type="text/javascript"></script>
  
    <script src="/javascripts/twitter-options-5e0a859802705e93583ec7d344aa7239.js" type="text/javascript"></script>
  
  

  <!--Fonts from Google"s Web font directory at http://google.com/webfonts -->
<link href="http://fonts.googleapis.com/css?family=PT+Serif:regular,italic,bold,bolditalic" rel="stylesheet" type="text/css">
<link href="http://fonts.googleapis.com/css?family=PT+Sans:regular,italic,bold,bolditalic" rel="stylesheet" type="text/css">

</head>


<body 
   >
  <header role="banner"><hgroup>
  <h1><a href="/">R.D.Müller - Bits from my Brain</a></h1>
  
    <h2>making the software-world a better place one document at a time</h2>
  
</hgroup>

</header>
  <nav role="navigation"><ul class="subscription" data-subscription="rss ">
  <li><a href="/atom.xml" rel="subscribe-rss" title="subscribe via RSS">RSS</a></li>
  
</ul>

  <form action="http://google.com/search" method="get">
    <fieldset role="search">
      <input type="hidden" name="q" value="site:" />
      <input class="search" type="text" name="q" results="0" placeholder="Search"/>
    </fieldset>
  </form>

<ul class="main-navigation">
  <li><a href="about.html">About</a></li>
  
    <li><a href="/">Blog</a></li>
  
    <li><a href="/About.md">About</a></li>
  
    <li><a href="/archives/">Archives</a></li>
  
</ul>

</nav>
  <div id="main">
    <div id="content">
      
<div class="blog-index">
  <article class="hentry" role="article">
    <p>My goal is to make the software-world a better place with one doc at a time.</p>
<p>I truely believe that one of the biggest problems of the software-world isn't technology, skills or quality in the broad sense but missing <strong>documentation</strong>. Another is missing <strong>simplicity</strong>.</p>
<p><strong>Regarding the documentation</strong> - there are some open source projects out there which do have great user documentation, but as soon as you try to change the code, you are on your own - no documentation of the solution architecture. I only remember one open source project with a proper documentation of the solution architecture (http://biking.michael-simons.eu/docs/index.html), but maybe I don't know enough OS projects :-)</p>
<p>So my aim is to build software on <a href="http://arc42.de">the works of Gernot Starke and Peter Hruschka</a> to make use of arc42 even easier. In order to achieve this goal, there are the following ressources available:</p>
<ul>
<li>the original arc42 pages in <a href="http://arc42.de">german</a> and <a href="http://arc42.org">english</a> (Created by Gernot Starke and Peter Hruschka)</li>
<li>the <a href="https://github.com/arc42">arc42 ressources on github</a></li>
<li>github.io pages containing the links to all known available <a href="http://arc42.github.io/">arc42 templates in different formats</a></li>
<li>the <a href="https://github.com/rdmueller/asciidoc2confluence">asciidoc2confluence-script</a> to easily publish your docs to confluence</li>
</ul>
<p>In addition to arc42, my second stream of thoughts is about the documentation of test results. The red/green output of unit tests is often not enough - it doesn't say <em>what</em> has been tested and also reading the code is not the solution for all stakeholders.</p>
<p>So I first came up with the <a href="https://github.com/rdmueller/grails-filmStrip">Grails FilmStrip-Plugin</a> which displays screenshots made with the functional test module of <a href="https://www.grails.org">Grails</a>, as a film strip. This way, anybody can easily inspect those screens and check <em>what</em> has been tested.</p>
<p>Together with <a href="https://twitter.com/tokraft">Tobias Kraft</a> we developed this idea further and merged the test specification created for <a href="https://github.com/spockframework">Spock</a> Tests with the screenshots made with <a href="http://www.gebish.org/">Geb</a> and came up with a good looking test report. As a result, there is</p>
<ul>
<li>the <a href="https://github.com/rdmueller/Excel2Spec">execl2spec</a> script on github which let's you define the spock specification in a spreadsheet. A script will turn the spreadsheet in a Spock test skeleton.</li>
<li>a <a href="https://github.com/rdmueller/etka15">full blown example</a> for creating asciidoc based test reports with Geb based screenshots</li>
<li>we presented the example at <a href="https://entwicklertag.de/karlsruhe/2015/spock-und-geb-bersichtlich-und-nachvollziehbar-testen-f-r-alle">Entwicklertag Karlsruhe 2015</a> (<a href="https://www.youtube.com/watch?v=L75DdPon5Gk">video</a>)and <a href="https://www.javaland.eu/de/archiv-2016/">JavaLand 2016</a> (both talks where held in german)</li>
</ul>
<p><strong>When it comes to simplicity</strong> I often have to think about a talk given by <a href="https://twitter.com/mittie">Dierk König</a> with the headline <a href="https://www.dropbox.com/s/ui38pl12wobrgdl/Dierk_Koenig-Einfach-JAX2013.pdf?dl=0">"Einfach" - "Simple"</a>. The "facts" presented in this talk might not have a scientific foundation, but they sum up what many of us experience every day and Edsger Dijkstra fomulated as "Simplicity is a great virtue but it requires hard work to achieve it and education to appreciate it. And to make matters worse: complexity sells better."</p>
<hr />
<p>The Blog uses github pages together with <a href="https://github.com/jekyll/jekyll">Jekyll</a> as engine. Template from <a href="http://www.jekyllnow.com/">Jekyll Now</a></p>
<h4>Contribute</h4>
<p>You've found a typo? You've got a good idea for an article for this blog?</p>
<p>Just for this repository on https://github.com/rdmueller/rdmueller.github.io and send a pull request!</p>
<h4>Contact me</h4>
<p><a href="mailto:ralf.d.mueller@gmail.com">ralf.d.mueller@gmail.com</a></p>

  </article>

</div>

<aside class="sidebar">
  
    
<section>
  <h1>About Me</h1>
  <p>Groovy & Grails Developer, Solution Architect, arc42 enthusiast.</p>
</section>


  
    <section>
    <a href="https://stackexchange.com/users/70694"><img src="https://stackexchange.com/users/flair/70694.png" width="208" height="58" alt="profile for Ralf on Stack Exchange, a network of free, community-driven Q&amp;A sites" title="profile for Ralf on Stack Exchange, a network of free, community-driven Q&amp;A sites"></a>
</section>
  
    <section>
  <h1>Recent Posts</h1>
  <ul id="recent_posts">
    
      <li class="post">
        <a href="/blog/2016/06/26/why-you-should-use-asciidoc-to-document-your-software-solution/">Why You Should Use AsciiDoc to Document Your Software Solution</a>
      </li>
    
      <li class="post">
        <a href="/blog/2016/05/16/why-i-don-t-like-word-to-write-documentation/">Why I Don't Like Word to Write Documentation</a>
      </li>
    
      <li class="post">
        <a href="/blog/2016/05/09/groovy-is-java-is-groovy/">Groovy Is Java Is Groovy...</a>
      </li>
    
      <li class="post">
        <a href="/blog/2016/04/30/a-groovy-notebook/">A Groovy Notebook</a>
      </li>
    
      <li class="post">
        <a href="/blog/2016/04/28/wacom-bamboo-spark-could-have-been-so-much-more/">Wacom Bamboo Spark - Could Have Been So Much More...</a>
      </li>
    
  </ul>
</section>

  
    
<section>
    <!-- Latest Tweets -->
    <h1>My Tweets</h1>

    <div class="tweet query footer"><!-- Tweets Code --></div>

    <!-- Twitter Follow Button which allows users to follow a Twitter account -->
    
    <a href="https://twitter.com/RalfDMueller"
       class="twitter-follow-button"
       data-show-screen-name="true"
       data-show-count="true"
       data-lang="en"
       data-size="large">
        Follow @RalfDMueller
    </a>
    <script>!function (d, s, id) {
        var js, fjs = d.getElementsByTagName(s)[0];
        if (!d.getElementById(id)) {
            js = d.createElement(s);
            js.id = id;
            js.src = "http://platform.twitter.com/widgets.js";
            fjs.parentNode.insertBefore(js, fjs);
        }
    }(document, "script", "twitter-wjs");
    </script>
    

</section>


  
    
<section>
  <h1>GitHub Repos</h1>
  
  
    <a href="https://github.com/RDMueller">RDMueller</a> on GitHub
  
  
</section>


  
</aside>



    </div>
  </div>
  <footer role="contentinfo"><p>
  Copyright &copy; 2016 - Ralf D. Müller -
  <span class="credit">Powered by <a href="http://sysgears.com/grain/">Grain</a></span>
</p>

</footer>
  <!-- Load script if disquss comments are enabled and `page.comments` is either empty (index) or set to true -->



  <div id="fb-root"></div>
  <script>
    (function(d, s, id) {
      var js, fjs = d.getElementsByTagName(s)[0];
      if (d.getElementById(id)) {return;}
      js = d.createElement(s); js.id = id; js.async = true;
      js.src = "//connect.facebook.net/en_US/all.js#appId=212934732101925&xfbml=1";
      fjs.parentNode.insertBefore(js, fjs);
      }(document, 'script', 'facebook-jssdk'));
  </script>



  <script type="text/javascript">
    (function() {
      var script = document.createElement('script'); script.type = 'text/javascript'; script.async = true;
      script.src = 'https://apis.google.com/js/plusone.js';
      var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(script, s);
    })();
  </script>



  <script type="text/javascript">
    (function(){
      var twitterWidgets = document.createElement('script');
      twitterWidgets.type = 'text/javascript';
      twitterWidgets.async = true;
      twitterWidgets.src = 'http://platform.twitter.com/widgets.js';
      document.getElementsByTagName('head')[0].appendChild(twitterWidgets);
    })();
  </script>


<!-- Place your javascript or css declarations here so that they will be placed after footer -->


</body>

</html>
