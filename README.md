# Cursor Slash Commands

A comprehensive collection of production-ready slash commands for Cursor that provides intelligent automation and multi-step orchestration capabilities for modern software development.

## Overview

This repository provides **36 production-ready slash commands** (11 workflows, 25 tools) that extend Cursor's capabilities through:

* **Workflows**: Multi-step orchestration systems that coordinate complex, multi-step operations across different domains
* **Tools**: Specialized single-purpose utilities for focused development tasks

## System Requirements

* Cursor IDE installed and configured
* Git for repository management (optional)

## Installation

### For Cursor IDE

Cursor automatically detects slash commands in your workspace. To use these commands:

1. **Option 1: Use commands in current workspace**
   - Commands in the `commands/` directory are automatically available
   - Type `/` in Cursor's chat to see available commands
   - Commands are invoked directly like `/command-name` (e.g., `/feature-development`)

2. **Option 2: Copy to .cursor directory** (for global access)
   ```bash
   # Copy commands to Cursor's config directory
   mkdir -p ~/.cursor/commands
   cp -r commands/* ~/.cursor/commands/
   ```

3. **Option 3: Symlink for easy updates**
   ```bash
   # Create symlink (adjust path as needed)
   ln -s $(pwd)/commands ~/.cursor/commands
   ```

**Note:** Each command file contains an executable prompt template. When you invoke a command, Cursor uses the prompt in that file to guide the AI's response.

## Command Invocation

All commands are in the `commands/` directory and can be invoked directly:

### Workflow Commands

```
/feature-development implement user authentication with JWT
/smart-fix Fix memory leak in React component
/full-review src/components/UserProfile.tsx
/tdd-cycle create shipping cost calculator
/legacy-modernize src/utils/oldHelpers.js
/git-workflow feature "Add login page"
/api-design users CRUD operations
/improve-agent Optimize code review agent
/multi-platform user auth web, iOS, Android
/workflow-automate CI/CD with testing and deployment
/data-driven-feature recommendation system
```

### Tool Commands

```
/api-scaffold products CRUD with pagination
/security-scan src/api/auth.js
/test-generate src/utils/calculator.js
/docker-optimize Dockerfile
/performance-analyze src/components/DataTable.tsx
/doc-generate src/api/
/db-migrate add user preferences table
/refactor-extract function calculateTotal
/k8s-manifest user-service with autoscaling
/code-format src/utils/helpers.js
/deps-upgrade react
/env-setup production
/ci-cd-setup github-actions with testing
/component-generate UserCard functional
/monitor-setup user-service with Prometheus
/cost-optimize AWS infrastructure
/data-pipeline ETL from S3 to Redshift
/data-validation user registration data
/tdd-red create shipping calculator
/tdd-green implement to pass tests
/tdd-refactor optimize while keeping tests green
/context-save authentication-feature
/context-restore authentication-feature
/bundle-analyze dist/
/lint-setup TypeScript with strict rules
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

### Tools (25 commands)

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
| lint-setup      | Linting configuration      | Linter setup, Code formatting, Pre-commit hooks |

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
/feature-development implement shopping cart with add, remove, and checkout functionality
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
/smart-fix Fix "Cannot read property 'map' of undefined" error in UserList component
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
/tdd-cycle create a function to validate email addresses with domain checking
```

This will:
1. Write failing tests (Red)
2. Implement minimal code (Green)
3. Refactor for quality
4. Verify coverage

### Security Audit

