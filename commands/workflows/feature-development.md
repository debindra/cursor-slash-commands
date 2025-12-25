# Feature Development Workflow

Complete end-to-end feature implementation with multi-agent coordination.

## Usage
/feature-development [feature description]

## Example
/feature-development implement user authentication with JWT tokens

## Workflow Steps

1. **Requirements Analysis Agent**
   - Analyze the feature description
   - Identify required components (backend, frontend, database, tests)
   - Determine technology stack and dependencies
   - Create implementation plan with file structure

2. **Backend Implementation Agent**
   - Generate API endpoints with proper HTTP methods
   - Create database models/migrations
   - Implement business logic with error handling
   - Add input validation and sanitization
   - Create service layer if needed

3. **Frontend Implementation Agent**
   - Create UI components with proper styling
   - Implement state management (Redux, Context, etc.)
   - Add form validation and user feedback
   - Create responsive layouts
   - Handle loading and error states

4. **Testing Agent**
   - Generate unit tests for all components
   - Create integration tests for API endpoints
   - Add E2E test scenarios
   - Ensure minimum 80% test coverage
   - Create test fixtures and mocks

5. **Documentation Agent**
   - Generate API documentation (OpenAPI/Swagger)
   - Create component documentation
   - Add inline code comments
   - Update README with new features
   - Document environment variables

6. **Security Review Agent**
   - Check for security vulnerabilities
   - Verify authentication/authorization
   - Review input validation
   - Check for sensitive data exposure

## Output
- Complete feature implementation across all layers
- Comprehensive test suite with coverage report
- API documentation
- Database migration files
- Configuration updates
- Security review report

## Variables
$ARGUMENTS - The feature description provided by the user

## Best Practices
- Follow existing code patterns in the project
- Maintain consistency with project structure
- Include error handling and logging
- Write self-documenting code
- Consider scalability and performance

