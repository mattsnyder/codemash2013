# CodeMash 2013

## The Buzz
* JavaScript
* Gamification
* Single Page Applications

## 10,000 foot view
### JavaScript
Trending this year at CodeMash was Javascript. It was extremely difficult to not attend a talk that did not mention it. Several frameworks have evolved around JavaScript, including AngularJS, Backbone, Node, and Knockout. Testing for Javascript has matured significantly with tools like Jasmine and lineman (see [notes on the Test Double talk](https://github.com/mattsnyder/codemash2013/blob/master/test_double.md)).

On a similar note, [CoffeeScript](http://coffeescript.org) is the language of choice for crafting Javascript as it compiles down to best practice Javascript code that is 99.9% guaranteed to work in IE! And you don't need to work in Rails to use CoffeeScript. You can use the coffee command line tool to watch a directory and have it (re)compile your CoffeeScript as you make changes to it.

### Gamification & Single Page Applications
Dennis and Brian from [SRT Solutions](http://www.srtsolutions.com)
have crafted an application for exploring different ways to write
[single page applications](http://en.wikipedia.org/wiki/Single-page_application).
If you have ever read a choose your own adventure book, you're going to
love this app,
[Choose your own application](http://chooseyourownapplication.com).
The focus is on building your own Single Page Application with your choice of technologies. The application has been "gamified" and "players" earn badges for each choice they make. This is a great opportunity to explore a new technology in a fun way. Technologies covered include *Backbone, Knockout.js, .NET, Rails, Node.js, Heroku, CoffeeScript, and Azure*.

Rails & Single Page Applications => With the release of Rails 4.0, Rails will be adding in default support
for Single Page Applications ([TurboLinks](https://github.com/rails/turbolinks)). It can be disabled by
removing the TurboLinks gem from the Gemfile, otherwise you will need
to disable it on a per link basis. [DHH](http://david.heinemeierhansson.com) has stated he intends to drive
rails in the direction which is best for BaseCamp, so expect more
changes like this in the near future. _My $.02, expect a community fork of
Rails in the near future as well_

[Brian Prince](http://www.brianhprince.com) delivered an excellent talk on [Gamification](http://en.wikipedia.org/wiki/Gamification). He discussed several real world examples where Gamification has led to modifying user behavior, including applications that encourage diabetics to test insulin levels regularly and elderly people living at home alone to stay active and engaged. The important thing to remember is to identify the behavior you want to change and then gamify that aspect of your application to encourage that behavior. Adding badges for the sake of adding badges often results in encouraging the wrong behavior. 

### Machine Learning
[Seth Juarez](http://www.sethjuarez.com) delivered two excellent presentations on Machine Learning. Machine learning allows us to find and exploit patterns in data. There are two main classifications of machine learning, supervsed and unsupervised. Supervised learning allows us to be predictive while unsupervised learning helps us to understand the structure of the data. For more details, read my notes from Seth's talks.

Seth also has a NuGet package that can be imported into Visual Studio.
It is called NuML and can be found [here](http://numl.net). It was
demoed during his talk and looks awesome!

### Real world Javascript testing
Javascript testing has really improved since I last looked into it. Jasmine appears to be the front runner and from what I saw and experienced is my prefered choice. It looks alot like rspec and can use the rspec-given syntax thanks to Justin Searls and [Jasmine-Given](https://github.com/searls/jasmine-given). Justin demonstrated a combination of tools that makes testing Javascript extremely easy. [Lineman](https://github.com/testdouble/lineman) is one of those tools and requires Node.js and NPM in order to install it. Lineman is used to run your Jasmine specs. You can read more about Javascript testing in [my detailed notes on his talk](https://github.com/mattsnyder/codemash2013/blob/master/test_double.md).

### Better Metrics for your team, Nayan Hajratwala
[Nayan Hajratwala](http://agileshrugged.com/blog/) gave a great talk on measuring your team's
effectiveness. Traditionally teams have been measured by cyclomatic
complexity, velocity, hours in office, etc. However none of those
answer what the customer really wants to know ... What is the team's
throughput? 

Throughput is the rate at which features are passing
through the system. Most often teams try to deliver more by putting
more work into the system. However that often results in lower
quality, bottlenecks, and overall lower throughput.

Cycle Time is the time between two succesfully delivered features and
applies Little's Law to compute. Little's Law is described as:
``` 
The average number of work items in a stable system is equal to
their average completion rate, multiplied by their average time in the
system. 
```

To demonstrate, Nyan created 4 teams and had each team play
["The Dot Game"](http://www.netobjectives.com/resources/articles/the-dot-game).
The game has the team divided up into 8 roles and the team measures
how fast they can assemble the "product". The demonstration showed
that by adding more work in progress only resulted in less being
delivered. Nyan then changed the rules of the game such that there was
less work in progress at any given time and repated the game. Each of
the 4 teams saw an avreage of 8x improvement in Cycle Time, huge
improvement in quality and the amount of product produced.

The goal should not be 100% utilization of workforce, it should be
maximizing throughput. This demosnstration showed that by minimizing
work in progress and having each role focus on one thing at a time,
while resulting in less than 100% utilization, resulted in much higher
throughput and higher quality.


