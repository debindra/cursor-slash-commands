# Full Review Workflow

Comprehensive multi-perspective code analysis and improvement suggestions.

## Usage
/full-review [file path or "current file"]

## Example
/full-review src/components/UserProfile.tsx

## Workflow Steps

1. **Architecture Review Agent**
   - Analyze code structure and organization
   - Check design patterns usage (MVC, MVVM, etc.)
   - Evaluate separation of concerns
   - Review module dependencies
   - Suggest architectural improvements
   - Check SOLID principles adherence

2. **Security Review Agent**
   - Scan for common vulnerabilities (OWASP Top 10)
   - Check input validation and sanitization
   - Review authentication/authorization logic
   - Identify potential security risks
   - Check for sensitive data exposure
   - Review error messages for information leakage

3. **Performance Review Agent**
   - Analyze time and space complexity
   - Check for memory leaks
   - Identify optimization opportunities
   - Review database queries (N+1 problems)
   - Check for unnecessary re-renders (React)
   - Analyze bundle size impact

4. **Code Quality Agent**
   - Check code style and consistency
   - Identify code smells (long methods, duplicate code, etc.)
   - Review error handling patterns
   - Check naming conventions
   - Suggest refactoring opportunities
   - Calculate cyclomatic complexity

5. **Best Practices Agent**
   - Verify framework-specific best practices
   - Check accessibility standards (WCAG)
   - Review testing coverage and quality
   - Ensure maintainability
   - Check for deprecated APIs
   - Verify TypeScript/type safety

6. **Documentation Agent**
   - Review inline documentation
   - Check JSDoc/TSDoc comments
   - Verify README accuracy
   - Suggest missing documentation

## Output
- Comprehensive review report with scores
- Prioritized improvement suggestions
- Code examples for fixes
- Refactoring recommendations
- Security vulnerability report
- Performance optimization suggestions
- Best practices checklist

## Variables
$ARGUMENTS - File path or "current file"

## Review Categories
- Architecture: Structure and design patterns
- Security: Vulnerabilities and risks
- Performance: Speed and efficiency
- Quality: Code smells and maintainability
- Best Practices: Framework and language standards
- Documentation: Code comments and docs

