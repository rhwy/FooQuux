# FooQuux Challenge- An Extreme FizzBuzz

The rules of FizzBuzz are quite simple. For a list of numbers from 1 to 100, when a number is a multiple of 3, you return “Fizz”, when it’s a multiple of 5, you return “Buzz”, when multiple of both you return “FizzBuzz”. In all other cases, you simply return the original number.

But what about pushing a little bit these limits ? 

## Here’s the rules

Take a list of numbers from 1 to 1000, and apply these rules for each input number:

* When number is a multiple of 3, return “Foo”,
* When number is a multiple of 5, return “Bar”,
* When number is a multiple of 7, return “Baz”,
* When number is a multiple of 11, return “Qux”,
* When number is a multiple of 13, return “Quux”,
* When number is a multiple of 17, return “Corge”,
* When number is a multiple of 19, return “Grault”,
* When number is a multiple of 23, return “Garply”,
* When number is a multiple of 29, return “Waldo”,
* When number is a multiple of 31, return “Fred”
* When an input number is a multiple of more than one of these rule numbers: 
    * apply all matching rules, and concatenate the values
* Otherwise, return the number

Discuss the design issues and problems involved by the great number of cases.

Exercice variants:

1. Start with a regular FizzBuzz, and add the new rules one by one to see incrementaly the initial design issues
2. Start with all the rules from scratch to see the impact on your initial design
3. Do the exercice without any loop or conditional instructions (no for, while, if, then, switch, etc…)


## References

* [Original FizzBuzz](http://codingdojo.org/kata/FizzBuzz/)
* [Variant FooBarQix](http://codingdojo.org/kata/FooBarQix/)
* [Etymology of "Foo"](https://www.ietf.org/rfc/rfc3092.txt)
* [Metasyntactic variable](https://en.wikipedia.org/wiki/Metasyntactic_variable)
