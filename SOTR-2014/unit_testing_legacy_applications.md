# Unit Testing Legacy Applications

## Kev McCabe - @bigmadkev - 5 June 2014 14:00

[slides](http://bit.ly/sotr14-testing)

Examples in talk are Coldfusion based

**Test Everything**

Mentions of Selenium

#### TDD

SRP - Single Responsibility Principle  
Functions should do one thing only and do it well

Run code coverage tools to check you have good coverage

Minimum code coverage should be 80%

Have fines in your team for breaking builds through failed unit tests  
For example, on tea duty all day or fined £1 a money goes to charity

#### Good Tests Are

- Understandable
- Maintainable
- Repeatable
- Necessary
- Granular
- Fast

Mentioned *Builder Pattern* from OO Patterns

Don't test twice. You might test a lib or file in one test then test it again later. DON'T  
Keep it fast. Slow testing hinders more than it helps!

Mock externals - DBs and APIs
External APIs and Systems should be tested inside their codebase not yours

TDD is hard, but all great tech disciplines are hard

#### BDD

Jasmine for JS  
Behat for PHP


**-Demo-**

