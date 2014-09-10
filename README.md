
# Ruby Methods

##Makers Academy | Week 9 | Challenge


##Table of Contents

* [General Description](#general-description)
* [Guidelines](#guidelines)
* [Testing](#testing)


This repo contians the answer for __Week 9 Friday Challange__ of the course 
at [Makers Academy](http://www.makersacademy.com/).

This particular challange was about writing effective [Ruby](https://www.ruby-lang.org/en/) 
methods.

It initially cosisted of 41 empty methods (or 'questions') for which we needed to write code 
so that the pre-defined tests will pass. 


##Guidelines

* There are 41 questions - you don't have to do every single one 
  (although if you can, that's great) 
* You should be able to do at least 50% of them. They vary in level from quite easy to 
  fairly hard
* You should be able to answer most questions with a couple of lines of code, 
  and just a few methods
* Get the RSpec tests to pass (but not by cheating - i.e. hardcoding the expected value)
* You shouldn't need any extra libraries or gems
* The last two methods cannot be tested by Rspec
* The cleaner your code the better!
* Googling is fine as usual


##Testing

Tests were written with [Rspec](http://rspec.info/) (3.0.2).

To run the testing suite in terminal: 

```bash
$> cd ruby_methods
$> rspec
```

To see the last two methods in action run the following commands in terminal:

```bash
$> irb
>> require './lib/questions.rb'
>> fizzbuzz_without_modulo
>> ninety_nine_bottles_of_beer
```
