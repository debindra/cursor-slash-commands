# Cursor Slash Commands

A comprehensive collection of production-ready slash commands for Cursor that provides intelligent automation and multi-step orchestration capabilities for modern software development.

## Overview

This repository provides **35+ production-ready slash commands** (11 workflows, 24+ tools) that extend Cursor's capabilities through:

* **Workflows**: Multi-step orchestration systems that coordinate complex, multi-step operations across different domains
* **Tools**: Specialized single-purpose utilities for focused development tasks

## System Requirements

* Cursor IDE installed and configured
* Git for repository management (optional)

## Installation

### Option 1: Copy Commands to Cursor Directory

```bash
# Navigate to your workspace
cd /Users/deb/Documents/CursorPrompts

# The commands are already in the commands/ directory
# Cursor will automatically detect commands in the workspace
```

### Option 2: Symlink to Cursor Config (if supported)

```bash
# Create symlink to Cursor configuration directory
# Note: Adjust path based on your Cursor installation
ln -s /Users/deb/Documents/CursorPrompts/commands ~/.cursor/commands
```

## Command Invocation

Commands are organized in `workflows/` and `tools/` directories and can be invoked using:

### Workflow Commands

```
/workflows:feature-development implement user authentication with JWT
/workflows:smart-fix Fix memory leak in React component
/workflows:full-review src/components/UserProfile.tsx
/workflows:tdd-cycle create shipping cost calculator
/workflows:legacy-modernize src/utils/oldHelpers.js
/workflows:git-workflow feature "Add login page"
/workflows:api-design users CRUD operations
/workflows:improve-agent Optimize code review agent
/workflows:multi-platform user auth web, iOS, Android
/workflows:workflow-automate CI/CD with testing and deployment
/workflows:data-driven-feature recommendation system
```

### Tool Commands

```
/tools:api-scaffold products CRUD with pagination
/tools:security-scan src/api/auth.js
/tools:test-generate src/utils/calculator.js
/tools:docker-optimize Dockerfile
/tools:performance-analyze src/components/DataTable.tsx
/tools:doc-generate src/api/
/tools:db-migrate add user preferences table
/tools:refactor-extract function calculateTotal
/tools:k8s-manifest user-service with autoscaling
/tools:code-format src/utils/helpers.js
/tools:deps-upgrade react
/tools:env-setup production
/tools:ci-cd-setup github-actions with testing
/tools:component-generate UserCard functional
/tools:monitor-setup user-service with Prometheus
/tools:cost-optimize AWS infrastructure
/tools:data-pipeline ETL from S3 to Redshift
/tools:data-validation user registration data
/tools:tdd-red create shipping calculator
/tools:tdd-green implement to pass tests
/tools:tdd-refactor optimize while keeping tests green
/tools:context-save authentication-feature
/tools:context-restore authentication-feature
/tools:bundle-analyze dist/
/tools:lint-setup TypeScript with strict rules
```

## Command Architecture

### Workflows (11 commands)

Workflows implement multi-step orchestration patterns for complex, cross-domain tasks. Each workflow analyzes requirements, coordinates multiple steps, and ensures complete implementation.

#### Core Development Workflows

| Command             | Purpose                               | Steps                                    |
| ------------------- | ------------------------------------- | ---------------------------------------- |
| feature-development | End-to-end feature implementation     | Analysis, Backend, Frontend, Testing, Docs |
| smart-fix           | Intelligent problem resolution        | Analysis, Solution, Implementation, Verify |
| full-review         | Multi-perspective code analysis       | Architecture, Security, Performance, Quality |
| tdd-cycle           | Test-driven development orchestration | Red (Tests), Green (Code), Refactor, Verify |

#### Process Automation Workflows

| Command         | Purpose                    | Scope                                    |
| --------------- | -------------------------- | ---------------------------------------- |
| legacy-modernize| Codebase modernization     | Analysis, Modernization, Compatibility, Testing |
| git-workflow    | Version control automation | Branching, Commits, PR preparation, Quality |
| api-design      | Complete API design        | Design, Implementation, Documentation, Testing |
| improve-agent   | Agent optimization         | Analysis, Optimization, Testing, Documentation |
| multi-platform  | Cross-platform development | Platform Analysis, Shared Code, Platform-Specific, Integration |
| workflow-automate | CI/CD automation        | Analysis, Design, Implementation, Security, Monitoring |
| data-driven-feature | ML/data features      | Data Analysis, Pipeline, ML Model, API, Monitoring |

