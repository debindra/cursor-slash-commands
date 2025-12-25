# Test Generate Tool

Generate comprehensive test suites for code with multiple testing strategies.

## Usage
/test-generate [file path or function name]

## Example
/test-generate src/utils/calculator.js

## Test Types Generated

1. **Unit Tests**
   - Function-level testing
   - Edge cases
   - Boundary conditions
   - Error handling

2. **Integration Tests**
   - Component interactions
   - API endpoint testing
   - Database operations
   - External service mocking

3. **E2E Tests**
   - User flow testing
   - Browser automation scenarios
   - Full stack testing

4. **Property-Based Tests**
   - Random input generation
   - Property verification
   - Fuzz testing

## Output
- Test files with comprehensive coverage
- Test fixtures and mocks
- Test utilities
- Coverage configuration
- Test documentation

## Variables
$ARGUMENTS - File path or function name

## Supported Frameworks
- JavaScript: Jest, Mocha, Vitest
- Python: pytest, unittest
- Java: JUnit, TestNG
- C#: NUnit, xUnit
- Go: testing package
- Rust: built-in tests

## Test Patterns
- AAA (Arrange, Act, Assert)
- Given-When-Then
- Test doubles (mocks, stubs, spies)
- Fixtures and factories
- Parameterized tests

