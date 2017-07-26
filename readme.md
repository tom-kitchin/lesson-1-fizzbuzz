# Lesson 1 - FizzBuzz

## Getting started

This project requires PHP and [composer](https://getcomposer.org/download/).

* Clone the repo with `git clone git@github.com:tom-kitchin/lesson-1-fizzbuzz.git`
* Set up the project with `composer install` (or if composer isn't in your path, `php composer.phar install`)
* Run the tests with `bin/phpspec run`

## Completing the lesson

A simple coding task with provided tests to fulfil.

Each test has been commented out to disable it at first.

Aim to fulfil the tests in order according to Test Driven Development practices,
uncommenting each test in turn after the previous step is done. If you think of
something else which needs testing as you go or a feature you'd like to write,
feel free to write more tests.

Uncomment the first test, run it to see it fail, write just enough code to make it pass,
then check to see if you need to refactor your code, refactor to pass again, then
uncomment the next test and repeat.

Remember: Don't write code unless your tests fail,
don't refactor or write tests unless your existing tests pass.

## FizzBuzz spec

FizzBuzz counts from 1 to a given value, printing the current value unless
it divides by 3, in which case it prints Fizz, or it divides by 5, in which case
it prints Buzz. If it divides by both, it prints both.

This spec assumes an object called FizzBuzz which provides public methods as follows:

* `for($index)`, which returns as a string the FizzBuzz value at that index.
* `to($count)`, which returns an array of strings of the FizzBuzz count from 1 to the given value, inclusive.