### Tools (24+ commands)

Tools provide focused, single-purpose utilities for specific development tasks.

#### Development Tools

| Command            | Purpose                      | Output                              |
| ------------------ | ---------------------------- | ----------------------------------- |
| api-scaffold       | Generate RESTful APIs        | Routes, Controllers, Models, Docs   |
| test-generate      | Generate test suites         | Unit, Integration, E2E tests       |
| component-generate | Generate UI components       | Component, Styles, Tests, Docs     |
| refactor-extract   | Extract reusable code        | Extracted code, Updated references |

#### Quality & Security Tools

| Command         | Purpose                    | Output                              |
| --------------- | -------------------------- | ----------------------------------- |
| security-scan   | Vulnerability scanning      | Security report, Fixes              |
| performance-analyze | Performance analysis    | Bottleneck report, Optimizations   |
| code-format     | Code formatting            | Formatted code, Config              |
| full-review     | Comprehensive code review  | Review report, Suggestions          |

#### Infrastructure Tools

| Command      | Purpose                    | Output                              |
| ------------ | -------------------------- | ----------------------------------- |
| docker-optimize | Optimize Dockerfiles    | Optimized Dockerfile, Metrics       |
| k8s-manifest | Generate K8s manifests     | Deployment, Service, ConfigMaps    |
| db-migrate   | Database migrations        | Migration files, Rollback scripts   |
| ci-cd-setup  | CI/CD pipeline setup       | Pipeline configs, Documentation     |

#### Maintenance Tools

| Command      | Purpose                    | Output                              |
| ------------ | -------------------------- | ----------------------------------- |
| deps-upgrade | Dependency upgrades        | Updated packages, Compatibility     |
| env-setup    | Environment configuration  | .env files, Documentation           |
| doc-generate | Documentation generation   | API docs, Code docs, Diagrams       |
| monitor-setup | Observability setup       | Metrics, Logging, Tracing, Alerts, Dashboards |
| cost-optimize | Cloud cost optimization    | Resource analysis, Optimization strategies, Recommendations |
| data-pipeline | Data processing pipelines  | ETL, Streaming, Batch, Data quality |
| data-validation | Data validation schemas  | Schema validation, Business rules, Quality checks |
| tdd-red | TDD Red phase (failing tests) | Test generation, Edge cases, Error scenarios |
| tdd-green | TDD Green phase (minimal code) | Minimal implementation, Test passing |
| tdd-refactor | TDD Refactor phase | Code optimization, DRY, Maintainability |
| context-save | Save project context | Context snapshot, Metadata, Storage |
| context-restore | Restore project context | Context retrieval, State restoration |
| bundle-analyze | Bundle size analysis | Size breakdown, Optimization suggestions, Visualization |
| lint-setup | Linting configuration | Linter setup, Code formatting, Pre-commit hooks |

## Usage Examples

### Complete Feature Development

```
/workflows:feature-development implement shopping cart with add, remove, and checkout functionality
```

This will:
1. Analyze requirements
2. Create backend API endpoints
3. Build frontend components
4. Generate comprehensive tests
5. Create documentation
6. Perform security review

### Smart Problem Resolution

```
/workflows:smart-fix Fix "Cannot read property 'map' of undefined" error in UserList component
```

This will:
1. Analyze the error
2. Identify root cause
3. Generate solution
4. Implement fix
5. Add tests
6. Document the issue

### Test-Driven Development

```
/workflows:tdd-cycle create a function to validate email addresses with domain checking
```

This will:
1. Write failing tests (Red)
2. Implement minimal code (Green)
3. Refactor for quality
4. Verify coverage

### Security Audit

```
/tools:security-scan src/api/
```

