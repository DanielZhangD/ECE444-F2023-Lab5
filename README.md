# Pros & Cons of Test Driven Development

## Pros:
- Bug Detection: With TDD, programmers can notice and fix bugs very early on. TDD forces programmers to write out tests prior to developing the actual code, which means that programmers must shape their code to match the tests. As a result, if the application fails the tests, that means that the programmer will be able to imemdiately catch any errors and fix them on the spot.
- Consistent Understanding/Documentation throughout: With test-driven documentation, because you have to write tests prior to implementing an app, that means you must have a stronger understanding for the design of the app itself (since programmers are testing the app before it's even written). As such, this forces higher levels of understanding, as many details must be hashed out prior to writing the rest of the code and thus creating an almost living documentation.
- Ability to future-proof and refactor easier: As tests are always there for every piece of code, that means that the code will practically be future-proofed, as all future functionality must pass the tests (and/or modify the tests for future purposes). In adition, TDD makes it so refactoring can be done easier - if a programmer makes a mistake while refactoring, the existence of the unit tests will ensure that those mistakes will be caught and no unintended side-effects may occur.

## Cons:
- Initial Time Investment: Many programmers (like me :) may not be too experience w/TDD and as such have to spend much more time in the initial stages of programming and development. As programmers must create their unit tests first before implementing any functionality, this means that functionality may be delayed, which can cause issues with time-sensitive projects.

- False sense of security/TDD is not a 100% guarantee: TDD w/unit tests does not guarantee that the code is flawless or perfect and free of bugs. TDD will only guarantee up to the features that are tested in the unit tests. As such, flawed unit tests will still lead to issues, with potential edge cases causing issues.
