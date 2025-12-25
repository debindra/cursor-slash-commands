# Legacy Modernize Workflow

Modernize legacy codebase with incremental refactoring strategy and safety checks.

## Usage
/legacy-modernize [target file or directory]

## Example
/legacy-modernize src/utils/oldHelpers.js

## Workflow Steps

1. **Analysis Agent**
   - Identify legacy patterns and anti-patterns
   - Map dependencies and call sites
   - Assess modernization scope and risk
   - Detect deprecated APIs and libraries
   - Create detailed migration plan
   - Identify breaking changes

2. **Modernization Agent**
   - Convert to modern syntax (ES6+, TypeScript, etc.)
   - Update to current framework versions
   - Replace deprecated APIs with modern alternatives
   - Implement modern patterns (async/await, hooks, etc.)
   - Add type safety (TypeScript, PropTypes, etc.)
   - Update import/export statements

3. **Compatibility Agent**
   - Ensure backward compatibility where needed
   - Update dependent code
   - Maintain API contracts
   - Create migration guide
   - Add feature flags if needed
   - Test integration points

4. **Testing Agent**
   - Update existing tests
   - Add tests for new functionality
   - Ensure test coverage maintained
   - Create regression tests
   - Verify behavior unchanged

5. **Documentation Agent**
   - Document changes made
   - Update API documentation
   - Create migration guide
   - Document breaking changes
   - Update examples and tutorials

## Output
- Modernized code
- Migration plan and guide
- Updated tests
- Dependency updates
- Breaking changes documentation
- Rollback strategy

## Variables
$ARGUMENTS - Target file or directory path

## Modernization Patterns
- Callbacks → Promises → async/await
- var → let/const
- function declarations → arrow functions
- class components → functional components (React)
- CommonJS → ES modules
- jQuery → modern frameworks
- Vanilla JS → TypeScript

## Safety Measures
- Incremental changes
- Feature flags for gradual rollout
- Comprehensive testing
- Rollback plans
- Version control checkpoints

