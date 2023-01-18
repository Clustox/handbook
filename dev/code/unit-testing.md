# Unit Testing Strategies

A unit test validates and verifies individual software units (or components) to ensure each unit works as intended. A unit may be a function, procedure, method, object, or module. Unit testing occurs during the coding phase of the software development lifecycle, and can help identify coding errors, code quality issues, and security issues.

## TDD:

The recommended approach to write unit test is to follow Test Driven Development process.

TDD includes:

1. Begin with writing a failing test for the functionality that you want to implement.
2. Then, write the new code to implement the functionality and make sure all tests pass after your changes. 
3. The last step is the refactor phase. In this phase, you eliminate duplication in the new code and make it clean.

## TDD Best Practices:

- Make sure each test fails initially
- Write a test before writing production code
- Write independent tests
- Automate tests
- Use test doubles to reduce coupling
- Know when to use TDD

## Backend:

We mostly use Ruby on Rails for our backend development.

And for Ruby on Rails code we recommend using [Rspec](https://rspec.info/) for writing unit tests for your application.

Rspec Best Practices:

- [Describe your methods](https://github.com/abinoda/rspec-best-practices#describe-your-methods)
- [Use Context](https://github.com/abinoda/rspec-best-practices#use-context)
- [Only one expectation per example](https://github.com/abinoda/rspec-best-practices#only-one-expectation-per-example)
- [Test valid, edge and invalid cases](https://github.com/abinoda/rspec-best-practices#test-valid-edge-and-invalid-cases)
- [Use let](https://github.com/abinoda/rspec-best-practices#use-let)
- [DRY](https://github.com/abinoda/rspec-best-practices#dry)
- [Optimize database queries](https://github.com/abinoda/rspec-best-practices#optimize-database-queries)
- [Use factories](https://github.com/abinoda/rspec-best-practices#use-factories)
- [Choose matchers based on readability](https://github.com/abinoda/rspec-best-practices#choose-matchers-based-on-readability)
- [Run specific tests](https://github.com/abinoda/rspec-best-practices#run-specific-tests)
- [Debug Capybara tests with save_and_open_page](https://github.com/abinoda/rspec-best-practices#debug-capybara-tests-with-save_and_open_page)
- [Only enable JS in Capybara when necessary](https://github.com/abinoda/rspec-best-practices#only-enable-js-in-capybara-when-necessary)
- [Consult the logs](https://github.com/abinoda/rspec-best-practices#consult-the-logs)

## Frontend:

TODO: JS Testing tools
