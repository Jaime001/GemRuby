# How create a Ruby gem with ***Bundler***?
First we need to know what is a gem in Ruby, how works, and finally how create and install the gem.

## What is a Ruby gem?

A ***Ruby gem*** is like a library for Ruby and it could be installed in the system and after that, it's ready to being used inside of your ruby projects.

### What contains a gem?

* .gemspec
* /lib
* /spec (Test)
* /bin
* Documentation

### About .gemspec

> This file cointains all information about the gem:
- Name
- Version
- Summary
- Authors
- Email
- Description
- License

### About /lib
> In this file you can start your code with your main-file.rb and another folder if you're going to use helpers.

### About Documentation
> Contain some documentation about the gem and how to install it.


## What is Bundler?
> Bundler provides a consistent environment for Ruby projects by tracking and installing the exact gems and versions that are needed.
Documentation and downloads: https://bundler.io

### How install bundler?
Yo can start installing it with: ***bundle install.***
If we have Bundler already installed in our PC, we can create a gem in this steps;
> 1. Open your console and go to the directory that you want the gem.
 
> 2. Write this: bundle gem |Name|.

Next, automatically the gem will be created in the directory.
  
## The gem are ready to be used.
