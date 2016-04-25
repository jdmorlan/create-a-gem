# Lets Build a Gem

So...you want to build a gem! Awesome, I hope this repo of information and links will help 
you on your journey to build new gems and give back to the Ruby community that is so great. 

I have put together a list of links that I found helpful when I was creating my first gem. 
Also, this readme acts as a topical guide to building a gem. If you have any questions, 
please post an issue. 

## File Structure 

The basic file structure for a gem is relatively simple after you have seen it a couple 
of times. 

- lib/
  - traits.rb
  - traits/
- test/
  - test_helper.rb
- Rakefile
- LICENSE.txt
- gem-name.gemspec

### Lib

The lib folder contains all the coding goodness that is your gem! This is where you write the code that 
does whatever you are trying to solve. Generally speaking there are two major items in the lib folder. 

### Test

The test folder contains tests. Bet you didn't see that coming! I use minitest, but you can setup 
any test framework that you please. You can do TDD, BDD, but the most important part is that you 
test your gem. First off, more people are likely to use your gem if they see that it has tests, cause 
who wants to add more bugs into their project! 

### Rakefile 

The Rakefile lets you define tasks that are specific to your project. For example, you can setup a 
task that runs all your tests, or builds and installs the gem locally! 

### LICENSE.txt

### gem-name.gemspec
