# Java TDD Calculator

A Java test-driven development quiz with integer arithmetic, parity, and a month-length check. The `Calculator` and `DateChecker` APIs are exercised by JUnit 5 tests, including parameterized month cases.

## Build and test

Use JDK 17 or later and Maven. Run `mvn verify` to compile the library and execute its test suite.

## Behavior

The calculator uses Java `int` arithmetic. Division truncates toward zero and throws for a zero divisor. `DateChecker.has31Days` takes a `Month` enum value and rejects null.
