# Workflow Automate

Automate CI/CD pipelines and development workflows with best practices.

## Usage
/workflow-automate [workflow type] [requirements]

## Example
/workflow-automate CI/CD with testing, building, and deployment to staging and production

## Workflow Steps

1. **Workflow Analysis Agent**
   - Analyze project structure
   - Identify build requirements
   - Determine testing needs
   - Plan deployment strategy
   - Identify environment requirements

2. **Pipeline Design Agent**
   - Design CI/CD pipeline stages
   - Plan workflow triggers
   - Design approval gates
   - Plan rollback strategies
   - Design notification system

3. **Implementation Agent**
   - Generate CI/CD configuration
   - Create build scripts
   - Set up test automation
   - Configure deployment scripts
   - Set up environment configurations

4. **Security Agent**
   - Add secret management
   - Configure security scanning
   - Set up access controls
   - Add audit logging
   - Configure compliance checks

5. **Monitoring Agent**
   - Set up pipeline monitoring
   - Configure alerts
   - Add performance tracking
   - Set up logging
   - Create dashboards

## Output
- Complete CI/CD pipeline configuration
- Build and deployment scripts
- Environment configurations
- Security configurations
- Monitoring setup
- Documentation

## Variables
$ARGUMENTS - Workflow type and requirements

## Supported Platforms
- GitHub Actions
- GitLab CI
- Jenkins
- CircleCI
- Azure DevOps
- Bitbucket Pipelines
- AWS CodePipeline

## Pipeline Stages
- Build: Compile and build application
- Test: Run test suites
- Quality: Code quality checks
- Security: Security scanning
- Deploy: Deploy to environments
- Monitor: Post-deployment monitoring

