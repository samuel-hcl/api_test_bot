# api_test_bot
A simple framework for writing client-side REST API tests.

Tests from the point of view of API consumers (clients).

Simple and productive by using conventions to write tests.

Entities modeling provides responsibility separations.

## features
- written in ruby
- uses [RSpec](https://github.com/rspec/rspec) to run tests
- uses [parallel_tests](https://github.com/grosser/parallel_tests) to run tests in parallel
- uses [curb](https://github.com/taf2/curb) as HTTP client (the fastest client for ruby)
- uses [oj](https://github.com/ohler55/oj) to parse JSON (the fastest JSON parser for ruby)
- uses [hash_validator](https://github.com/jamesbrooks/hash_validator) for [contract tests](https://martinfowler.com/bliki/ContractTest.html)
- logs all HTTP requests made by the tests
