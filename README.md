# a2z
[JavaScript for text-based data, Shiffman, ITP, Fall 2016 on github][1]  
[Programming with Text - shiffman video playlist on youtube][3]

----------

##### requires
- [http-server via npm][4]
     - `npm install http-server -g`
- [node.js install for macos][5]
- Atom


##### to run locally:  
- run `http-server` in root along with LiveReload app and Chrome extension OR
- use Atoms atom-live-server
     - usage:
```
     ctrl-alt-l: launch live server on port 3000  
     ctrl-alt-q: stop live server 
     ctrl-alt-3: launch live server on port 3000   
     ctrl-alt-4: launch live server on port 4000   
     ctrl-alt-5: launch live server on port 5000   
     ctrl-alt-8: launch live server on port 8000   
     ctrl-alt-9: launch live server on port 9000   
```
     
##### serve from github pages `gh-pages`
1. create gh-pages branch
2. delete master
3. make gh-pages the primary remote
4. push to gh-pages branch
5. `git checkout gh-pages`  


#### Issues: 
- [] generate index page via js.
     - current workaround is to add each exercise to the [index page](http://jaylab.io/a2z)

##### [My notes wiki](https://github.com/jaycody/a2z/wiki)  
##### [My exercises](http://jaylab.io/a2z/)


### shiffman A2Z links:
* [A2Z tutorials - video playlist](https://youtu.be/HRANU6KtNEs?list=PLRqwX-V7Uu6YrbSJBg32eTzUU50E2B8Ch)
* [shiffman's A2Z blog](http://shiffman.net/a2z/)  
* [A2Z homework - ITP - F16](https://github.com/shiffman/A2Z-F16/wiki)  
* [shiffman's A2Z-F16 repo](https://github.com/shiffman/A2Z-F16)  
* [A2Z References](https://github.com/shiffman/A2Z-F16/wiki/References)

### my notes wiki
* [a2z.wiki][2] --> main page
* [wk_1-strings](https://github.com/jaycody/a2z/wiki/wk_01-strings)
* [wk_2-regex](https://github.com/jaycody/a2z/wiki/wk_02-regex)

### my a2z gong-fu via gh-pages
* [jaylab.io/a2z](http://jaylab.io/a2z)

### vids, tuts, & articles
* [Ultimate JavaScript Strings](https://www.youtube.com/watch?v=ot4YGBG5Img)


------------



course overview
-----------

This course focuses on programming strategies and techniques behind procedural analysis and generation of text-based data. We'll explore topics ranging from evaluating text according to its statistical properties to the automated production of text with probabilistic methods to text visualization. Students will learn server-side and client-side JavaScript programming and develop projects that can be shared and interacted with online. There will be weekly homework assignments as well as a final project.


## Info
- Daniel Shiffman, Tuesdays, 9:00am-11:30am
- [All class dates](http://help.itp.nyu.edu/curriculum/fall-class-dates)
- [Office Hours](https://itp.nyu.edu/inwiki/Signup/Shiffman)
- In addition to the ITP physical class, I am running an online version of the class for [Patreon](patreon.com/codingrainbow) subscribers.  ITP students will receive a slack invite should they want to participate.  YouTube live stream sessions TBA.

## Mailing List
* [Join ITP A2Z Google Group](https://groups.google.com/a/nyu.edu/forum/#!forum/a2z-group/).  This is for the ITP physical class only.
* Contact me for an invite to the online slack channel.

## Week 1 - Intro
* [Notes and Examples](http://shiffman.net/a2z/intro/)
* Git, Github, Github pages
* DOM manipulation in p5.js
* Strings in JS
* Text input (from user, from file)
* Client-side vs. Server-side programming
* [Homework Assignment](https://github.com/shiffman/A2Z-F16/wiki/Week-1-Homework)

## Week 2 -- Regular Expressions
* Also
  * multiple DOMs + multiple event
  * rita.js -- similar and rhyming, etc.
* Regular Expressions
  * meta-characters
    * position
    * single character
    * quantifiers
    * character classes
    * alternation
    * capturing groups and back reference
  * Regex in atom editor
  * Regex in JS:
      * Regex: `test()`, `exec()`
      * String: `match()`
  * Splitting with regex: `split()`
  * Replace with regex: `replace()`
  * [randexp.js](http://fent.github.io/randexp.js/)
* Homework Assignment -- TBA

## Week 3 -- Data/API Workshop
* APIs
* Working with google sheets
* Parse (doesn't exist anymore, something else?)

## Week 4 -- Intro to Node and Twitter Bots
* Server side programming with Node
* Node data persistence
* html scraping
* How to make a Twitter bot
* Start working on Twitter Bot project

## Week 5 - Text Analysis Workshop
* In class, we'll build a simple concordance together as well as demonstrate and discuss TF/IDF and Bayesian analysis.
* Simple Concordance
* TF/IDF
* Bayesian Analysis
* Node text analysis packages

## Week 6 - Show Twitter Bots

## Week 7 - Text Generation: Markov chains
* Using google sheets for text input
* ngrams and markov chains

## Week 8 - Text Generation: Grammars
* Tracery by Kate Compton
* Context free grammars

## Week 9 - Chrome Extensions

## Week 10 - Building your own API in Node

## Week 11 - Final Project Proposals part 1

## Week 12 - Final Project Proposals part 2

## Week 13 - User Testing

## Week 14 - Final Presentations

## References and Inspiration
* Moved to [references wiki](https://github.com/shiffman/A2Z-F16/wiki/References)

## Tools
* [p5.js](http://p5js.org)
* [p5.js on GitHub](https://github.com/processing/p5.js)
* [p5.js CDN](http://cdnjs.com/libraries/p5.js)
* [Node](http://nodejs.org/)
* [RitaJS](https://github.com/dhowe/RiTaJS)

## JS reference books
* [JavaScript: The Definitive Guide](http://shop.oreilly.com/product/9780596000486.do)
* [Eloquent JavaScript](http://eloquentjavascript.net/contents.html), Marijn Haverbeke
* [Beginning JavaScript](http://www.amazon.com/Beginning-JavaScript-Paul-Wilton/dp/0470525932), Paul Wilton and Jeremy McPeak

## Learning / Intro
* [CodeAcademy: JavaScript](http://www.codecademy.com/tracks/javascript)
* [How to learn JavaScript properly](http://javascriptissexy.com/how-to-learn-javascript-properly/)
* [JavaScript the right way](http://www.jstherightway.org/)
* [Code School](https://www.codeschool.com/paths/javascript)
* [JavaScript garden](http://bonsaiden.github.io/JavaScript-Garden/)
* [A re-introduction to JS by Mozilla](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript)
* [JavaScript 101 from JQuery](https://learn.jquery.com/javascript-101/)

## Tools
* Checking code: [JSLint](http://www.jslint.com/) / [JSHint](http://www.jshint.com)
* Browser debugging: Chrome Developer Tools ([tutorial](https://developer.chrome.com/extensions/tut_debugging)) / Firebug ([tutorial](http://www.developerfusion.com/article/139949/debugging-javascript-with-firebug/))
* Mobile debugging [jsconsole.com](http://jsconsole.com)
* Sharing code snippets (useful for asking questions): [gist.github.com](http://gist.github.com)

## Requirements
* You are required to attend all class meetings and submit all weekly assignments and a final project.
* Grading (pass/fail) will be based on a combination of factors:
  * Attendance, participation in class discussion, and engagement in other students' projects (25%)
  * Quality of assignments (50%)
  * Final Project (25%)



[1]:https://github.com/shiffman/A2Z-F16
[2]:https://github.com/jaycody/a2z-f16/wiki
[3]:https://www.youtube.com/playlist?list=PLRqwX-V7Uu6YrbSJBg32eTzUU50E2B8Ch
[4]:https://www.npmjs.com/package/http-server
[5]:https://nodejs.org/en/#download
