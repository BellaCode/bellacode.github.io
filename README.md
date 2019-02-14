<link href="//maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">

# Software Craftmanship
While I have been practicing software development for many years, before I read Robert C. Martin's (aka Uncle Bob) blog and the [software craftsmanship manifesto](http://manifesto.softwarecraftsmanship.org/), I didn't have the right term to express my goal.

The craftsmanship manifesto resonates with me. It doesn't have religious overtones, vanity certification, or the hype of other movements and methodologies.  

At my first job, the dev lead I worked for mentored me in quality software development practices. Because I had this early inspiration, I've strived to avoid compromising my coding values because of deadline pressure, silver bullet technologies, or existing poor codebases.  

The craftsman/apprentice partnership is one of the best ways to learn software development. This site is my attempt to share what I've learned.

As of early 2019 I'm refactoring a lot of my previous posts and projects, so your patience is appreciated.

# Code Locality
I organize my code within files a little differently than most developers. By following the computer science principle of code locality I dramatically improve readability, maintainability, and editing speed.  [Read more](/Locality) 

# Code Kits - Web Application
In each new web application project, I end up starting from scratch. Past projects can be kind of hard to tear down to the base libraries I need.  

I have found a technology and tool stack that I really like and would strongly recommend to anyone doing professional or hobby web development. 

I considered creating a Yeoman template. but it feels like too much magic; it is hard to trace back the sequence used to build the template from the end result.

I created [Code Kits](https://github.com/GeoffCox/CodeKits) to document each of the steps.  My first one is for [web apps](https://github.com/GeoffCox/CodeKits/blob/master/webapp/README.md).  I'll be adding some additional flavors in the near future.