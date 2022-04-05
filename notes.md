WHY TEST
- testing imitigates regressions, situations whereby initially functioning features stop working for some reason
- allows refactoring with greater confidence(changing codes form without altering its functionality)
- Tests acts s the client of the application code, this way it helps determine the design and interface of the application alongside other system parts
- build your application incrementally

### Guidelines for testing first or last
- when the tests is simpler than the application code being  lean towards first
- when the desired behaviour is not yet as predicatble lean towards later
- since security is paramount incline towards writing security tests first
- when a bug is spotted, write a test to reproduce it to avoid regressions then write application code to fix it.
- lean against writing tests for code likely to change in the future
- write tests before refactoring code focus on testing error-prone code that is especially likely to break

This way we can conclude that we can lean towards writing model and controller tests and integration tests later