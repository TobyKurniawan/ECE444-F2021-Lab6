# ECE444-F2021-Lab6

Deployed app can be found here: https://murmuring-fjord-18632.herokuapp.com/

## Pros and Cons of TDD

### Pros

With TDD, bugs are easier to catch at first, and designs must be more rigid and clear. The outputs must be known, thus forcing devs to think ahead about what code they are writing, and why they are writing it. In addition, your code must be more portable and modular. It is difficult to write tests for super functions, so by writing tests first, the functions being tested must be small enough and often satisfy the single responsibility principle more deliberately. In addition, TDD keeps code clean and maintainable - technical debt cannot pile up quickly as some form of test coverage is guaranteed. And finally, TDD ensures the developer knows what they are writing, as opposed to just blindly copying code. To write a test, the dev must know the ins and outs, the expected inputs and outputs of the code.

### Cons

Development slows down at first - you must spend more time designing, architecting, and thinking of valid use cases and tests for your functions. Also, tests can be very time consuming and difficult to write, especially beyond unit tests. E2E and integration tests are tricky to write, especially if you don’t even have anything tangible yet to fully integrate yet! UI tests can be hard to write at first too - since oftentimes you may not know what props and event handlers your components will have. Most of the cons of TDD can be attributed to the time and effort investment it requires initially - but the benefits reveal themselves as the project evolves and grows.
