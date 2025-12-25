# Environment Setup Tool

Generate environment configuration files with security best practices.

## Usage
/env-setup [environment type]

## Example
/env-setup production

## Features

1. **Environment Files**
   - .env.example template
   - Environment-specific configs
   - Secret management
   - Default values

2. **Configuration Management**
   - Environment variables
   - Configuration validation
   - Type checking
   - Required vs optional

3. **Security**
   - Secret detection
   - Secure defaults
   - Encryption recommendations
   - Access control

4. **Documentation**
   - Variable descriptions
   - Usage examples
   - Security notes
   - Setup instructions

## Output
- .env.example file
- Environment-specific configs
- Validation schemas
- Documentation
- Security recommendations

## Variables
$ARGUMENTS - Environment type (development, staging, production)

## Environment Types
- Development: Local development settings
- Staging: Pre-production testing
- Production: Live environment
- Testing: Test environment

## Security Best Practices
- Never commit secrets
- Use environment variables
- Encrypt sensitive data
- Rotate credentials regularly
- Use secret management services

