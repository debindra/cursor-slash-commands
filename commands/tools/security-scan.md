# Security Scan Tool

Comprehensive security vulnerability scanning and remediation.

## Usage
/security-scan [target: file, directory, or "project"]

## Example
/security-scan src/api/auth.js

## Scan Types

1. **Dependency Vulnerabilities**
   - Scan package.json, requirements.txt, etc.
   - Check for known CVEs
   - Suggest secure versions

2. **Code Vulnerabilities**
   - SQL injection risks
   - XSS vulnerabilities
   - CSRF protection
   - Authentication flaws
   - Authorization issues
   - Sensitive data exposure

3. **Secret Detection**
   - API keys in code
   - Passwords in plaintext
   - Database credentials
   - Private keys
   - OAuth tokens

4. **Configuration Security**
   - CORS misconfigurations
   - Security headers
   - SSL/TLS settings
   - Environment variables

## Output
- Vulnerability report with severity levels
- Affected code locations
- Remediation suggestions
- Code fixes
- Security best practices recommendations

## Variables
$ARGUMENTS - Target file, directory, or "project"

## Severity Levels
- Critical: Immediate action required
- High: Fix as soon as possible
- Medium: Fix in next release
- Low: Consider fixing

## Security Standards
- OWASP Top 10
- CWE Top 25
- SANS Top 25
- Framework-specific security guidelines