```
/security-scan src/api/
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

Each slash command is a markdown file containing an executable prompt template:

| Component     | Description             | Example                                            |
| ------------- | ----------------------- | -------------------------------------------------- |
| **Filename**  | Determines command name | api-scaffold.md → /api-scaffold              |
| **Content**   | Executable prompt       | The actual prompt/instructions Cursor AI will execute |
| **Variables** | $ARGUMENTS placeholder  | Captures and processes user input when command is invoked |
| **Directory** | Command location        | All commands are in the `commands/` directory |

**How it works:**
- When you type `/feature-development implement auth`, Cursor loads the prompt from `commands/feature-development.md`
- The `$ARGUMENTS` placeholder is replaced with "implement auth"
- Cursor's AI executes the prompt with your arguments

### File Organization

```
commands/
├── feature-development.md    # Workflow: End-to-end feature implementation
├── smart-fix.md              # Workflow: Intelligent problem resolution
├── full-review.md            # Workflow: Comprehensive code review
├── tdd-cycle.md              # Workflow: Test-driven development
├── legacy-modernize.md       # Workflow: Codebase modernization
├── git-workflow.md           # Workflow: Git automation
├── api-design.md             # Workflow: Complete API design
├── improve-agent.md          # Workflow: Agent optimization
├── multi-platform.md         # Workflow: Cross-platform development
├── workflow-automate.md      # Workflow: CI/CD automation
├── data-driven-feature.md    # Workflow: ML/data features
├── api-scaffold.md           # Tool: Generate RESTful APIs
├── security-scan.md          # Tool: Vulnerability scanning
├── test-generate.md          # Tool: Generate test suites
├── docker-optimize.md        # Tool: Optimize Dockerfiles
├── performance-analyze.md    # Tool: Performance analysis
├── doc-generate.md           # Tool: Documentation generation
├── db-migrate.md             # Tool: Database migrations
├── refactor-extract.md       # Tool: Extract reusable code
├── k8s-manifest.md           # Tool: Kubernetes manifests
├── code-format.md            # Tool: Code formatting
├── deps-upgrade.md           # Tool: Dependency upgrades
├── env-setup.md              # Tool: Environment configuration
├── ci-cd-setup.md            # Tool: CI/CD pipeline setup
├── component-generate.md     # Tool: UI component generation
├── monitor-setup.md          # Tool: Observability setup
├── cost-optimize.md          # Tool: Cloud cost optimization
├── data-pipeline.md          # Tool: Data processing pipelines
├── data-validation.md        # Tool: Data validation schemas
├── tdd-red.md                # Tool: TDD Red phase
├── tdd-green.md              # Tool: TDD Green phase
├── tdd-refactor.md           # Tool: TDD Refactor phase
├── context-save.md            # Tool: Save project context
├── context-restore.md         # Tool: Restore project context
├── bundle-analyze.md          # Tool: Bundle size analysis
├── lint-setup.md             # Tool: Linting configuration
└── README.md                 # This documentation
```

## Development Guidelines

### Creating New Commands

#### Workflow Development

1. **File Creation**: Place in `commands/` directory with descriptive naming
2. **Step Orchestration**: Define multi-step process with clear phases
3. **Error Handling**: Include fallback strategies and error recovery
4. **Output Coordination**: Specify how outputs should be combined

#### Tool Development

1. **File Creation**: Place in `commands/` directory with single-purpose naming
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
/feature-development user authentication system
/security-scan authentication implementation
/test-generate authentication test suite
/docker-optimize authentication service
/k8s-manifest authentication deployment

# Code quality pipeline
/full-review src/
/performance-analyze src/components/
/code-format src/
/doc-generate src/
```

## License

MIT License - See LICENSE file for complete terms.

## Support and Contribution

* **Issues**: Report issues or suggest improvements
* **Contributions**: Pull requests welcome following the development guidelines
* **Questions**: Open a discussion for questions

## About

A collection of **36 production-ready slash commands** for Cursor IDE that provides intelligent automation and multi-step orchestration capabilities for modern software development.

### How It Works

These commands are executable prompt templates designed for Cursor IDE. Each `.md` file contains a prompt that guides Cursor's AI when the command is invoked:

1. **Invoke Command**: Type a slash command in Cursor's chat (e.g., `/feature-development implement auth`)
2. **Load Prompt**: Cursor loads the corresponding `.md` file from the `commands/` directory
3. **Replace Variables**: Cursor replaces `$ARGUMENTS` with your input
4. **Execute**: Cursor's AI executes the prompt with your project context

### Requirements

- Cursor IDE installed and configured
- Commands directory accessible to your workspace (either in project or `~/.cursor/commands/`)
- Git for repository management (optional)

---

**Total Commands**: 36 (11 Workflows + 25 Tools)

For a quick reference, see [QUICK_REFERENCE.md](commands/QUICK_REFERENCE.md).

