# Rails Interview Questions

I get a fair number of questions via [Hacker Hours](http://hackerhours.org) and elsewhere regarding what questions to use/expect in an interview for a Rails developer, so figured I would get it together in a tidy list.  Pull requests welcome.

## Tips

### Interviewers

* Personalize your list of questions.
* Don't ask questions you don't know the answers to.
* Mix trivia questions with open-ended ones.

### Interviewees

* Don't study to the test.  Not all of these questions will be used, and others will be asked that aren't covered here.  Know your stuff.
* Rails skills != CS skills
* Know whether you are interviewing for a full-stack vs. backend-focused position.
* Have code up on Github/Bitbucket/wherever - the more side projects you have to talk about, the better.
* Be comfortable with *some* version control system.
* Community awareness and resourcefulness can be as important as technical knowledge.

## The Questions

### General

* What is a tree?  What is a DAG?
* Pseudo-code depth-first and breadth-first search.
* Given a sorted array, what is the fastest way to find a element?  What is the Big-O time to do so?
* Explain how ajax works, hitting all parts of the stack. ([@abestanway](https://twitter.com/abestanway/status/278967644705677312))

### Ruby

* What is the difference between a lambda, a block and a proc? [I have gotten this one at every Ruby interview I've been in]
* How do you sort an Array of objects by a particular attribute?  What is a better way to do sorting with ActiveRecord?
* What are some of your favorite gems?  What are their alternatives?
* In Ruby, which is generally the better option: a recursive function or an iterative one?
* What are `#method_missing` and `#send`?  Why are they useful?
* What are the various Ruby runtimes, and how are they different?
* Define "Matz".

### Rails

* What is the general history of Rails?
* Explain the different pieces of Rails.
* Walk through the flow of a request through Rails.
* What are the different server options for running a Rails/Rack app?
* Explain CSRF and how Rails combats it.
* Explain mass-assignment vulnerability.
* Define "DHH".
* Define "tenderlove".
* Why do some people say "Rails can't scale"?
* What is Rack?
* What is middleware? How does it compare to controller filters/actions?
* Explain various forms of caching available in Rails.
* What are some Ruby web server options?
* On a scale of [@gorbypuff](https://twitter.com/gorbypuff) (0) to [@tenderlove](https://twitter.com/tenderlove) (10), how would you rate your Rails profiency? 

## Resources

(no particular order)

* [@darcyclarke](https://github.com/darcyclarke)'s [Frontend Interview Questions](https://github.com/darcyclarke/Front-end-Developer-Interview-Questions) (inspiration for this repo)
* My [Advanced JavaScript](https://github.com/afeld/advanced_js) class materials
* [Open Letter: Rails Interview Prep](http://afeld.me/nerdery/561078) from my blog
* [Video](http://afeld.me/nerdery/522101) of the Junior Developer Panel that I hosted
* [Ruby Koans](http://rubykoans.com/)
* [Project Euler](http://projecteuler.net/)
* [Flatiron School Prework](http://prework.flatironschool.com/) and [background](http://blog.flatironschool.com/post/37150595905/flatiron-school-prework)
* [Job Interview](https://github.com/ruby-jokes/job_interview) by @ruby-jokes

------------

<a rel="license" href="http://creativecommons.org/licenses/by/3.0/deed.en_US"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by/3.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">Rails Interview Questions</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/afeld/rails_interview_questions" property="cc:attributionName" rel="cc:attributionURL">Aidan Feldman</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/3.0/deed.en_US">Creative Commons Attribution 3.0 Unported License</a>.
