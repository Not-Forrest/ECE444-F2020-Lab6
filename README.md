# Forrest Zhang
This repo follows the examples outline in https://github.com/mjhea0/flaskr-tdd

# TDD Pros and Cons
Pros:
Test driven development keeps code modular because each feature needs to be tested individually, this encourage
programers to write them in a way that is easily separable. This helps with the Single Responsibility principle.
Requiring unit tests to be written first also ensures that there is enough testing throughout the project. Programmers
will not be scrambling to write tests at the end of the project. TDD also helps detect bugs in the code early, which
reduces the cost of these bugs. Having suites of tests also allows them to be used in automated regression testing.
This allows programmers to easily verify their code base everyday.

Cons:
During my PEY, I worked with teams that used TDD. One of the downside I experienced with TDD is that the
tests need to be maintained. Having a suite of tests for one variant of a product is easy to manage. However, there are
often multiple variants / products being developed in parallel. This leads to some overhead in managing which tests
are applicable to which products, which tests need to be modified, and if there are any testing condition should be excluded.
Another downside I experienced is that tests themselves can become very complex. Often the tests need to be debugged
as often as the product they are testing. Furthermore, upper management seems to be very keen on weekly regression results.
I feel this incentivizes too much having tests that can pass rather than tests to expose a weak area in the system.


# Heroku
Deployed here: https://nameless-springs-70725.herokuapp.com/

