# Lesson 1 - FizzBuzz

A simple coding task with provided tests to fulfil.

Each test has been disabled with an early return, which looks like:
```
return; // DELETE ME TO RUN TEST
```

Aim to fulfil the tests in order according to Test Driven Development practices,
enabling each test in turn by removing the early return line. If you think of
something else which needs testing as you go or a feature you'd like to write,
feel free to write more tests.

Enable the first test, run it to see it fail, write just enough code to make it pass,
then check to see if you need to refactor your code, refactor to pass again, then
enable the next test and repeat.

Remember: Don't write code unless your tests fail,
don't refactor or write tests unless your existing tests pass.

# FizzBuzz spec

FizzBuzz counts from 1 to a given value, printing the current value unless
it divides by 3, in which case it prints Fizz, or it divides by 5, in which case
it prints Buzz. If it divides by both, it prints both.

This spec assumes an object called FizzBuzz which provides public methods as follows:

`for($index)`, which returns as a string the FizzBuzz value at that index.
`to($count)`, which returns an array of strings of the FizzBuzz count from 1 to the given value, inclusive.
