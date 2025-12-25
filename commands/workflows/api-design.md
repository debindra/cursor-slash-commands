# API Design Workflow

Complete RESTful API design and implementation with best practices.

## Usage
/api-design [resource name] [operations]

## Example
/api-design users CRUD operations with authentication

## Workflow Steps

1. **API Design Agent**
   - Design RESTful endpoints
   - Define resource structure
   - Plan HTTP methods (GET, POST, PUT, DELETE, PATCH)
   - Design request/response schemas
   - Plan error handling strategy
   - Design pagination and filtering

2. **Implementation Agent**
   - Generate route handlers
   - Create controllers
   - Implement business logic
   - Add input validation
   - Implement error handling
   - Add logging

3. **Documentation Agent**
   - Generate OpenAPI/Swagger specification
   - Create API documentation
   - Add endpoint descriptions
   - Document request/response examples
   - Create Postman collection

4. **Testing Agent**
   - Generate API tests
   - Create integration tests
   - Add endpoint documentation tests
   - Test error scenarios
   - Test authentication/authorization

5. **Security Agent**
   - Add authentication middleware
   - Implement authorization checks
   - Add rate limiting
   - Validate input sanitization
   - Check for security headers

## Output
- Complete API implementation
- OpenAPI/Swagger documentation
- Test suite
- Postman collection
- Security implementation

## Variables
$ARGUMENTS - Resource name and operations

## API Best Practices
- RESTful design principles
- Proper HTTP status codes
- Consistent naming conventions
- Versioning strategy
- Error response format
- Pagination and filtering
- Rate limiting
- CORS configuration