This will:
1. Scan for vulnerabilities
2. Check dependencies
3. Detect secrets
4. Review security configurations
5. Generate remediation report

## Command Selection Guide

### When to Use Workflows

| Task                             | Recommended Workflow       | Why                                    |
| -------------------------------- | ------------------------- | -------------------------------------- |
| "Build complete feature"         | feature-development        | Multi-tier implementation required     |
| "Debug production issue"         | smart-fix                 | Unknown root cause, needs analysis     |
| "Modernize legacy code"          | legacy-modernize          | Complex refactoring across stack       |
| "Review code quality"             | full-review               | Multi-perspective analysis needed      |
| "Implement with TDD"              | tdd-cycle                 | Test-first approach                    |

### When to Use Tools

| Task                             | Recommended Tool           | Output                                 |
| -------------------------------- | -------------------------- | -------------------------------------- |
| "Generate API endpoints"         | api-scaffold              | Complete API implementation            |
| "Audit security"                 | security-scan             | Vulnerability report with fixes         |
| "Create tests"                    | test-generate             | Comprehensive test suite                |
| "Optimize Docker"                | docker-optimize           | Optimized Dockerfile                   |
| "Generate docs"                  | doc-generate              | API and code documentation             |

## Best Practices

### Context Optimization

1. **Technology Stack**: Specify framework versions, database systems, deployment targets
2. **Constraints**: Define performance requirements, security standards, compliance needs
3. **Integration**: Specify external services, APIs, authentication methods
4. **Output Preferences**: Indicate coding standards, testing frameworks, documentation formats

### Command Chaining

1. **Progressive Enhancement**: Start with workflows for foundation, refine with tools
2. **Pipeline Construction**: Chain commands in logical sequence
3. **Iterative Refinement**: Use tool outputs as inputs for subsequent commands

### Performance Considerations

* Workflows typically require 30-90 seconds for complete orchestration
* Tools execute in 5-30 seconds for focused operations
* Provide detailed requirements upfront to minimize iteration cycles

## Technical Architecture

### Command Structure

Each slash command is a markdown file with the following characteristics:

| Component     | Description             | Example                                            |
| ------------- | ----------------------- | -------------------------------------------------- |
| **Filename**  | Determines command name | api-scaffold.md → /tools:api-scaffold              |
| **Content**   | Execution instructions  | Step-by-step workflow and agent prompts            |
| **Variables** | $ARGUMENTS placeholder  | Captures and processes user input                  |
| **Directory** | Command category        | tools/ for utilities, workflows/ for orchestration |

### File Organization

```
commands/
├── workflows/          # Multi-step orchestration commands
│   ├── feature-development.md
│   ├── smart-fix.md
│   ├── full-review.md
│   ├── tdd-cycle.md
│   ├── legacy-modernize.md
│   ├── git-workflow.md
│   ├── api-design.md
│   ├── improve-agent.md
│   ├── multi-platform.md
│   ├── workflow-automate.md
│   └── data-driven-feature.md
├── tools/             # Single-purpose utility commands
│   ├── api-scaffold.md
│   ├── security-scan.md
│   ├── test-generate.md
│   ├── docker-optimize.md
│   ├── performance-analyze.md
│   ├── doc-generate.md
│   ├── db-migrate.md
│   ├── refactor-extract.md
│   ├── k8s-manifest.md
│   ├── code-format.md
│   ├── deps-upgrade.md
│   ├── env-setup.md
│   ├── ci-cd-setup.md
│   ├── component-generate.md
│   ├── monitor-setup.md
│   ├── cost-optimize.md
│   ├── data-pipeline.md
│   ├── data-validation.md
│   ├── tdd-red.md
│   ├── tdd-green.md
│   ├── tdd-refactor.md
│   ├── context-save.md
│   ├── context-restore.md
│   ├── bundle-analyze.md
│   └── lint-setup.md
└── README.md          # This documentation
```

## Development Guidelines

### Creating New Commands

#### Workflow Development

1. **File Creation**: Place in `workflows/` directory with descriptive naming
2. **Step Orchestration**: Define multi-step process with clear phases
3. **Error Handling**: Include fallback strategies and error recovery
4. **Output Coordination**: Specify how outputs should be combined

