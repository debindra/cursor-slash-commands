# TDD Cycle Workflow

Complete Test-Driven Development orchestration (Red-Green-Refactor cycle).

## Usage
/tdd-cycle [feature or function description]

## Example
/tdd-cycle create a function to calculate shipping costs based on weight and distance

## Workflow Steps

1. **Red Phase - Test Writing Agent**
   - Write failing tests first (red)
   - Cover happy path scenarios
   - Include edge cases and boundary conditions
   - Test error conditions
   - Set up test framework if needed
   - Create test fixtures and mocks
   - Ensure tests are descriptive and readable

2. **Green Phase - Implementation Agent**
   - Write minimal code to pass tests
   - Focus on making tests pass (green)
   - Avoid premature optimization
   - Keep implementation simple
   - Ensure all tests pass
   - Verify test coverage

3. **Refactor Phase - Optimization Agent**
   - Improve code quality without changing behavior
   - Remove code duplication (DRY principle)
   - Optimize performance if needed
   - Improve readability and maintainability
   - Extract methods/functions if appropriate
   - Maintain 100% test coverage
   - Ensure all tests still pass

4. **Verification Agent**
   - Run full test suite
   - Check test coverage (aim for 100%)
   - Verify code quality metrics
   - Ensure no regressions
   - Check for test quality (not just quantity)

## Output
- Test suite (failing initially, then passing)
- Implementation code (minimal, then refactored)
- Test coverage report
- Code quality metrics
- Refactoring suggestions

## Variables
$ARGUMENTS - Feature or function description

## Supported Test Frameworks
- JavaScript/TypeScript: Jest, Mocha, Vitest
- Python: pytest, unittest
- Java: JUnit, TestNG
- C#: NUnit, xUnit
- Go: testing package
- Rust: built-in test framework

## TDD Principles
1. Write a failing test first
2. Write minimal code to pass
3. Refactor while keeping tests green
4. Repeat the cycle

