# CodeMash 2013

## The Buzz
* JavaScript
* Gamification
* Single Page Applications

## 10,000 foot view
### JavaScript
Trending this year at CodeMash was Javascript. It was extremely difficult to not attend a talk that did not mention it. Several frameworks have evolved around JavaScript, including AngularJS, Backbone, Node, and Knockout. Testing for Javascript has matured significantly with tools like Jasmine and lineman (see notes on the Test Double talk).

On a similar note, CoffeeScript appears to the language of choice for crafting Javascript as it compiles down to best practice Javascript code that is 99.9% guaranteed to work in IE! And you don't need to work in Rails to use CoffeeScript. You can use the coffee command line tool to watch a directory and have it (re)compile your CoffeeScript as you make changes to it.

### Gamification & Single Page Applications
The guys from SRT crafted an application for exploring all of the above. If you ever read a choose your own adventure book, you're going to love thei app, Choose your own application. The focus is to build your own Single Page Application with your choice of technologies. The application has been gamified and "players" can earn badges for each choice they make. This is a great opportunity to explore a new technology in a fun way. Technologies covered include Backbone, Knockout, .NET, Rails, Node.js, Heroku, CoffeeScript, and Azure.

Brian Prince delivered an excellent talk on Gamification. He discussed several real world examples where Gamification has led to modifying user behavior, including applications that encourage diabetics to test insulin levels regularly and elderly people living at home alone to stay active and engaged. The important thing to remember is to identify the behavior you want to change and then gamify that aspect of your application to encourage that behavior. Adding badges for the sake of adding badges often results in encouraging the wrong behavior. 

With the release of Rails 4.0, Rails will be adding in default support for Single Page Applications (TurboLinks). 

### Machine Learning
Seth Juarez delivered two excellent presentations on Machine Learning. Machine learning allows us to find and exploit patterns in data. There are two main classifications of machine learning, supervsed and unsupervised. Supervised learning allows us to be predictive while unsupervised learning helps us to understand the structure of the data. For more details, read my notes from Seth's talks.

Seth also has a NuGet package that can be imported into Visual Studio. It is called NuML and can be found [here](http://numl.net)

## Real world Javascript testing
Javascript testing has really improved since I last looked into it. Jasmine appears to be the front runner and from what I saw and experienced is my prefered choice. It looks alot like rspec and can use the rspec-given syntax thanks to Justin Searls and [Jasmine-Given](https://github.com/searls/jasmine-given). Justin demonstrated a combination of tools that makes testing Javascript extremely easy. [Lineman](https://github.com/testdouble/lineman) is one of those tools and requires Node.js and NPM in order to install it. Lineman is used to run your Jasmine specs. You can read more about Javascript testing in my detailed notes on his talk.

## Better Metrics for your team, Nayan Hajratwala


## Simple & Beautiful Rails Code