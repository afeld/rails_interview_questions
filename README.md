# Rails Interview Questions

I get a fair number of questions via [Hacker Hours](http://hackerhours.org) and elsewhere regarding what questions to use/expect in an interview for a Rails developer, so figured I would get it together in a tidy list.  Pull requests welcome.

## Tips

### Interviewers

* Personalize your list of questions.
* Don't ask questions you don't know the answers to.
* Mix trivia questions with open-ended ones.
* Use [Codr](http://codr.io/) or a similar online collaborative text editor for doing coding challenges
    * Can be seen in real-time by remote team members
    * The unique URL with the solution can be easily sent around or added wherever you a tracking information about the candidate

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

### Rails

* What is the general history of Rails?
* What is new in Rails 4?
* Explain the different pieces of Rails.
* Walk through the flow of a request through Rails.
* What are the different server options for running a Rails/Rack app?
* Explain CSRF and how Rails combats it.
* Explain mass-assignment vulnerability.
* Why do some people say "Rails can't scale"?
* What is Rack?
* What is middleware? How does it compare to controller filters/actions?
* Explain various forms of caching available in Rails.
* What are some Ruby web server options?
* How is something like `30.seconds.ago` implemented? (c/o @harrisj)
* On a scale of "I've heard of it" (0) to "I maintain it" (10), how would you rate your Rails proficiency? 

## Resources

(no particular order)


* [@darcyclarke](https://github.com/darcyclarke)'s [Frontend Interview Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions) (inspiration for this repo)
* My [Advanced JavaScript](https://github.com/advanced-js/syllabus) class materials
* [Video](https://www.youtube.com/watch?v=xPY1uqq1cgk) of the Junior Developer Panel that I hosted
* [Ruby Koans](http://rubykoans.com/)
* [Project Euler](https://projecteuler.net/)
* [Flatiron School Prework](http://prework.flatironschool.com/) and [background](http://blog.flatironschool.com/flatiron-school-prework/)
* [Job Interview](https://github.com/ruby-jokes/job_interview) by @ruby-jokes
* [Developer Evangelist Interview Questions](https://github.com/MurtzaM/Developer-Evangelist-Interview-Questions)
* [Resources](http://hackerhours.org/resources.html) from Hacker Hours
* [Technical interview cheat sheet](https://gist.github.com/TSiege/cbb0507082bb18ff7e4b)

------------

<a rel="license" href="http://creativecommons.org/licenses/by/3.0/deed.en_US"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by/3.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">Rails Interview Questions</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/afeld/rails_interview_questions" property="cc:attributionName" rel="cc:attributionURL">Aidan Feldman</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/3.0/deed.en_US">Creative Commons Attribution 3.0 Unported License</a>.