#### Tool Development

1. **File Creation**: Place in `tools/` directory with single-purpose naming
2. **Implementation**: Provide complete, production-ready code generation
3. **Framework Detection**: Auto-detect and adapt to project stack
4. **Best Practices**: Include security, performance, and scalability considerations

### Naming Conventions

* Use lowercase with hyphens: `feature-name.md`
* Be descriptive but concise: `security-scan` not `scan`
* Indicate action clearly: `deps-upgrade` not `dependencies`
* Maintain consistency with existing commands

## Troubleshooting Guide

### Diagnostic Steps

| Issue                  | Cause                        | Resolution                                            |
| ---------------------- | ---------------------------- | ----------------------------------------------------- |
| Command not recognized | File missing or misnamed     | Verify file exists in correct directory               |
| Slow execution         | Normal workflow behavior     | Workflows coordinate multiple steps (30-90s typical) |
| Incomplete output      | Insufficient context         | Provide technology stack and requirements             |
| Integration failures   | Path or configuration issues | Check file paths and dependencies                     |

### Performance Optimization

1. **Context Caching**: Provide detailed context upfront
2. **Batch Operations**: Combine related tasks in single workflow
3. **Tool Selection**: Use tools for known problems, workflows for exploration
4. **Requirement Clarity**: Detailed specifications reduce iteration cycles

## Featured Command Implementations

### Test-Driven Development Suite

| Command      | Type     | Capabilities                                                          |
| ------------ | -------- | --------------------------------------------------------------------- |
| tdd-cycle    | Workflow | Complete red-green-refactor orchestration with test coverage analysis |
| tdd-red      | Tool     | Generate failing tests first with comprehensive coverage              |
| tdd-green    | Tool     | Implement minimal code to make tests pass                             |
| tdd-refactor | Tool     | Refactor code while keeping tests green                               |
| test-generate| Tool     | Comprehensive test generation with multiple testing strategies        |

**Framework Support**: Jest, Mocha, PyTest, RSpec, JUnit, Go testing, Rust tests

### Security and Infrastructure

| Command         | Specialization          | Key Features                                                       |
| --------------- | ----------------------- | ------------------------------------------------------------------ |
| security-scan   | Vulnerability detection | SAST/DAST analysis, dependency scanning, secret detection          |
| docker-optimize | Container optimization  | Multi-stage builds, layer caching, size reduction (50-90% typical) |
| k8s-manifest    | Kubernetes deployment   | HPA, NetworkPolicy, service mesh ready                            |

**Security Tools Integration**: OWASP Top 10, CWE Top 25, dependency scanning

### Data and Database Operations

| Command         | Database Support                     | Migration Strategies                           |
| --------------- | ------------------------------------ | ---------------------------------------------- |
| db-migrate      | PostgreSQL, MySQL, MongoDB, DynamoDB | Blue-green, expand-contract, versioned schemas |

**Zero-Downtime Patterns**: Rolling migrations, feature flags, dual writes, backfill strategies

## Additional Resources

### Documentation

* Cursor IDE Official Documentation
* Slash Commands Reference
* Best Practices Guide

### Integration Examples

```bash
# Complete feature development pipeline
/workflows:feature-development user authentication system
/tools:security-scan authentication implementation
/tools:test-generate authentication test suite
/tools:docker-optimize authentication service
/tools:k8s-manifest authentication deployment

# Code quality pipeline
/workflows:full-review src/
/tools:performance-analyze src/components/
/tools:code-format src/
/tools:doc-generate src/
```

## License

MIT License - See LICENSE file for complete terms.

## Support and Contribution

* **Issues**: Report issues or suggest improvements
* **Contributions**: Pull requests welcome following the development guidelines
* **Questions**: Open a discussion for questions

## About

A collection of production-ready slash commands for Cursor IDE that provides intelligent automation and multi-step orchestration capabilities for modern software development.

---

**Note**: These commands are designed to work with Cursor's AI capabilities. Ensure you have Cursor properly configured and that the commands directory is accessible to Cursor.

