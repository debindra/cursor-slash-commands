# TDD Red Tool

Generate failing tests first (Red phase of TDD) with comprehensive coverage.

## Usage
/tdd-red [function or feature description]

## Example
/tdd-red create a function to calculate shipping costs

## Features

1. **Test Generation**
   - Write failing tests first
   - Cover happy path scenarios
   - Include edge cases
   - Test error conditions
   - Boundary value testing

2. **Test Structure**
   - Arrange-Act-Assert pattern
   - Descriptive test names
   - Test organization
   - Test fixtures
   - Mock setup

3. **Coverage**
   - Comprehensive test cases
   - Edge case coverage
   - Error scenario coverage
   - Integration test scenarios

## Output
- Failing test suite
- Test fixtures
- Mock configurations
- Test documentation

## Variables
$ARGUMENTS - Function or feature description

## Supported Frameworks
- JavaScript: Jest, Mocha, Vitest
- Python: pytest, unittest
- Java: JUnit, TestNG
- C#: NUnit, xUnit
- Go: testing package
- Rust: built-in tests

## Test Patterns
- Unit tests
- Integration tests
- Property-based tests
- Parameterized tests
- Test doubles (mocks, stubs)

