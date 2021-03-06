Check out the links below for more information on creating your own gems. 

# Whats a Gemspec 

The Gemspec defines all the metadata about your gem. This allows the internals 
of a Gem to work properly, but it also allows you to easily publish your 
gem to RubyGems. 

[Specification Reference](http://guides.rubygems.org/specification-reference/)


# Choose a License 

Picking a license is important when building any type of software, but 
certainly when creating an open source project. You want to make sure 
users understand what they are agreeing to when it comes time for them 
to add your project as a dependency. 

[Choose a License](http://choosealicense.com/)

# How to build a Gem 

[Nick Quaranto](https://github.com/qrush) did a great write up on creating 
a gem. Alot of what I am showing is based on his write up. If you ever 
need something to go back to for the basics, this is it! 

[Ruby Gems - How To](http://guides.rubygems.org/make-your-own-gem/)

[Source Code](https://github.com/qrush/hola)

# Ruby Gems API 

The Ruby Gems API can be used to setup a custom workflow for deploying or yanking 
your gem. For example, you could setup a script to check the CI build is valid then 
automagically upload the new version of the gem to RubyGems. There is also a gem 
that wraps the API, so you can easily call it from Ruby land without using an HTTP 
gem. 

[Ruby Gems API Docs](http://guides.rubygems.org/rubygems-org-api/)

[Ruby Gems API Gem](https://github.com/rubygems/gems)

