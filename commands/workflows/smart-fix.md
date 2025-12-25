# Smart Fix Workflow

Intelligent problem resolution with dynamic agent selection based on issue type.

## Usage
/smart-fix [problem description or error message]

## Example
/smart-fix Fix memory leak in React component causing performance issues

## Workflow Steps

1. **Problem Analysis Agent**
   - Parse error messages or problem description
   - Identify root cause through code analysis
   - Determine affected components and files
   - Classify issue type (bug, performance, security, memory leak, etc.)
   - Trace error stack if available

2. **Solution Generation Agent**
   - Generate multiple solution approaches
   - Evaluate pros/cons of each approach
   - Consider impact on existing code
   - Select optimal solution based on best practices
   - Create step-by-step implementation plan

3. **Fix Implementation Agent**
   - Apply the fix with minimal changes
   - Ensure backward compatibility
   - Add defensive coding and error handling
   - Update related code if needed
   - Add logging for debugging

4. **Verification Agent**
   - Generate test cases for the fix
   - Verify fix doesn't break existing functionality
   - Run existing test suite
   - Check for similar issues in codebase
   - Suggest preventive measures

5. **Documentation Agent**
   - Document the issue and solution
   - Add comments explaining the fix
   - Update changelog if needed
   - Create prevention guidelines

## Output
- Fixed code with explanation
- Test cases verifying the fix
- Documentation of issue and solution
- Recommendations for prevention
- Similar issues found in codebase (if any)

## Variables
$ARGUMENTS - Problem description or error message

## Issue Types Handled
- Memory leaks
- Performance bottlenecks
- Security vulnerabilities
- Logic errors
- Race conditions
- Null pointer exceptions
- Type errors
- API compatibility issues

